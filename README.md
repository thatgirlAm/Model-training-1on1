# Model-training-1on1
Learning to manipulate IA models

## Step 1 : Defining our first mission.

Here we will want to sort emails as when to put it in spam, normal and important.
We want a specific model that would learn from the user's data only which can see a bit redutive, but for confidentiality reasons it would be better.

### 1.a. What would be requiered ? 

#### 1.a.i. Accessing the email inbox

We would need to acess the user's email inbox so we will need an API key in order to do things the right way. 
Here I wil start with my personnal email account, which has thousands of emails which would be great for the training part of the IA.  

#### 1.a.ii. Using a model to sort the emails

The model would need to recognize the new emails (so recognize unread ones), pick one (the latest maybe?), read it, decide what is the category the email is in and put it in the right basket (Important, Stay in inbox or Spam).

However, there is a few icks I have : 

##### ick 1 : how would I know which are the new emails if the model had already read them? 
I will add another step which is to mark the emails as unread si that i can know they're new ones.

##### ick 2 : confidentiality issues...
Do I really want my AI to be able to read sensitive data...? 
The fact is that it kinda is ok because the data isn't supposedly kept...But the question still is : it is a door to the user's privacy...Will ask the Chat about this later maybe ! 

#### 1.b. Optional features !

##### 1.b.i. Getting notified

It would be great to have a notification like : " You had X new e-mails, amoung which Y important e-mails, Z Inbox messages, W Spam ones "


##### 1.b.ii. Being able to reverse the workflows

The user might want to reverse the sorting. 
For that we could have an interface to see the different worlflows and be able to reverse them (i.e being able to put all those sorted emails in the inbox)


##### 1.b.iii. Creating a User Interface

The user could be able to acces an interface on the desktop that would allow them to watch, manage and modify workflows. The thing is that is would be ideal for it to be integrated in the inbox app on the desktop but for simplicity reasons we can put it on a spearate interface on the desktop.
The features on the app would be : 
 - Displaying the differet operations
 - Reversing one operation
 - Reversing multiple operations (We would be able to select operations we would use a checkbox)
 - Stop workflows
 - Plan workflows (each day for instance or every 30 mins ?)