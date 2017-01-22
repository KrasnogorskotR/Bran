Permissions Overview
===================
Have you ever felt confused or even overwhelmed when trying to set Bran's permissions? In this guide we will be explaining how to use the 
permission commands correctly and even cover a few common questions! Every command we discuss here can be found in the [Commands List](http://bran.readthedocs.io/en/latest/Commands%20List/#permissions).

Why do we use the Permissions Commands?
------------------------------
Permissions are very handy at setting who can use what commands in a server. If something is a bot owner only command, it can only be ran by the bot owner.

The Administration module still requires that you have the correct permissions on the Perm system, so for users to be able to use commands like `.kick` and `.prune`, they need kick and prune messages permissions respectively.

With the permissions system it possible to restrict who can ban a person, play a music...

First Time Setup
------------------
To change permissions you **must** meet the following requirement:

- Be the server owner.

Basics & Hierarchy
-----
The [Commands List](http://bran.readthedocs.io/en/latest/Commands%20List/#permissions) is a great resource which lists **all** the available commands, however we'll go over a few commands here.

Firstly, let's explain how the permissions system works - It's simple once you figure out how each command works!
The permissions system works with separately permissions, like `RUN_BASECMD` to run a basic command, or even `KICK_USR` to kick an user.

To view this permissions, do `.perms list`.

If you want to remove a permission from an user, do `.perms `

Commonly Asked Questions
---------------

### How do I manage the permissions
To allow users to use certain commands by using the permissions

1.	`.perms +[PERM] @User#0001`

	*	Add a perm to an user

2.	`.perms -[PERM] @User#0001`

	*	Remove a perm from a user

3.	`.perms get @User#0001`

	*	Get the list of perms of an user