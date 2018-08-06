# Your Project Name Goes Here

Your project description goes here.

## Development

Below are instructions for doing development on the project on Windows 10:

1.  Install [Python 3.6.6+](https://www.python.org/ftp/python/3.6.6/python-3.6.6-amd64.exe), [GitHub Desktop](https://desktop.github.com/), [Git](https://git-scm.com/download/win), and [VSCode](https://code.visualstudio.com/docs/?dv=win64). Note that you'll need a GitHub account to setup `GitHub Desktop`.

2.  If you haven't already, clone (download) this project by clicking the big green `clone or download` button in the top right of the screen and selecting `Open in Desktop`. Click `clone` in the window that appears.

3.  In the `GitHub Desktop` app, make sure that this repository is selected under `Current Repository` in the top right

4.  From the `Repository` menu select `Open in Visual Studio Code` to open the project in the `VSCode` editor. Any time you want to edit the project you can follow steps `3` and `4`.

5.  In the `Code` app if the terminal is not showing reveal it by selecting `View > Integrated Terminal`.

6.  In the terminal enter the following command to install the tool that we will use to manage the libraries used by this project:

```sh
pip install pipenv
```

7.  Next install the dependencies themselves with the following commands in the terminal:

```sh
cmd
set PIPENV_VENV_IN_PROJECT=True
pipenv install --dev --python %userprofile%\AppData\Local\Programs\Python\Python36\python.exe
```

8.  Next close and reopen the project in `Code`. You can now create python files by right clicking in the file explorer on the right. You can run a python file by opening it and selecting the `Debug > Start Debugging` menu.
