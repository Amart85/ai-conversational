---
title: Import your bot and add to your website
durationInMinutes: 30
labId:
---

Power Virtual Agents (PVA) enables building a bot with little to no coding necessary, which opens up opportunities for subject matter experts to develop bots without developer assistance. These bots might be answering customer service questions, providing information on an order, or answer internal employee benefits questions. After a bot has been built, it's often the developer's job to take that bot and integrate it into an app or a website.

In this exercise, you'll import an already built bot into PVA, publish it, and add it to your website.

## Clone the repo

## Import your bot

A bot has already been built for you, and you just need to import it.

1. Go to PVA website, and log in
2. Visit the Power Apps Solutions page, sign in, and make sure you're in the correct environment
3. Go to the Solutions tab, and select the Import button
4. Select the `.zip` file you downloaded, and click Next
5. View the details about the solution you're importing, and then select Import
6. Importing may take a few minutes, and will provide details once it completes. Close that window
7. Select the bot to open the PVA portal

## Publish your bot

After your bot is imported, you need to publish it through the PVA portal.

1. Go to the Publish page on the left
2. Select Publish, which may take a couple minutes
3. Once published, you can see it on the demo website by the link just below the Publish button

## Get the embed link and put into your website

The demo website offers a great way to share your bot with other stakeholders to try it out, but for customer and other production uses you'll need to publish your bot.

Once your bot is published, get the embed code and put it into your web page

1. Go to the Settings page, and select Channels
2. Select Custom Website, and locate the embed code
3. Copy the code provided. It will look something like this:
  
  ```html
  ```
  
1. Go to the repo cloned at the beginning of this lab, and open `CustomWebpage.html` is VS Code
1. Paste the embed code in place of `<embed code here>`
1. Save the file
1. Go to a File Explorer window, and double click to open `CustomWebpage.html`
Say hello to your bot