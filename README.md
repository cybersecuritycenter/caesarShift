# caesarShift

## Description
This is a tool to encrypt and decrypt a message using a Caesar Shift cipher.  A Caesar Shift cipher is a type of substition cipher that replaces a letter with a fixed number of positions down the alphabet. 

### Caesar.py
This program is written in Python and its goal is to decrypt encrypted flags

### caesarshift.sh
This is a bash Script that will put our flags in a flags.txt file

### createflags.py
Python program that will use CaesarShift to give a randomly generated flags that follow this format CAHSI-AAAAA-#####

### fasttrack.txt
Our wordlist that users can easily modify.

## Installation
Users can download the repo form here on our github, or open up your linux machine open up a terminal and open up your favorite text editor.

## Usage
These instruction will how you how to use the program using Visual Studio Code.
Open the repo using Visual Studio Code and install the needed extensions of Python if you have not yet done so.
Then, verify the Python installation by typing in the following:
```
py -3 --version
```
If the installation was successful, the output window should show the version of Python that you installed.

To begin the program, first type in 
```
py createflags.py > flags.txt
```
This will create flags and input them into a .txt file called flags.txt.
*Note - Any other name can be used as long as it ends with .txt*

The next step is to run caesar.py, open up your newly created file, and create a `.csv` file to input your results.
```
py caesar.py flags.txt > shiftedwords.csv
```

You should get something that looks like the following file

![image](https://user-images.githubusercontent.com/93400667/140547051-f4266742-1656-442d-8e55-84d71ada164b.png)


## Contributing

## Credits

## License
