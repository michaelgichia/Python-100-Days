## Day01 - First Python

### Introduction to Python

#### Python history

1. Christmas 1989: Guido von Rossum began writing compilers for the Python language.
2. February 1991: The first Python compiler (also an interpreter) was born, which was implemented in C (there were Java and C# implementations of Jython and IronPython, and PyPy, Brython, Pyston, etc.). Other implementations), you can call library functions in C language. In the earliest versions, Python already provided support for building blocks such as "class", "function", "exception handling", and provided core data types such as "list" and "dictionary", while supporting module-based. Expansion system.
3. January 1994: Python 1.0 is officially released.
4. October 16, 2000: Python 2.0 released, adding a complete [garbage collection] (https://en.wikipedia.org/wiki/Garbage_collection_(computer_science)), provided for [Unicode]( Support for https://zh.wikipedia.org/wiki/Unicode). At the same time, the entire development process of Python is more transparent, the community's influence on the development progress is gradually expanding, and the ecosystem is slowly forming.
5. December 3, 2008: Python 3.0 is released, it is not fully compatible with previous Python code, but because there are still many companies using Python 2.x in projects and operations, Python 3.x Many new features were later ported to Python 2.6/2.7.

The version of Python 3.7.x we are currently using is released in 2018. The version number of Python is divided into three sections, which are shaped like ABC. Where A indicates a large version number, generally when the overall rewrite, or a change that does not backward compatibility, increase A; B indicates a function update, increase B when a new function occurs; C indicates a small change (such as fixing a bug) ), increase C as long as there is a change. If you're interested in the history of Python, check out a blog post titled "A Brief History of Python" (http://www.cnblogs.com/vamei/archive/2013/02/06/2892628.html).

#### Advantages and disadvantages of Python

The advantages of Python are many, and the simple ones can be summarized as follows.

1. Simple and clear, there is only one way to do one thing.
2. The learning curve is low, and Python is easier to use than many other languages.
3. Open source, with a strong community and ecosystem.
4. Interpretative language, inherently platform portable.
5. Support for both mainstream programming paradigms (object-oriented programming and functional programming).
6. Extensibility and embeddability, you can call C / C + + code, you can also call Python in C / C + +.
7. The code is highly standardized and readable, suitable for people with code cleanliness and obsessive-compulsive disorder.

The shortcomings of Python are mainly focused on the following points.

1. Execution efficiency is slightly lower, so computationally intensive tasks can be written in C/C++.
2. The code can't be encrypted, but many companies don't sell software but sell services. This problem will be diluted.
3. There are too many frameworks to choose from during development (for example, there are more than 100 web frameworks), and there are errors in the choices.

#### Python application area

At present, Python has a wide range of applications in cloud infrastructure, DevOps, web crawler development, data analysis mining, machine learning, etc., so it also produces Web back-end development, data interface development, automated operation and maintenance, automated testing, scientific computing and A range of positions in visualization, data analysis, quantitative trading, robot development, image recognition and processing.

### Building a programming environment

#### Windows Environment

You can download the Python Windows installer (exe file) on the [Python official website] (https://www.python.org). Note that if you install it in Windows 7, you need to install the Service Pack 1 patch package first. Can be installed by some tool software to automatically install the system patch function), the installation process is recommended to check "Add Python 3.6 to PATH" (add Python 3.6 to the PATH environment variable) and select a custom installation, in the "Optional Features" interface It is best to tick all items such as "pip", "tcl/tk", and "Python test suite". It is highly recommended to use a custom installation path and ensure that there is no Chinese in the path. After the installation is complete, you will see the prompt "Setup was successful", but when you start the Python environment, the Python interpreter may not run due to missing some dynamic link library files. The common problem is mainly api-ms-win-crt\* The .dll is missing and some dynamic link library files are missing after updating DirectX. The former can be processed according to the method of [api-ms-win-crt\*.dll missing cause analysis and solution] () or directly Download the Visual C++ Redistributable for Visual Studio 2015 file for repair at [Microsoft's official website] (https://www.microsoft.com/en-us/download/details.aspx?id=48145), which can download a DirectX repair tool Make a repair.

#### Linux Environment

The Linux environment comes with Python 2.x, but if you want to update to the 3.x version, you can download the Python source code and pass the source code on [Python's official website] (https://www.python.org). Install the installation method, the specific steps are as follows.

Install dependent libraries (because these dependent libraries may fail when the source code artifacts are installed because of missing the underlying dependencies).

```Shell
Yum -y install wget gcc zlib-devel bzip2-devel openssl-devel ncurses-devel sqlite-devel readline-devel tk-devel gdbm-devel db4-devel libpcap-devel xz-devel libffi-devel
```

Download the Python source code and extract it to the specified directory.

```Shell
Wget https://www.python.org/ftp/python/3.7.3/Python-3.7.3.tgz
Xz -d Python-3.7.3.tar.xz
Tar -xvf Python-3.7.3.tar
```

Switch to the Python source directory and execute the following commands to configure and install.

```Shell
Cd Python-3.7.3
./configure --prefix=/usr/local/python37 --enable-optimizations
Make && make install
```

Modify the file named .bash_profile in the user's home directory, configure the PATH environment variable and make it take effect.

```Shell
Cd ~
Vim .bash_profile
```

```Shell
# ... omitting the above code here...

Export PATH=$PATH:/usr/local/python37/bin

# ... The following code is omitted here...
```

```Shell
Source .bash_profile
```

#### MacOS Environment

MacOS comes with a version of Python 2.x. You can install the 3.x version from the installation file (pkg file) provided by [Python's official website] (https://www.python.org). After the default installation is complete, you can launch the 2.x version of the Python interpreter by executing the python command on the terminal. You can launch the 3.x version of the Python interpreter by executing the python3 command.

### Running Python programs from the terminal

#### Confirming the Python version

Type the following command at the terminal or command line prompt.

```Shell
Python --version
```
Of course, you can also enter python into the interactive environment, and then execute the following code to check the Python version.

```Python
Import sys

Print(sys.version_info)
Print(sys.version)
```

#### Writing Python source code

You can use the text editing tools (recommended to use Sublime, Atom, TextMate, VSCode and other advanced text editing tools) to write Python source code and save it as hello.py, the code content is as follows.

```Python
Print('hello, world!')
```

#### Running the program

Switch to the directory where the source code is located and execute the following command to see if "hello, world!" is output on the screen.

```Shell
Python hello.py
```

### Comments in the code

Annotation is an important part of the programming language. It is used to explain the function of the code in the source code to enhance the readability and maintainability of the program. Of course, the code segment in the source code that does not need to participate in the operation can be removed by comments. This is often used when debugging programs. Comments are removed when the source code enters the preprocessor or compiles, and are not retained in the target code and do not affect the execution results of the program.

1. Single line comment - part beginning with # and space
2. Multi-line comments - three quotes at the beginning, three quotes at the end

```Python
"""
The first Python program - hello, world!
Pay tribute to the great Mr. Dennis M. Ritchie

Version: 0.1
Author: Luo Wei
"""

Print('hello, world!')
# print("Hello, the world!")
Print('hello', 'world')
Print('hello', 'world', sep=', ', end='!')
Print('goodbye, world', end='!\n')
```

### Other tools introduction

#### IDLE - Built-in integrated development tools

IDLE is an integrated development tool that comes with the Python environment, as shown in the following figure. But because IDLE's user experience is not so good, it is rarely used in actual development.

![](./res/python-idle.png)

#### IPython - Better interactive programming tools

IPython is a Python-based interactive interpreter. IPython provides more powerful editing and interaction features than the native Python Shell. IPython and Jupyter can be installed via Python's package management tool pip, as shown below.

```Shell
Pip install ipython jupyter
```

or

```Shell
Python -m pip install ipython jupyter
```

After the installation is successful, you can start IPython with the following ipython command, as shown in the following figure.

![](./res/python-ipython.png)

Of course, we can also use the project called Notenote to run interactively in the browser window through Jupyter.

```Shell
Jupyter notebook
```

![](./res/python-jupyter-2.png)

#### anaconda - One-stop data science artifact
Anaconda refers to an open source Python distribution that includes more than 180 scientific packages such as conda and Python and their dependencies.
Anaconda's download file is large (about 531 MB) because it contains a large number of scientific packages. If you only need some packages, or need to save bandwidth or storage space, you can also use the smaller distribution of Miniconda (conda only) Python).
For those who study data science, anaconda is an absolute artifact, easy to install, and anaconda supports the installation of related software [such as ipython, jupyter notebook mentioned above, and even other data science software such as R]
[A very valuable introduction] (https://www.jianshu.com/p/169403f7e40c)
The only problem now is that the Tsinghua image service has been closed, and the international download will be slower.

#### Sublime - Text Editing Artifact

![](./res/python-sublime.png)

- First install Sublime 3 or Sublime 2 via the [Official Website] (https://www.sublimetext.com/) download installer.

- Install package management tools.
	1. Open the console with the shortcut key Ctrl+` or select Show Console in the View menu and enter the code below.


	- Sublime 3

  ```Python
  Import urllib.request,os;pf='Package Control.sublime-package';ipp=sublime.installed_packages_path();urllib.request.install_opener(urllib.request.build_opener(urllib.request.ProxyHandler()));open( Os.path.join(ipp,pf),'wb').write(urllib.request.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')) .read())
  ```
	- Sublime 2

  ```Python
  Import urllib2,os;pf='Package Control.sublime-package';ipp=sublime.installed_packages_path();os.makedirs(ipp)ifnotos.path.exists(ipp)elseNone;urllib2.install_opener(urllib2.build_opener(urllib2. ProxyHandler()));open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ', '%20')).read());print('Please restart Sublime Text to finish installation')
  ```
	2. Manually install the browser and type https://sublime.wbond.net/Package%20Control.sublime-package to download this file.
	After downloading, open sublime text, select menu Preferences->Browse Packages... Open the installation directory
	At this point, you will enter a directory called Packages, click to enter the sub-directory Sublime Text3, there is a folder called Installed Packages in this directory, put the files you just downloaded here. Then restart sublime text3 and see if there are two options, Package Settings and Package Control, at the bottom of the Preferences menu. If there is one, it means the installation is successful.


- Install the plugin. Open the command panel through the Package Control of the Preference menu or the shortcut key Ctrl+Shift+P. Enter the Install Package in the panel to find the tool to install the plugin, and then find the required plugin. We recommend that you install the following plugins:

  - SublimeCodeIntel - Code Completion Tool Plugin.
  - Emmet - front-end development code template plugin.
  - Git - Version Control Tool Plugin.
  - Python PEP8 Autoformat - PEP8 specification autoformatting plugin.
  - ConvertToUTF8 - Converts the local encoding to UTF-8.

#### PyCharm - Python Development Artifact

The installation, configuration and use of PyCharm will be introduced later.

![](./res/python-pycharm.png)

#### Gitpod - One-click online development tools

Open any Python project on GitHub with a single click.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/jackfrued/Python-100 -Days)

### Exercise

1. View the following code results in a Python interactive environment and translate the content into Chinese.

    ```Python
    Import this

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Though practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Though never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!
    ```

2. Learn to use the turtle to draw graphics on the screen.

    ```Python
    Import turtle

    Turtle.pensize(4)
    Turtle.pencolor('red')
    Turtle.forward(100)
    Turtle.right(90)
    Turtle.forward(100)
    Turtle.right(90)
    Turtle.forward(100)
    Turtle.right(90)
    Turtle.forward(100)
    Turtle.mainloop()
    ```