# app.env
Build your own python environment from source (and forget about virtualenv)

## Prerequisite

Install additional packages on your debian first by running:

```
sudo xargs -a debian-packages.txt apt install -y
```

## Usage

### Create your project dir
Create your project dir, for ex. `app1`:

```
mkdir $HOME/proj/app1
```

### Pull this repo into it this way:

```
cd $HOME/proj/app1
git clone git@github.com:TheCoderHouse/app.env.git env
```

### Go to this dir
cd into this newly created directory by typing:

```
cd env
```

### Copy contents of `Makefile.sample`
Simply copy contents of `Makefile.sample` to your own `Makefile`

```
cp Makefile.sample Makefile
```

### Modify `Makefile`
Edit it with vim, nano, joe or and editor of your choice:

```
vim Makefile
```

### Build your environment
Finally run `make`:

```
make
```



