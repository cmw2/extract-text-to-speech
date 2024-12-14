# Repo to extract bill summary info and generate audio file.

## Features
This repo has a python jupyter notebook that will read files i the input folder and process them with Azure Document Intelligence.  It will then use Azure OpenAI gpt-4o to extract the desired content and turn it into a markdown file.  Finally it uses Azure Speech Services to turn that into an audio file which is stored in the output folder.

## Get Started
To get started you need to:
1. Clone the repo
1. Create a folder called input and place one or more input documents into it
1. Copy the .env.sample file and fill it in with your details.
1. Ensure you have python installed.
1. Ensure you have the Jupyter vscode extension (from Microsoft) installed.
1. Open the notebook file.
1. Use the Select Interpreter button to create a new python venv environment.  (After this you can use that to select the one you created.)
1. Go through each step of the notebook.  When done there should be an audio file in the output folder.
   - You may be prompted to install the ipykernel package which you should confirm.