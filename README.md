

#### Quick Links
- [Spanish Instructions/Instrucciones en Español](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/README_es.md)
- [Download & Instructions](#Installation)
- [Inspiration for this tool](#Inspiration-for-this-tool)
- [Questions/feedback/issues](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/issues)
- [Track bugs/enhancements](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/projects)
- [Notice about 'disappearing' delivery windows](#notice-about-disappearing-delivery-windows)
- [Supporting me/Donations](#supporting-medonations)

# Amazon Fresh/Whole Foods delivery Slot Finder for Windows and Mac
Automated script for finding available delivery windows for Amazon.com's Fresh delivery and Amazon Whole Foods services that is compatible with multiple OS and Browsers. Bookmark this page so you can easily come back to it.

## New Features
* #### New Support - added 4/29/20
  * Enabled Support for Multiple Languages and Amazon Pages from Multiple Countries.
  * Note: Only Tested with Pages in the United States.
  
## Installation
In order to make this tool as compatible as possible it's built on top of (Tampermonkey® by Jan Biniok) the most popular userscript manager.

1. Install the Tampermonkey® userscript manager on your browser, just follow the instructions provide at Tampermonkey® [here](https://www.tampermonkey.net/)

2. Once installed you will see an icon like this on your browser's toolbar

![TampermonkeyIcon](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart5.JPG)

3. Now you need to install the "Delivery Slot Finder" script via this link [here](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/raw/master/kLk-Delivery-Slot-Finder.user.js)

4. Click "Install" when you see this screen.
![ScriptInstall](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart6.JPG)

5. Open a new tab and visit Amazon.com, go to your Amazon Main cart by clicking the Cart Icon on the upper right side of the page.

 ![AmazonCartIcon](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart1.JPG)

6. You will see a new button at the top of the page. The button should be "Off", for now please leave it Off.
![ScriptIcons](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart2.JPG)

### You have successfully install the "Delivery Slot Finder" Script.
### Notes:
The script will stop running if your computer falls asleep. You can adjust your 'Energy Saver' settings in System Preferences or download [Caffeine app](https://intelliscapesolutions.com/apps/caffeine) to keep your computer awake.




## How it works
- Once you have the script installed you will see a new set of buttons on your Amazon's Cart Page and on pages related to the checkout process.
- It's recommended that you have the script off until your product selection is in your cart.
- You will see these icon on your Amazon Cart. You can turn the script On and Off by just clicking the button.
- Below I will show you the process for using the script to find an available delivery window for an Amazon Fresh Order.


## 1) Fill your Amazon Fresh cart with your order, when ready click the Cart Icon on the upper right side of the page.
![AmazonCartIcon](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart1.JPG)



## 2) You will see the new button at the top of the page. The button should be "Off". 
![FreshChkOut1](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut1.JPG)

## 3) Click on the Off Button, this will refresh the page and the button will now say "ON" and you will see another button with "Amazon Fresh". Use this button to select if you are going to perform checkout for Amazon Fresh or Whole Foods.![ScriptOnIcons](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart3.JPG)

## 4) On this example we are going to place the order using Amazon Fresh. Click on the "Checkout Amazon Fresh Cart" button.
![FreshChkOut2](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut2.JPG)



## 5) The script will automatically click on continue for the "Before you checkout" Page. This is done in case your checkout session expires while waiting for an available Slot. This enables the script to navigate back to the "Schedule your order" Page to wait for an available delivery window.
![FreshChkOut3](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut3.JPG)



## 6) You should be taken to the "Schedule your order" Page. Here the script will wait and automatically refresh the page until there is an available delivery window.
![FreshChkOut4](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut4.JPG)
### Note: If it turns out that there is an available delivery window the alert will instantly start sounding and you can select the delivery window and continue the check out.



## 7) You should see this countdown bar, it shows the time left in seconds until the page is automatically refreshed. It will do this until a delivery window is found.
![FreshChkOut5](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut5.JPG)



## 8) Turn up the volume to hear the notification when a delivery window is found



## 9) Once a Delivery Window is found, the script will generate an alert and the countdown bar will disappear.
![FreshChkOut6](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut6.JPG)



## 10) Once you're notified, quickly select a delivery window and finish checking out because available delivery windows are snagged almost instantly.











## Compatibility
For Whole Foods you will need to manually click on “Continue” for the "Substitution preferences" Page that comes up after the "Before you checkout" Page. The script is not fully compatible with Whole Foods orders.  I'm currently on the waiting list for Ordering from Whole Foods, once I gain access I will continue working on the support for it, Prime Now compatibility may be added at the same time. 

**Before using this tool**, ensure that your checkout page looks **exactly** like the examples in the _Compatible_ section below.
This tool currently only works for some regions because Amazon's checkout pages seem to vary based on your location and I designed the tool based on the page I see in my region. 
If your checkout page doesn't look like the examples in the _Compatible_ or _Incompatible_ sections below, this tool may still work for you but no guarantees.

## Notice about "disappearing" delivery windows
No guarantee that delivery windows will be found and/or that delivery windows will work. Often you will select a delivery window and by the time you click the continue button the delivery window will not be available, when that happens the page refreshes and if there is another delivery window still available you will get another opportunity to try and get the available delivery window. These disappearing delivery windows are very common and are unfortunately in Amazon's control, not mine.  Eventually a slot should work. Wishing you resilience and hope! Feel free to post concerns in the [Issues](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/issues) section.

### Compatible
These are sample screenshots for delivery to a New Jersey address

#### Amazon Fresh
![Amazon Fresh](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut7.JPG)

#### Whole Foods
![Whole Foods](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut7.JPG)


### Incompatible
#### Amazon Fresh
##### 1.
![Santa Clara, CA](https://i.imgur.com/SyNtrZs.png)
##### 2.
![an unknown city in CA](https://i.imgur.com/PYrO9Il.jpg)


## Inspiration for this tool
As The Coronavirus 2019 pandemic caused a surge in demand for grocery delivery services, making it nearly impossible to find an open delivery slot. I was having a difficult time getting a delivery window for my Amazon Fresh order, I came across this other GitHub project from [ahertel](https://github.com/ahertel/Amazon-Fresh-Whole-Foods-delivery-slot-finder) whish provides a script for people using Macs. I don't own a Mac so I decide to make a version of the script that would be compatible with people running Windows or Mac. My intention in providing this tool is first and foremost help those in need (e.g. at-risk people, health care workers, all the people that are trying to stop the spread of COVID-19 by staying at Home) have an easier time staying safe.

## Supporting me/Donations
Thank you so much for wanting to support me! I don't want anything in return for this tool - I'm just happy to be hearing all the stories about how this has helped people, especially those in need. 
