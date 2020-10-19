# SATA-SMS-Bot
Get instant answers to your questions with a chatbot powered by Python, Twilio, Wikipedia, and Wolfram Alpha!

# Required Installations

- In order to run this program, you will need to follow these steps:

    - Download **pip** if you haven't already, from [here](https://pip.pypa.io/en/stable/installing/)
    - Create a free **Twilio** account [here](https://www.twilio.com/) and press “Get a Free API Key.”
      then run `pip install twilio`
    - Install **Flask** using `pip install Flask`
    - Install the Wikipedia API using `pip install wikipedia`
    - Download **Ngrok** [here](https://ngrok.com/)
    
    
# How To Run

   - First, download the zip file containing all the source code and unzip the folder. Then, move the folder to your desktop and rename it to SMSBot 
   
   - Run `cd desktop` in terminal to navigate to your desktop directory. Then, run `cd SMSBot` to navigate to that folder and finally run `sata_smsbot.py` to execute the code.
   
   - When you run the code, your terminal should look like this:
   
   ![image](https://user-images.githubusercontent.com/43652410/96400763-9740a300-119f-11eb-9470-e5b4d90f876d.png)
   
   - Your **Port Number** is highlighted in the yellow box. In my case, it is 5000.
   
   - Next, you want to open up Ngrok and type in `ngrok http (port number)`. **Replace "port number" inside the parentheses with your port number.**, in my case it would be `ngrok http 5000`. 
   
   - Your Ngrok should look like this: 
   
   ![image](https://user-images.githubusercontent.com/43652410/96400827-cb1bc880-119f-11eb-8de4-2270c92b17ae.png)
   
   - Next, you want to copy the http address that is highlighted in the yellow box and navigate to your Twilio account screen. 
   
   - Click the “#” on the top left of the screen, then click on your Twilio number, scroll down and **enter the http address into the space that says “A message comes in”. Make sure the dropdown is set to “webhook”: as highlighted in the blue box:** 
   
   
   ![image](https://user-images.githubusercontent.com/43652410/96400932-146c1800-11a0-11eb-97ee-5f6d23959d9e.png)
            

   - **Save your changes** and you are now set!
   - Message your Twilio number and test out the program!


# Troubleshooting

If you are having any issues running the code, please refer to these links or contact me. 
    
   - https://makezine.com/projects/sms-bot/
