---
layout: module
title: Module 1&#58; Setting Up Your Environment
---
In this module, you create a Developer Edition Account that provides you with a full-featured but isolated Salesforce environment to perform the exercises in this workshop. You then enable Lightning Components in that development environment.

## What you will learn
- Enable Lightning Components in your Salesforce org
- Set up My Domain


## Step 1: Creating a Developer Edition Account

> Even if you already signed up for a Developer Edition account, it is **strongly recommended** that you sign up for a new Developer Edition account for this tutorial.Some of the steps in this tutorial may break some of the work you already did with your existing account.

1. Open a browser and access the following URL: [http://developer.salesforce.com/signup](http://developer.salesforce.com/signup)

2. Fill in the signup form:
  - Enter your First Name and Last Name
  - For **Email**, enter an email address you have access to at this time (you will need to open an activation email)
  - For **Username**, specify a unique user name in the form of an email address. For example: **firsname.lastname@workshop.com** (It doesn't have to be an existing email address: the Username is not used to send you emails)
  - Check the Master Subscription Agreement checkbox and click the **Sign Me Up** button

3. Check your email. You will receive an activation email for your Developer Edition Account.

4. Click the link in the activation email. Enter your new password information, and click **Save**.

## Step 2: Set up My Domain

Lightning Components require My Domain.  Let's set that up.


1. Go To Setup->Domain Management->My Domain
2. Enter a name, it must be unique.
3. Click 'Check Availability'.
4. Click 'Register Domain'. (Usually this takes a few minutes).
5. Once the Domain is ready, refresh the page and log in with the domain.
6. Deploy the domain to all users.

## Step 3: Enable Lightning Components

Depending on your developer org, you may need to enable Lightning Components.  Here's how to do so.

1. In Setup, click **Develop** > **Lightning Components**

1. Check the **Enable Lightning Components** checkbox

    ![](images/enable-lightning.jpg)

1. Click **Save**


<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="index.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="create-apex-controller.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
