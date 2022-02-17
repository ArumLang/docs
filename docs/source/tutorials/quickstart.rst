.. _quickstart:

Quickstart
====================

This is a quick guide for **JERScript**. Intended for those new to the language,
not experts. For more in-depth documentation, see the `JERScript documentation <https://jerscript.readthedocs.io/en/latest/>`_.

.. contents:: Contents
    :local:
    :depth: 2

First example: Hello world
--------------------------------

Your first program should ALWAYS be `Hello world!`_, and it should be the first
program you write. It is a good idea to write a program that prints out
`Hello world!`_ to the screen to teach you the basics of the language.

Step 1. Create a file ending in `.jer`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

First, create a file ending in `.jer`, pretty simple. I know.

Linux:
::

    $ touch hello.jer

Windows:
::

    $ type nul > hello.jer`

Good, we have a file ending in `.jer`. Cool!

Step 2. Edit the file using your favorite text editor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Edit a file using a favorite text editor! Whether that is `vim`
`emacs` or `nano`, it is a good idea to edit the file using a text editor.
(We have syntax highlighting for VS Code!)

Step 3. Write your program
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

All we have to do now is to type:
```
write("Hello world!")
```

Step 4. Run the program
^^^^^^^^^^^^^^^^^^^^^^^^^

Assuming you have the CLI installed, (if you dont, refer to :ref:`Download <obtain>`)you can run:
::
    
    npx jerscript --file=hello.jer

It will output
::

    Hello world!
to the console! Good job! You've made your first program!