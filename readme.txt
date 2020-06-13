* download the given software for 64-bit from the given link and restart the computer after installing the software:
  https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads

* the chatbot uses tensorflow library and it is tested and supported on the following 64-bit systems:
  Python 3.5–3.7
  
  so, make sure to have the above python version installed for better results.

  Now, open command prompt and then type some code given below to begin with the chatbot project:

1) mkdir chatbot (makes a directory named "chatbot" in the parent folder)
2) cd chatbot (change directory to "chatbot")
3) py -m venv botenv(creates virtual environment named "botenv" in the "chatbot" directory)
4) botenv\Scripts\activate (activates the environment named "botenv")

  We create a virtual environment and then install all additional libraries required for our project in the virtual environment because some of the libraries used can start demanding GPU from systems as they require higher processing speed which can create problems in execution of our programs. Creation of virtual environment makes sure that normail processor is alloted to our program for smooth functioning.
  
  {now we will have to install the libraries in our newly created virtual environment that are required to run the chatbot project in any computer 
  and the requirements and it's versions have been frozen into a ".txt" file named "requirements.txt"}

5) pip install -r requirements.txt (please make sure to give the path where the "requirements.txt" is saved)
6) copy and paste all the files of the project in the chatbot folder that we've created in our first step.
7) now all the programs should be running in the virtual environment that we've created 
8) first run the file named "train_chatbot.py" to create the model and train it(just type train_chatbot.py in the cmd in the activated environment)
9) then run the file named "gui_chatbot.py" and test the chatbot(just type the gui_chatbt.py in the same activated environment)
