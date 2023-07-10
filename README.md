# Hello world

This is a simple hello world tutorial to highlight how java code can be compiled and run.  

All the bellow commands are expected to be run from the root of the repository.

## Compile

The source code for this project is located in the [src](src) directory. In order to compile it run the following
command:

```shell
javac src/* -d out
```

In the above command the following parameters passed to `javac` command:

* `src/*` the path containing the classes to be compiled
* `-d out` the directory where the generated files should be placed

## Run

Once the above command was used to compile an `out` folder will be created with `HelloWorld.class` file. In order to run
it use the following command:

```shell
java -cp out HelloWorld
```

In the above command `-cp` is used to specify the classpath (in our case we want to provide the contents of the `out`
directory) and `HelloWorld` represents the name of the class in which the `main` method to be called is located.
