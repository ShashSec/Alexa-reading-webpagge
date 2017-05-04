# Alexa-reading-webpagge
python program to read the worpress page content using Alexa and AWS Lambda service

# create Alexa skill 
In order to create amazon skill, create an account in Amazon developer account.
once you logged in, use Alexa skill and select Alexa skill kit
follow the guidlines and use the Amazon-alexa-skill to build a interaction model

# creating AWS Lambda service
using the python code create Alexa lambda service and copy the ARN Id

# linking Alexa skill with Lambda service
In Alexa skill created provide Aws Lambda ARN and provide following sample utterarnce

WhatIsIntent what is {The Voyage network name|AskedQuestion}
WhatIsIntent what's' {The Voyage network name|AskedQuestion}
TellMeIntent tell me about {The Voyage network|TellMeQuestion}
TellMeIntent tell me {The Voyage network|TellMeQuestion}
