# Drehmal Apotheosis Server
This GitHub page serves as a guide to install the client for my Drehmal survival adventure map server and as a repository that holds all the required and optional mods. This also serves as practice for markdown documentation for you dickheads who think I'm doin too much.

## Drehmal Apotheosis
![Drehmal Apotheosis landscape image](https://wiki.drehmal.cyou/assets/img/primal_start.png)

This server will be running the Drehmal: Apotheosis survival-adventure map. A massive, rich open world with an original storyline, many custom gameplay features, expansive lore, and more. The most recent version of Drehmal is v2.2.2: Apotheosis, built for Minecraft Java Edition 1.20.1. 

The main page for the map can be found [here](https://www.drehmal.net/), and the wiki page for the map can be found [here](https://wiki.drehmal.cyou/).

## Install Guide
It is recommended that you install the map and the required modpack through the Prism Launcher. The Prism Launcher is an all-in-one launcher that allows you to install modpacks, resource packs, shader packs, maps and extensively configure Minecraft. The map and modpack can easily be found and installed using Modrinth within the launcher. If you have not yet installed the Prism Launcher, the installer can be directly downloaded using the link [here](https://github.com/PrismLauncher/PrismLauncher/releases/download/10.0.5/PrismLauncher-Windows-MSVC-Setup-10.0.5.exe).

If this is your first time installing the Prism Launcher, open the header below for instructions on how to log into your Minecraft account.

<details>
  <summary>Logging into Minecraft</summary>

  To log into your Minecraft account, you will have to log into the Prism Launcher using the Microsoft account associated with your Minecraft license. Open the Prism Launcher and you should find the Accounts button on the top-right of the application as shown below. Press it and select the option "Manage Accounts..." as shown on the image below.

  ![prism launcher manage accounts](/assets/manage%20accounts.png)

  The Prism Launcher settings window within the Accounts section should have opened. On the right side of the window, you should see the option to add your Microsoft account labelled "Add Microsoft".

  ![prism launcher settings add microsoft](/assets/settings%20-%20add%20microsoft.png)

  Once selected, a new window should have opened up that will allow you to log into your Microsoft account. It will allow you to login by either opening a link to manually login with your credentials, or by scanning a QR code or using https://www.microsoft.com/link to enter a code to login. Either option is fine, but both will require you to login to your Microsoft account. The login process may differ for the option you choose, so please follow the directions provided by the login process. 

  **Please ensure that the Microsoft account you are logging into is accociated with a valid Minecraft account. If you use the wrong account, you may receive an error when logging in.**

  Once you are done logging into your Microsoft account, you should see your Minecraft account appear on the Accounts setting. 

  If for any reason you are still having errors when logging into your Microsoft account AND you are certain that the account you are logging into has a valid Minecraft license/account, you may need to try the options below:
  - Ensure that the Microsoft Account you are logging into contains a valid Minecraft license/account. To check if your Microsoft account has one, log into the Minecraft page [here](https://www.minecraft.net/en-us/msaprofile). This link should show you if you own Minecraft with this account.
  - Log into your Microsoft account and open your account settings using the link [here](https://account.microsoft.com/). On the left side of the webpage, open "Your info". Under "Date of birth", enter a date that would give your account an age over 18.
  - Use your Microsoft account to log into Xbox [here](https://www.xbox.com/en-US/).

  Once you have done the above. Attempt to log into your Microsoft account through the Prism Launcher again. If you are still having issues, let me know. 

</details>


If it has been a while since you last played Minecraft, you may need to install the Java Runtime Environment (JRE) again. Open the header below for instructions on installing JRE.

<details>
  <summary>Installing Java</summary>

  The download page for JRE can be found [here](https://www.java.com/en/download/manual.jsp). For Windows users, you can either download using the "Windows Online" or "Windows Offline (64-bit)" link. I would recommend that you use the "Windows Offline (64-bit)" link as you can ensure you are installing the 64-bit version. Download and run the installer. Follow the instructions as indicated by the installer. You do not need to change any options unless you wish to. Once you have completed installing Java, open the Settings on the Prism Launcher. On the left side of the Settings window, select Java. Under "Java Executable" you should see a path that points to the executable "javaw.exe". If you installed JRE correctly, you may already see a path that points to javaw.exe. If not, you may need to click on "Detect" to find your installation of JRE. Select the runtime that is within your Program Files, and the highest version value. Recommended version is equal to or greater than 17.0.**. Select your desired runtime and press OK. 
  
  The image below shows where you can find how you set your Java runtime and an example of a valid path. 

  ![prism launcher java runtime path](/assets/java%20runtime%20path.png) 

</details>


At this point, if you have not already, it may be a good idea to set your memory allocation for Minecraft as well. The following dropdown header provides instructions on setting you memory allocation values.

<details>
<summary>Setting Memory Allocation</summary>
 Open the settings within the Prism Launcher and open the Java section. This is also the window where you set your JRE path. On the middle of the window, you will see the "Memory" section. This section allows you to set your minimum and maximum memory allocation. 

These values need to be based on your total system memory. You can find this by doing either of the following: 
- Task Manager - Open Task Manager by pressing the following hot-key `Ctrl + Shift + Esc`. Once open, select the "Performance" icon on the left of the window. Under "Performance", select "Memory". This should open the usage graph for your system memory. On the top-right of the graph, you will see the your total amount of system memory. 
- System Information - Open the System Information control panel by searching for `sysinfo` using Windows search and selecting "System Information". The System Information window should already have the "System Summary" open. If not, select it on the left pane. Under System Summary, you will find the "Total Physical Memory" and you will see a value to the right of that. That value is your total system memory.

Now that you know how much system memory you have, you may find that it may be either 32GB or 16GB. 
- If you have 16GB of total system memory, it is recommended to enter the value `8192 MiB` onto both "Minimum Memory Usage" and "Maximum Memory Usage".
- If you have 32GB or more of total system memory, it is recommended you enter a value equal or between `8192 MiB` and `16384 MiB` for "Minimum Memory Usage", and `16384 MiB` for "Maximum Memory Usage".

Ensure that the "Minimum Memory Usage" value is less than the "Maximum Memory Usage".

The image below shows where you set your memory allocations and examples of memory allocation values set for a 32GB total memory system.

![prism launcher java memory allocation](/assets/java%20memory%20allocation.png)

</details>

### Creating and Installing Drehmal Instance

In this section, a new Minecraft instance will created to install Minecraft and the Drehmal modpack. On the Prism Launcher main window, press the option to add a new instance in the top-left labeled "Add Instance". This will open a new window that will let you create your instance and select your modpack. The window will open the `Custom` section by default. Do not edit any settings. Select the section `Modrinth`. On the search bar, enter "drehmal". You probably may not find the modpack at first. If this is the case, try re-entering "drehmal" or typing in "drehmal apotheosis" as well. 

At this point, you should have found the "Drehmal" modpack. Select the modpack and on the bottom-right, you should find a drop-down that allows you to select the version. Ensure `Drehmal 2.2.2f for 1.20.1 - [release]` is selected. Press OK. 

![drehmal modpack selection](/assets/drehmal%20modpack%20select.png)

After pressing OK, the modpack will download and install. After that finishes, your instance should be ready to play. Double click or highlight the icon and press Launch to play.

## (OPTIONAL) Installing QOL Mods
Although optional, you can also install a variety of quality-of-life mods through to make your experience better.

> [!NOTE]
> The full mod list for this modpack can be found [here](https://www.drehmal.net/2-2-mod-list). Some mods include performance boosting mods and a shader mod.
