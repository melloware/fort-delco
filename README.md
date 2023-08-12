<div align="center">
<img src="https://github.com/melloware/fort-delco/blob/main/images/fort-delco.webp" width="150" height="150" />
</div>

# Fort Delco Check In/Out
Instructions for texting the gym owner "In" upon arriving at the gym and texting "Out" when leaving the gym for Apple iPhone owners.

The following steps will automate the whole process so you never have to remember!

## Create a Fitness Focus

I’ve started by creating a new **Focus (Settings → Focus)** mode called "Fitness", triggered automatically when I arrive at the gym.

<img src="https://github.com/melloware/fort-delco/blob/main/images/1-create-focus.png" width="275" height="600" />

Click on the **Fitness Focus** and make sure to set **"While at this location"** and use the address of the gym as what triggers this Focus.

<img src="https://github.com/melloware/fort-delco/blob/main/images/2-configure-focus.png" width="275" height="600" />

## Automate with Shortcuts App
<img src="https://github.com/melloware/fort-delco/blob/main/images/shortcuts.png" width="50" height="50" /> The next step is we need to automate the text messages using the Apple Shortcuts app.

Click on the **Shortcuts** application and then make sure to select the **Automation** tab like in the screenshot below:

<img src="https://github.com/melloware/fort-delco/blob/main/images/3-shortcut-automation.png" width="275" height="600" />

### Send Text "In" On Arrival
Create a new Automation and choose Fitness Focus and select **"When turning Fitness on**". Make sure to disable **"Ask before running"** so this job just runs automatically as soon as you arrive at the gym without any interaction from you.

<img src="https://github.com/melloware/fort-delco/blob/main/images/4-fitness-on.png" width="275" height="600" />

Next select **"Send A Message"** as the action to run when **"When turning Fitness on**" and choose the person to send it to and the message to send.

<img src="https://github.com/melloware/fort-delco/blob/main/images/5-send-message.png" width="275" height="600" />

### Send Text "Out" On Departure
Create a new Automation and choose Fitness Focus and select **"When turning Fitness off**". Make sure to disable **"Ask before running"** so this job just runs automatically as soon as you leave the gym without any interaction from you.

Next select **"Send A Message"** as the action to run when **"When turning Fitness off**" and choose the person to send it to and the message to send.

<img src="https://github.com/melloware/fort-delco/blob/main/images/6-fitness-out.png" width="275" height="600" />

## Conclusion

That is it!  Once set up it will now automatically text upon arriving and leaving the gym and you will never have to remember again!
