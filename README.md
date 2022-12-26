# VSlack

Update your Slack status based on your activity in VSCode

## The One Singular Feature

- Show what file and what workspace you are working in

## Requirements

You need a Slack User Token and a Signing Secret.

Go to https://api.slack.com/apps/ and press that shiny "Create New App" button
![](https://cloud-izu52zfib-hack-club-bot.vercel.app/0image.png)

Select the from "From Scratch" option:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/0image.png)

Input the name (just make something up) and input workspace that you want the extension to update your profile in: 
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/1image.png)

Copy the Signing Secret on this section of the resulting page:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/2image.png)

Navigate to the "OAuth & Permissions" section of the sidebar:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/3image.png)

Scroll down the the "User Token Scopes" section:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/4image.png)

Add the following scopes:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/5image.png)

Scroll up to the "OAuth Tokens for Your Workspace" section and hit the "Install to Workspace" button:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/6image.png)

Accept on the following screen:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/7image.png)

Copy the User OAuth Token from the "OAuth Tokens for Your Workspace" section on the page that it redirects to:
![](https://cloud-fwxcwxvaq-hack-club-bot.vercel.app/8image.png)


Navigate over to VSCode. Open the settings page (`Ctrl+,` or `Cmd+,`). Type `"vslack"` in the search bar.

![](https://cloud-mpx2npspn-hack-club-bot.vercel.app/0image.png)

Here, you will see two boxes corresponding to the Signing Secret and the User Token. Input the credentials that you copied from the previous steps here and press enter in each box.

Restart VSCode and you're good to go!

## Extension Settings

* `vslack.userToken`: Slack User Token
* `vslack.signingSecret`: Slack Signing Secret


