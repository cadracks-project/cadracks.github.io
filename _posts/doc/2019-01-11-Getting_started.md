---
layout: doc
title: "Getting started with cadracks.org"
categories: doc
date: 2019-01-11
---

The goal of this 'Getting started' tutorial is to help you become a user and create your first 
project hosted on [cadracks.org](http://cadracks.org).

Prerequisite
------------

As detailed further down in this tutorial, there are 2 options to add files 
to a repository. If you choose the first way (Local clone), you will need 
to install git on your machine.

The download and installation instructions can be found at [git downloads](https://git-scm.com/downloads)

If you choose the second way, you do not need to install git. 
Yet, as [cadracks.org](http://cadracks.org) is a git repositories hub, 
learning about **git** is a good idea to become a power user.


Create an account and/or login
------------------------------

If you don't already have one, please create an account by following the steps at 
['Create an account at cadracks.org']({% post_url doc/2019-01-10-Create_an_account %})


Create your first repository
----------------------------

Choose **New Repository** from the drop-down (**+**) in the upper right corner:

![new_repository_button][new_repository_button].

Fill in the New Repository form with a name, a description.

**MAKE SURE THE VISIBILITY IS UNCHECKED (private repositories containing CAD files are not supported yet)**.

![new_repository_form_filled][new_repository_form_filled].

If you want (not strictly necessary), you can choose and **.gitignore** file and a **License** from the drop-down lists. 
Ticking **Initialize Repository** will add these files to the initial version of your repository.


Option 1 - Local clone
----------------------

On your machine, go to the command line, move to the directory where you want to clone your newly created repository. 
Then type:

```bash
git clone http://www.cadracks.org/<user name>/<repository name>
```

This will create a local copy of your online repository.        

Add some files to your repository.

Then, at the command line prompt:

```bash
git add .
git commit -m "<describe your changes>"
git push

```


Option 2 - Add files online
---------------------------

You may also add files to your repository online. Choose the **Upload File** button 
to do so.

![upload_file_button][upload_file_button].

Use the **Drop files or click here to upload** area to add the files.

![upload_file_form][upload_file_form].

Fill the short description in. Optionally, you can also fill the long description in.

As we are just getting started,  you can leave the **Commit directly to the master branch** 
ticked unless you know **git** and therefor know what you are doing.

Finally, commit your changes.


Conclusion
----------

The CAD files you added to [cadracks.org](http://cadracks.org) are now available publicly and 
others might decide to clone your project, make it better and have their improvements integrated in your own project version through **pull requests**

[new_repository_button]: {{ site.url }}/img/new_repository_button.png "New repository button"
[new_repository_form_filled]: {{ site.url }}/img/new_repository_form_filled.png "New repository form filled"
[upload_file_button]: {{ site.url }}/img/upload_file_button.png "Upload file button"
[upload_file_form]: {{ site.url }}/img/upload_file_form.png "Upload file form"