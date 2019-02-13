<!-- $theme: default -->
<!-- footer: #python - 01  -->
<!-- $size: 16:9 -->
<!-- page_number: true -->

# Running python

If you already have `python3` on your machine, you can directly move on to the Questions sections.

# Check if you already have python

* **Linux (Ubuntu, Debian, ...)** : Open a terminal, input `python3`
* **Windows** : Open the **Start** menu, write `python`
* **MacOS** : Open a terminal, input `python3`

---

# Installing Python

The first step into programming is to get Python installed on your Virtual Machine (VM). You will need two things:

* Python itself
* An IDE (Interactive Development Environment)

---

## Ubuntu (Linux)

### python3

By default, Python is already installed. In this tutorial however, we will use Python3 whenever possible. You can install it from a terminal window (`Ctrl`+`Alt`+`T`) with: 

    sudo apt-get install python3

If you are using our VM, you already have python, this is in case you ever need to install it.

To check whether everything worked, type:

    python3

This will take you to the interactive console.

---

### Code editor

If you open a terminal and type `gedit`. It will open the text editor **gedit**.

As a text editor, it is fine to start with **gedit**. Please make sure to change tabs to spaces via *Edit -> Preferences -> Editor -> tick 'Insert spaces instead of tabs'* [(Want to learn more about this?](001b-space-tabs.md)).

Later, we will use a text editor with more features that will be helpful for python code writing.

---

## Question


> Which python version are you running?

Check your python version by typing (in the terminal): 
```
python3 --version
```
You should see something like `Python 3.6.7`.
It is important that your python version is superior to 3.5 at least.

---

## On Windows

A convenient way to install Python, an editor and many additional packages in one go is [**Anaconda**](https://store.continuum.io/cshop/anaconda/), a Python distribution with many pre-installed packages for scientific applications.

---