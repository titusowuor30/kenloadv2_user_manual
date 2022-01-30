# mkdocs-example with django

## The docs has been customized with django but can still be run as standalone

### Follow the steps bellow to run as standalone in windows enviroment

- Steps

#### Install python and create a viryual enviroment

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
cd mkdocs-example
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
