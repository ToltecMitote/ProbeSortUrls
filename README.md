To start the program use the built-in terminal option in pycharm.

First you copy and paste a .txt file which you want to scan for errors or misspellings.

Second use the command -ls to see that the .txt file is added properly

lastly use the following to pipe the file through python: cat urls.txt | python main.py.

Depending your python version you might need to write python3 instead of just python e.g: cat urls.txt | python3 main.py.

Now your program will go through the .txt file and produce a new .txt file named "filtered_urls.txt" or whatever you choose to name the file. 
