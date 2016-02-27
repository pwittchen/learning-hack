learning-hack
=============
learning basics of Hack programming language by Facebook

Setup on Linux
--------------

**Install required software**

Hint: *this operation needs to be run only once*

```
make install
```

**Run typechecker**

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

You should see `Hello Hack!` message

Type `Ctrl+C` in terminal to stop server. Optionally, type `make clean` to remove temporary files.

Sample program
--------------

```hack
<?hh
echo "Hello Hack!";

```

References
----------
http://hacklang.org/ - official website of the Hack language
