---
title: Login with Token
tags: login, token, shortcuts
category: Authentication
excerpt: Guide to login with Tesla API token
created: 2020-04-07
image: ./images/IMG_6577.png
image_caption: Acquire token by Shortcut
author: author1
---

## Acquire authentication Shortcut

From your phone, navigate to this page and tap the green download shortcut button: https://shareshortcuts.com/shortcuts/256-tesla-access-token.html

That should open in the Shortcuts app, which is an app from Apple themselves that should already be on your phone. It’s a scripting toolbox that allows you to automate a lot of stuff on your phone - and in our case, it allows us to call the Tesla api directly without a dedicated app. 

If you get a security error at this point, please take a side-step to this guide for how to enable 3rd party shortcuts in the Shortcuts app: https://9to5mac.com/2019/08/14/allow-untrusted-shortcuts-ios-13/

First you'll see the Add shortcut screen - scroll all the down to the bottom, and you should se a red button "Add Untrusted Shortcut" - if you feel like, read all the steps in the shortcut and make sure you trust it. I do - and use it for my main login purposes for all 3rd party Tesla stuff - but you are your own man on this account. Then tap the button

![](./images/IMG_6577.png "")

![](./images/IMG_6578.jpeg "")

You'll then have to configure the shortcut - you can either store your username and password in the shortcut itself, or enter them whenever you run it - up to you. I always configure it with my credentials, because I log in a lot - but that's really up to you. Tap the Text field and input your tesla account email, if you wish now - or do it later when you run the actual shortcut

![](./images/IMG_6579.jpeg "")

Same thing applies to your password

![](./images/IMG_6580.jpeg "")

Now hop on over to the "My Shortcuts" tab found in the bottom toolbar and tap on the new shortcut "Tesla Access Token" (I have a few - in my case the name is different)

![](./images/IMG_6581.jpeg "")

The shortcut wil ask you for permission to check your stored shortcuts - that is because this authentication shortcut is actually part of a suite of shortcuts that work together - but we're only interested in this one - but you still have to accept it for the shortcut to work - so tap OK

![](./images/IMG_6582.jpeg "")

Then the shortcut will prompt you for your username and password - verify that they are correct

Then the shortcut will prompt you for access to an internet address - this is critical - Shortcuts will always prompt you for ANY internet servers it wish to access - so you can clearly see where your crendetials are going. The addres MUST BE owner-api.teslamotors.com - that is the official Tesla authentication server. So tap OK

![](./images/IMG_6583.jpeg "")

Then you SHOULD see your access token, and it will look like just garbage text

![](./images/IMG_6584.jpeg "")

Then tap ok, and then choose to copy the token

![](./images/IMG_6585.jpeg "")

Now you can use the watch app and in the login form scroll down to the token input field - so skip the username and password fields and leave those empty. Tap in the field and then tap on the keyboard icon on your watch, which should send a notification to your phone to allow you to enter text with your phone. 

In the textfield - and I mean directly in the text field itself - tap with three fingers simultaneusly - then you'll get access to the new paste function in iOS 13 - tap paste and then tap on the login button below the text field on the watch - verify that the text was transferred properly. 

![](./images/IMG_6586.jpeg "")

Be aware that the login token will only last for 48 days. If you want a persistent login, you can paste in the refresh_token instead. Follow along if you wish to do that - we'll need to update the shortcut to return the refresh_token. 

First, open up the Shortcuts app, and open the My Shortcuts tab and find your Tesla Access Token shortcut. Then tap the button in the top right corner of the shortcut labelled just "...". This will put the shortcut in edit mode. 

Then scroll down throuh the shortcut steps - making sure not do drag any of the steps out of order. Scroll until you find the "Get Value for access_token in Contents of URL" step. 

![](./images/IMG_6593.jpeg "")

Then tap on the "access_token" field and change the value to "refresh_token" and then tap Done in the top right corner. 

![](./images/IMG_6594.jpeg "")

That's it! If you now run the shortcut, it will look completely the same, but the resulting token will work only once to login - but the login will then be perpetual - at least until you change your password, then you'll be logged out everywhere :-D

If you wish to switch over to that new token on the watch, scroll to the bottom of the main view on the watch and tap the Settings button. Then again scroll to the bottom and then tap the Log out button - and then do the same process as with the previous token, making sure to paste it into the token field in the login dialog through the three-finger-tap gesture on your phone!
