Prerequisite
--------------

1) Moving forward, we will be using virtualenv throughout the frameworks.
2) All the frameworks and example will be compiled using python 3.6+
3) To do common stuff throughout the book, we will try to build API`s using all the framework, though exceptions are everywhere.

Why virtualenv ?
++++++++++++++++++

The best time to learn about virtual environment is when you are a beginner/intermediate in python as it will be very much helpful.

* **What is virtual environment ?**

    A virtual environment is a way for you to have multiple versions of python on your machine without them clashing with each other, each version can be considered as a development environment and you can have different versions of python libraries and modules all isolated from one another. For more information visit `virtualenv <https://virtualenv.pypa.io/en/stable/>`_

* **Importance of virtual environment.**

    Say, if you're working on an open source project that uses :code:`django 1.7` but locally, you installed :code:`django 2.0` for other project. It's almost impossible for you to contribute to open source because you'll get a lot of errors due to the difference in django versions. If you decide to downgrade to :code:`django 1.7` then you can't work on your project anymore because that depend on :code:`django 2.0`. Virtual environment lets you handle this situation by creating a separate virtual(development) environments that are not tied together and can be activated/deactivated easily whenever you want.

* **How does virtual environment work ?** ::

    $ virtualenv venv
    $ cd venv
    $ source bin/activate
    (venv)$                 // The current shell starts using the virtual environment.
    (venv)$ deactivate      // virtual environment deactivated.


Why Python 3.6+ ?
++++++++++++++++++

* **Python is not traditionally a typed language, but Python v3.5 supports typing, which removes development conflicts when working new pieces of code.**
* **Each newer version of Python continues to get faster runtime. Meanwhile, nobody’s currently working to make Python 2.7 work faster.**
* **Community support is better with Python 3.**


Why follow common pattern?
+++++++++++++++++++++++++++

It would help in choosing what should be the best framework as per your requirement. And also it will provide you better understanding and as you can compare different frameworks for same task.





