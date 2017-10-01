# AWS Cognito User Pool- Boilerplate

[![Join the chat at https://gitter.im/aws-userpool-boilerplate/Lobby](https://badges.gitter.im/aws-userpool-boilerplate/Lobby.svg)](https://gitter.im/aws-userpool-boilerplate/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A Simplistic way to getting started with Cognito User Pools

## What's this User Pool? 

<img src="http://backspace.technology/images/SimpleIcon_Cognito.png" width="80px">

You can now use Amazon Cognito to **easily add user sign-up and sign-in to your mobile and web apps**. With the user pools feature, you can create your own user directory that can scale to hundreds of millions of users, and is fully managed so you don’t have to worry about the heavy lifting associated with building, securing, and scaling authentication to your apps. This feature also provides enhanced security functionality such as email verification, phone number verification, and multi-factor authentication.

Using a user pool gives you detailed control over the sign-up and sign-in aspects of your web and mobile SaaS apps, games, and so forth. Building and running a directory service at scale (potentially tens or even hundreds of millions of users) is not easy, but is definitely undifferentiated heavy lifting, with the added security burden that comes when you are managing user names, passwords, email addresses, and other sensitive pieces of information. You don’t need to build or run your own directory service when you use Cognito Identity.

 [Read More](https://aws.amazon.com/blogs/aws/new-user-pools-for-amazon-cognito/)
 
## High level architecture diagram for Boilerplate

<img src="https://cloud.githubusercontent.com/assets/5123109/18832830/2a5bcea2-840b-11e6-83a3-2a1c97db4283.png" width="800px">


 
## Getting Started

### Creating a Cognito User Pool in AWS Console
Login to your AWS Console and in Services list Select : Cognito
<br>
<br>
<img src="https://raw.githubusercontent.com/99xt/aws-userpool-boilerplate/master/documentation/cognito%20services.png" width="100px">

**Step 1
You will be directed to the main Cognito Dashboard like below.**

Now Select 'Manage Your User Pools'
<br>
<br>
<img src="https://raw.githubusercontent.com/99xt/aws-userpool-boilerplate/master/documentation/select%20user%20pool.png">

**Step 2 On the Right corner click "Create a User Pool"**

Enter a Pool name,
<br>
<br>
<img src="https://raw.githubusercontent.com/99xt/aws-userpool-boilerplate/master/documentation/pool%20name.png">

<br>
<br>
Then Select the attributes you need (you can select from the standard attributes),
<br>
<br>
<img src="https://raw.githubusercontent.com/99xt/aws-userpool-boilerplate/master/documentation/attributes.png">

Policies: you can add constraints for the password strength
Verifications: Email verification message can be customized (can be edited later.)
Triggers: You can choose custom Lambda triggers when events occur like (verification, pre signup)

In the Review tab you can see your configuration and Create the pool.
<br>
<br>
<img src="https://raw.githubusercontent.com/99xt/aws-userpool-boilerplate/master/documentation/review.png">
<br>
<br>

*Yay! Now you have created a AWS Cognito User Pool.*

*We'll be using bootstrap as the base for the front end 


**License"**

This repository is under the terms of the [MIT License](http://opensource.org/licenses/MIT). 

Explained in plain english: It is a short, permissive software license. Basically, you can do whatever you want as long as you include the original copyright and license notice in any copy of the software/source.  There are many variations of this license in use.

You can:
 · Use for Commercial purposes
 · Modify
 · Distribute
 · Sublicense
 · Use it for Private purposes
 
You must:
 · Include copyright
 · Include license
 
You cannot:
· Hold the author liable.
