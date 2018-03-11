.. _Installation:

Installation
=============

**Windows**
To install Pyblox, you must do the following:

1. Download or Clone https://github.com/Sanjay-B/Pyblox

2. Place the "pyblox" folder into ``Lib\site-packages``.

if you don't know where it is,run this script in Python:

>>> import sys
print(sys.exec_prefix)

and you will find ``Lib\site-packages`` inside.

MacOS and Linux are supported but installation will vary.

.. note::

    This was developed on a windows-based machine and thus, it's recommended to use windows.

**Example**
Once installed, you can call the wrapper and all of its modules:

.. code-block:: python

    import pyblox


To call a specific class from the wrapper:

.. code-block:: python

    from pyblox import CLASSNAME

A basic example that utilizes the Friend class:

.. code-block:: python

    import pyblox # Imports the API Wrapper 

    def GetFriendUN():
        CoolPeople = Friends.friendList(1) # Gets Friends List
        print(CoolPeople) # Returns usernames and prints them on console

    GetFriendsUN() # Calls "GetFriendUN" method
