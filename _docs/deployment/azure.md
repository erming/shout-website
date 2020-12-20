---
layout: documentation
title: Azure
description: Add your description here
category: Deployment
order: 4.3
---

# Azure

This document will explain how to install Shout on Microsoft Azure - which allows you to host Shout for free, if you run in the "free" tier. The installation is simple:

### Step 1:

Click the button below to open up the Azure Deployment Wizard, which will deploy Shout for you:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffelixrieseberg%2Fshout-azure%2Fmaster%2Fazuredeploy.json" target="_blank">
	<img src="http://azuredeploy.net/deploybutton.png"/>
</a>

### Step 2:

Enter the required parameters:

* Give your Shout Web App a name - you can later find at yourname.azurewebsites.net.
* Specify a name for the App Service plan. You can either create a new one or bundle your Shout app together with an already existing hosting plan.
* Then, choose a datacenter location: Some of the most commonly used locations are "West US", "East US", or "West Europe", but you can find a [full list of accepted location names here](https://azure.microsoft.com/en-us/regions/).
* Specify the tier in which your Shout instance should run. The higher the tier, the more resources will be available to Shout.
* Specify the instance size of the hosting plan (small, medium, or large).

### Step 3:

Give Azure a few minutes to pull Shout and to install all the dependencies. Once done, you'll be able to find your Shout app at your-app-name.azurewebsites.net!
