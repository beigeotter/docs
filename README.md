# Individual Droplet Page

## How do I restart my Droplet?

We recommend restarting a Droplet from the command line. This can be done with the following command:

	sudo shutdown -r now
	
However, in extenuating circumstances, you can restart your Droplet from the control panel. This course of action is not recommend, as it’s the same as hard resetting the server and may cause data corruption. 

To restart your server from the control panel, first navigate to the Droplets page in the control panel. Click on the name of the Droplet you are trying to connect to.

![Individual_Droplets](https://assets.digitalocean.com/site/ControlPanel/individual_Droplet.png)  

Once you’ve reached the individual Droplet’s page, click on the power icon and then select the power cycle button. 

![ControlPanel_PowerCycle](https://assets.digitalocean.com/site/ControlPanel/Powercycle.png)

## How do I shut down or power off my Droplet?

We recommend shutting down a Droplet from the command line. This can be done with the following command:

	sudo shutdown -r now

or
	
	sudo poweroff

However, in extenuating circumstances, you can power off your Droplet from the control panel. This course of action is not recommend, as this action is the same as unplugging the server and may cause data corruption. To power off your server from the control panel, first navigate to the Droplets page in the control panel. Click on the name of the Droplet you are trying to connect to.

![Individual_Droplets](https://assets.digitalocean.com/site/ControlPanel/individual_Droplet.png)  

Once you’ve reached the individual Droplet’s page, click on the power icon and then select the power off button. 

![ControlPanel_PowerOff](https://assets.digitalocean.com/site/ControlPanel/PowerOff.png)

**Note**: Users are still billed for powered off servers. In order to avoid being billed for shutdown Droplets, please be sure to destroy your servers when you don’t need them. 

## What is console access?

Console access is out of band access to your Droplet via our HTML5 VNC console. This is the equivalent of plugging a monitor and keyboard directly to your virtual server. 

![Console_LogIn](https://assets.digitalocean.com/site/ControlPanel/Console_LogIn.png)

## How do I connect to the VNC console?

First, you want to navigate to the Droplets page in the control panel. Click on the name of the Droplet you are trying to connect to.

![Individual_Droplets](https://assets.digitalocean.com/site/ControlPanel/individual_Droplet.png)

From here you can connect to the console in two ways:

- You can connect to the VNC console from the upper right hand corner of the individual Droplet page:

![Console_Access_RightHand_Corner](https://assets.digitalocean.com/site/ControlPanel/Console_Access_1.png)

- You can connect to the VNC by clicking on the access icon and pressing the console access button

![Console_Access_Access_Icon](https://assets.digitalocean.com/site/ControlPanel/Console_Access_2.png)


If you are having issues connecting to your console, please reach out to [support](https://cloud.digitalocean.com/support).


## Why am I unable to connect to the console? Why do I see the “Failed to Establish Connection to Console” message?

We strive to ensure that the console is always reachable for users. However, if you run into an issue connecting to the console, we recommend checking the following to see if addressing them fixes the issue.

Are you:

- Behind a restrictive firewall:  Opening ports 6000-7000 will usually clear this up.

- Using a network with a double-NAT configuration.

- Accessing the console from behind a web-proxy (almost all mobile broadband connections configure a proxy).

-  Having a satellite or other high latency connection. This can cause timeouts.

If none of the following issues are at play, and you are still unable to connect, please open up a [support ticket](https://cloud.digitalocean.com/support) so that we may investigate the issue more closely. 


## Why isn’t my password showing in the console?

For security reasons, when you type in your password into a linux server, nothing is displayed. This is completely normal-- simply type in your password normally and press enter to use it.

![Password_Doesnt_Show](https://assets.digitalocean.com/site/ControlPanel/Password_No_Show.png)

