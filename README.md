
## What it does
This is a smart no-code project using node red,IBM cloud and Assembly Api. This project can be used to turn On or OFF the home appliances using voice commands or we can also connect the device with alexa to controll the appliances using IFTTT.
In the special part it also has a language translation function that can translate english transcripts of assembly API to any of the 7+ language by choosing from the UI.

## How we built it
I had built it using a bolt wifi module containing esp8266 wifi chip for getting the command from the user and connecting to the internet. I am making the appliances ON or OFF using the relay module triggered by the bolt's digital pin.

The voice command is being picked by the assembly api and checked using switch node in the node-red flow. 
More over the language translator is made using the ibm cloud's language translator. 

## Challenges we ran into
The main challenge I ran into was using the language translator api in the node red.

## Accomplishments that we're proud of
I am proud that I had done the total project in this small span of time and had made it work as I wanted though some changes need to make.

## What we learned
1. Use of IBM cloud
2. Use of Language translator
3. Use of the Assembly API
## RUN
Just import the flow above to your node-red and change the API with yours.
