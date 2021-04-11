# app.env
Build your own python environment from source (and forget about virtualenv)

## Prerequisite

Install additional packages on your debian first by running:

```
sudo xargs -a debian-packages.txt apt install -y
```

## Usage

1. Create your project dir, for ex. `app1`:

```
mkdir $HOME/proj/app1
```

2. pull this repo into it this way:

```
cd $HOME/proj/app1
git clone git@github.com:TheCoderHouse/app.env.git env
```

3. cd into this newly created directory by typing:

```
cd env
```

4. Create your own version of `Makefile` by simply copying contents of `Makefile.sample`

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



