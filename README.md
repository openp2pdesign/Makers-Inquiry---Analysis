Makers-Inquiry---Analysis
=========================

IPython notebooks for the analysis and visualization of the Makers' Inquiry survey.

## Data

Save the results as **data/results-makers.csv**

## Requisites

Install this from the terminal:

1. *pip install numpy*
2. *pip install scipy*
3. *pip install matplotlib*
4. *pip install ipython[notebook]*
5. *pip install seaborn*

## Re-Install Python on MacOSx

If you are on Mac, please reinstall Python with the following commands:

1. *ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"*
2. *brew doctor*
3. *brew update*
4. *brew install python*
5. *vim ~/.bash_profile*
6. and insert this code:
	1. # Set architecture flags
    2. export ARCHFLAGS="-arch x86_64"
    3. # Ensure user-installed binaries take precedence
    4. export PATH=/usr/local/bin:$PATH
    5. # Load .bashrc if it exists
    6. test -f ~/.bashrc && source ~/.bashrc
7. *. ~/.bash_profile*
8. *easy_install pip*
9. *brew install gfortran*
10. *brew install freetype*
11. *brew install libpng*
12. *brew link freetype*

