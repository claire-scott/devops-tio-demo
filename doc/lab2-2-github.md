# Lab 2-1 - Configure github

In this lab we will install prepare github for our build job

## Create github account

1. If you don't have a github account, go to the following address and sign up for one

    ```
    https://github.com/
    ```

1. Log in to github

1. Go to my repository, and click 'fork' in the top right corner of the screen

    ```
    https://github.com/tj-scott/devops-tio-demo
    ```

    Follow the instructions to create your own fork of the project (keep it public, that will save some configuration on jenkins)

1. Go to your new fork of the repository, it will probably look like

    ```
    https://github.com/{your github username}/devops-tio-demo
    ```

1. There is a green button, above the list of code files, to the right which say 'Clone or download',  click this button, copy the url in the textbox,  it will look like

    ```
    https://github.com/{your github username}/devops-tio-demo.git
    ```

1. you can get a copy of this by going to your VM and typinh

    ```
    $ cd ~
    $ mkdir src
    $ cd src
    $ git clone https://github.com/{your github username}/devops-tio-demo.git
    ```

1. you can now see the files in a sub-directory name devops-tio-demo

