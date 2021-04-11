# app.env
Build your own python environment from source (and forget about virtualenv)

## Prerequisite

Install additional packages on your debian first by running:

```
sudo xargs -a debian-packages.txt apt install -y
```

## Usage

* Create your project dir, for ex. `/home/user/proj/app1`

* pull this repo into it this way:

```
git clone git@github.com:TheCoderHouse/app.env.git env
```

* cd into newly created directory by typing `cd env`

* create your own version of `Makefile` by simply copying contents of `Makefile.sample`

```
cp Makefile.sample Makefile
```

* edit it with vim, nano, joe or and editor of your choice:

```
vim Makefile
```

* Finally run `make`:

```
make
```



