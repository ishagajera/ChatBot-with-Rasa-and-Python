# ChatBot with Rasa and Python
 A timezone chatbot using rasa and python
Project made in: C:\Admin\Desktop\chatbot\timezone
Main files used in timezone were:
1. nlu.md :
    Contains all the intents to be used.
2. stories.md :
    Contains the various scenarios the chatbot can encounter in a converstation.
3. domain.yml :
    Contains all the intents,entities,actions and slots that the chatbot will require.
4. actions.py :
    Contains functionality for a given project.Eg:calculating the timezone(here).
    
The steps of this project are given below:
1. run the cmd, write
           rasa init
2. create a new project file
         timezonebot
3. train the project
4. open vs code using :" open . " command.
5. make changes in the files mentioned above.
6. write the command:
       rasa train
   to train chatbot to the changes done in the files.
7. write the command:
       rasa shell
   to open chatbot in the command shell.
   use /stop to close the chatbot
8. write the command:
       rasa shell nlu
   to see the confidence level for each statement entered by the user.
   use ctrl+c to close the nlu shell.
   
   
