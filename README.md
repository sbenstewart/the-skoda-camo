# the-skoda-camo
![GitHub repo size](https://img.shields.io/github/repo-size/sbenstewart/the-skoda-camo)

Get the pixel form of the digits of pi as a wallpaper using either the number of digits of pi you want or the screen resolution.<br>

<img src="camo.jpeg" alt="the-skoda-camo" width="500"><br>

## the-reason

Certainly nothing special. Had this in mind for a long long time, but [https://www.camowithskoda.com/](https://www.camowithskoda.com/) gave the motivation to finally code it out. And guess what seems they shortlisted the design too.

<img src="webpage.png" alt="the-skoda-camo"><br>

## the-pitch

Inspired by the simplicity of the basic regular shapes. Themed over the contrasting Skoda colour palette. Dazzled by the pseudo randomness of the camouflage patterns. Created using Python - the programming language.

## the-prereqs

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of [Python3](https://www.python.org/downloads/)
* You have the [pip](https://pip.pypa.io/en/stable/installing/) package manager.
* You have the [jupyter notebook](https://github.com/jupyter/notebook/blob/master/README.md#installation) installed.
* Microsoft Visual Studio 2019 Build Tools (https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2017) and add to Environment Variable (Control Panel> System and Security> System> Advanced System Settings> Advanced> Environment Variables> Path) and add the path of the folder containing the cl.exe file (in this system, it's at C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Tools\MSVC\14.24.28314\bin\Hostx64\x86\).
* For gmpy2 installation in Windows 10, download the pre-compiled binary file (gmpy2-2.0.8-cp36-cp36m-win_amd64.whl from https://www.lfd.uci.edu/~gohlke/pythonlibs/#gmpy ) 
Then run 
```
pip install gmpy2-2.0.8-cp36-cp36m-win_amd64.whl 
```

If the above are too complicated you can use the Python3 version of [Anaconda](https://www.anaconda.com/distribution/) which serves the same purpose. But requires a bit more of processing power and storage to install.

And if feeling a bit lazy today, you can have a glance at the [Google Colab sheet](https://colab.research.google.com/drive/1Chzc2GKgx8PJ21eZCe9fixYEq7zhbpzx#scrollTo=blzlDlmCnjPL) which is not necessarily the up-to-date version.

## the-run

To get started with the-skoda-camo, follow these steps:

* Clone the repository to your local machine.
* Change to the repo directory.
* Run the following command to install the required packages.
```
pip install -r requirements.txt
```
* Start the jupyter notebook.
```
jupyter notebook
```
* It opens up the web browser. 
* Navigate to the repo directory.
* You will find one file code.ipynb

## the-resolution
For this, you will have to open the `code.ipynb` file in the jupyter webpage.

Now change the value of the `width` and `height` variables along with the `scale` as the need be in the notebook. 

Once it is changed, run the whole notebook.

The output will be a `camo` for the resolution specified.

## the-contribution
To contribute to the-skoda-camo, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <user_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

## the-contact

If you want to contact me you can reach me at <sbenstewart@gmail.com>.

**Have a great day :)**