learning-hack
=============
learning basics of Hack programming language by Facebook

Contents
--------
- [Setup on Linux](#setup-on-linux)
- [Sample program](#sample-program)
- [References](#references)

Setup on Linux
--------------

**Install required software**

You can perform [manual installation](https://docs.hhvm.com/hhvm/installation/linux) or use Makefile from this repository.

Hint: *this operation needs to be run only once*

```
make install
```

**Run [typechecker](https://docs.hhvm.com/hack/typechecker/introduction)**

Hint: *this operation needs to be run only once*

```
make typechecker
```

**Run server**

```
make server
```

**Check if everything works**

Open your favorite broweser and go to: `http://localhost:8080/hello.php`

You can also open another terminal window and use curl:

```
curl http://localhost:8080/hello.php
```

You should see `Hello Hack!` message

Type `Ctrl+C` in terminal to stop server. Optionally, type `make clean` to remove temporary files.

Sample program
--------------

File: `hello.php`

```hack
<?hh
echo "Hello Hack!";

```

References
----------
- [Hack](http://hacklang.org/)
- [Getting started with Hack](https://docs.hhvm.com/hack/getting-started/getting-started)
- [HHVM](http://hhvm.com/)
- [Getting started with HHVM](https://docs.hhvm.com/hhvm/getting-started/getting-started)
- [Source code of HHVM](https://github.com/facebook/hhvm)
