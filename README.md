This project is the first step towards building a full web application of the AirBnB clone. In this first step we are building a console, a custom command interpreter that will be used in subsequent AirBnB projects to manage objects of our classes.

This console will allow us to do the following:

* Create a new object
* Retrieve an object from a file, a database etc…
* Do operations on objects (count, compute stats, etc…)
* Update attributes of an object
* Destroy an object


## Usage

* The console can be run in both interactive and non-interactive mode.
* It prints a prompt **(hbnb)** and waits for the user for input.

### Interactive Mode:
```
### Interactive Mode

```cmd
$ ./console.py
(hbnb) help
@@ -33,8 +35,9 @@ EOF  help  quit
$
```

### Non-Interactive Mode:
```
### Non-Interactive Mode

```cmd
$ echo "help" | ./console.py
(hbnb)
@@ -56,8 +59,8 @@ EOF  help  quit
$
```


## Commands

Command | Description
--- | ---
`quit` | Exits the program
@@ -73,7 +76,6 @@ Command | Description
`<class>.show(<id>)` | Retrieves an instance based on its id
`<class>.destroy(<id>)` | Destroys an instance based on its id


---

## Authors