#[KENYA NATIONAL HIGHWAYS AUTHORITY](https://kenha.co.ke)
## Weighbridge & Axle Load Management Software(Kenload) v2 User Manual

### Set UP

- Steps

#### Install python and create a virtual enviroment

```shell
#install virtualenv
py -m pip install --user virtualenv
#create virtaul enviroment
py -m venv env
#activate it
.\env\Scripts\activate
```

#### Clone the repo

```shell
git clone https://github.com/titusowuor30/kenloadv2_user_manual.git
```

#### move into the project directory

```shell
cd kenloadv2_user_manual
```

#### install requirements

```shell
pip install -r requirements.txt
```

#### buid the docs

```script
mkdocs build
```

#### run the server

```shell
mkdocs serve
```
