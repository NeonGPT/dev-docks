# how to setup the env
## Step 1
download the source code
 ```
git clone https://github.com/girlfriendGPT/girlfriendGPT.git
```
## Step 2
go into the folder git created
## Step 3
run this command
`python -m venv venv`
## Step 4
run this command
Windows:
`.\venv\scripts\activate`
## Step 5
install all the required packages
[PyTorch](https://pytorch.org/get-started/locally/)
and 
nltk
`pip install nltk`
## Step 6
Create a python script and paste this code
 ```
import nltk
nltk.download('punkt')
```
run it and after it downloads it you can delte the script.
