# ⛰️ Drehmal Apotheosis Server ⚔️
This GitHub page serves as a guide to install the client for my Drehmal survival adventure map server and as a repository that holds all the required and optional mods. This also serves as practice for markdown documentation.

## Drehmal Apotheosis
![Drehmal Apotheosis landscape image](https://wiki.drehmal.cyou/assets/img/primal_start.png)
![Drehmal Apotheosis ice](https://static.wixstatic.com/media/a539b0_26044d9ff9f343deaebcc6df8bee7436~mv2.png/v1/fit/w_2380,h_1169,q_90,enc_avif,quality_auto/a539b0_26044d9ff9f343deaebcc6df8bee7436~mv2.png)
![Drehmal Apotheosis lava castle](https://static.wixstatic.com/media/a539b0_ac13eaceee51493da4d7a43092289553~mv2.png/v1/fit/w_1920,h_1080,q_90,enc_avif,quality_auto/a539b0_ac13eaceee51493da4d7a43092289553~mv2.png)

This server will be running the Drehmal: Apotheosis survival-adventure map. A massive, rich open world with an original storyline, many custom gameplay features, expansive lore, and more. In order to join the server and play this map, it is required to install a modified version of Drehmal's latest modpack, Apotheosis v2.2.2 for Minecraft Java Edition 1.20.1.

The main page for the map and the wiki page can be found below.

* [Drehmal](https://www.drehmal.net/)
* [Wiki Page](https://wiki.drehmal.cyou/)

## Installing and Setting Up Prism
It is highly recommended that you install the required modpack for this custom map through the Prism Launcher. The Prism Launcher is an all-in-one launcher that allows you to install modpacks, resource packs, shader packs, maps and extensively configure Minecraft. If you have not yet installed and configured Prism, the installer can be directly downloaded using the link below.

* [Prism Launcher](https://github.com/PrismLauncher/PrismLauncher/releases/download/10.0.5/PrismLauncher-Windows-MSVC-Setup-10.0.5.exe)

If this is your first time installing the Prism Launcher, open the headers below for directions on how to configure Prism before creating the modded instance.

<details>
  <summary>Logging into Minecraft</summary>

  <br>To log into your Minecraft account, you will have to log into the Prism Launcher using the Microsoft account associated with your Minecraft license. Open the Prism Launcher and you should find the Accounts button on the top-right of the application as shown below. Press it and select the option "Manage Accounts..." as shown on the image below.

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

<details>
  <summary>Installing Java</summary>

  <br>
  The download page for Java can be found below.

  * [Java Runtime Environment Download Page](https://www.java.com/en/download/manual.jsp)
  
  For Windows users, you can either download using the "Windows Online" or "Windows Offline (64-bit)" link. It is recommend that you use the "Windows Offline (64-bit)" link as you can ensure you are installing the 64-bit version. Download and run the installer. Follow the instructions as indicated by the installer. You do not need to change any options unless you wish to. 
  
  Once you have completed installing Java, open the Settings on the Prism Launcher. On the left side of the Settings window, select Java. Under "Java Executable" you should see a path that points to the executable "javaw.exe". If you installed JRE correctly, you may already see the textbox occupied by a filepath that points to javaw.exe. If not, you may need to click on "Detect" to find your installation of JRE. Select the runtime that is within your Program Files, and contains the highest version value. Recommended version is equal to or greater than 17.0.**. Once you have selected your desired runtime, press OK. 
  
  The image below shows where you can find how you set your Java runtime and an example of a valid filepath. 

  ![prism launcher java runtime path](/assets/java%20runtime%20path.png) 

</details>


<details>
<summary>Setting Memory Allocation</summary>
 <br>Open the settings within the Prism Launcher and open the Java section. This is also the window where you set your JRE path. On the middle of the window, you will see the "Memory" section. This section allows you to set your minimum and maximum memory allocation. 

<br>These values need to be based on your total system memory. You can find this by doing either of the following: 
- Task Manager - Open Task Manager by pressing the following hot-key `Ctrl + Shift + Esc`. Once open, select the "Performance" icon on the left of the window. Under "Performance", select "Memory". This should open the usage graph for your system memory. On the top-right of the graph, you will see the your total amount of system memory. 
- System Information - Open the System Information control panel by searching for `sysinfo` using Windows search and selecting "System Information". The System Information window should already have the "System Summary" open. If not, select it on the left pane. Under System Summary, you will find the "Total Physical Memory" and you will see a value to the right of that. That value is your total system memory.

Now that you know how much system memory you have, you may find that it may be either 32GB or 16GB. 
- If you have 16GB of total system memory, it is recommended to enter the value `8192 MiB` onto both "Minimum Memory Usage" and "Maximum Memory Usage".
- If you have 32GB or more of total system memory, it is recommended you enter a value equal or between `8192 MiB` and `16384 MiB` for "Minimum Memory Usage", and `16384 MiB` for "Maximum Memory Usage".

Ensure that the "Minimum Memory Usage" value is less than the "Maximum Memory Usage".

The image below shows where you set your memory allocations and examples of memory allocation values set for a 32GB total memory system.

![prism launcher java memory allocation](/assets/java%20memory%20allocation.png)

</details>

## Creating Your Minecraft Instance

With a fully setup Prism Launcher client, an instance can now be created which will contain your modded Minecraft installation. While an official modpack already exists for Drehmal, a custom modpack was created to include a few more quality-of-life mods and shaders. If you have not already, please download the latest release of my custom modpack within the "Releases" section on the right side of the top of this page. A list of those mods plus details can be seen in the collapsed section below.

<details>
<summary>Added Mods and Shaders</summary>
<br>The following mods and shaders have been added in addition to the base modpack.

Mods:
- AppleSkin - Hunger-related HUD improvements
- Axiom - World Edit Utility
- BetterF3 - Better Debug Menu
- Cloth Config - API Dependency for BetterF3
- Distant Horizons - Established extended render distance mod (not enabled - see [here](https://github.com/leelancarbonell/drehmal-server#voxy-and-distant-horizons---extend-your-render-distance))
- Jade - "What am I looking at" UI
- Just Enough Items - Item and recipe menu within your inventory
- Simple Voice Chat - Voice Chat within Minecraft
- Voxy - Newly released extended render distance mod (not enabled - see [here](https://github.com/leelancarbonell/drehmal-server#voxy-and-distant-horizons---extend-your-render-distance))
- Xaero's Minimap - Minimap
- Xaero's World Map - Fullscreen Map
- You're in Grave Danger - Death grave

Shaders: (These shaders *should* all be compatible with the Voxy render distance extending mod)
- Bliss Shader - Unstable
- BSL Shaders
- Eclipse Shader - Fork of Bliss, HIGHLY RECOMMENDED, Unstable
- I Like Vanilla
- Scrumptious Shayders
- Shrimple
- Solas Shader
- Sundial Lite

</details>


To get started on creating your new instance, make sure you are on the main window on Prism, and select "Add Instance" on the top-left of the window. This will open a new window that will let you create your instance and select your modpack. Enter the name you want your instance to be labeled, and then select "Import" on the left side of the window. Here you will enter the location of the custom modpack. 

> [!IMPORTANT]
> To find the custom modpack file, locate the "Releases" section on the right side of the main repository webpage. Click on the link for the latest release. On the latest release page, you will find details about this release and the `.mrpack` modpack file. **You do not need to download the file.** Copy the link address to the modpack file and paste it to the "Local file or link to a direct download:" text input within the import menu in Prism. 

The image below shows the Import menu when creating a new instance with an example link pointing to the modpack.

![prism import modpack](/assets/import%20modpack.png)

> [!CAUTION]
> **DO NOT USE THE LINK FOUND IN THE SCREENSHOT. This links to a development modpack and it is different from latest release!!**

Once you have located the modpack on the Import menu, press "OK" to install the modpack and create the instance. Once created, your instance should be ready to play. Double click or highlight the icon and press "Launch" to play. On your first launch of this instance, Prism will also download and install Minecraft.

You are now ready to play Minecraft on the Drehmal: Apotheosis survival-adventure map server!

<!--
In this section, a new Minecraft instance will created to install Minecraft and the Drehmal modpack. On the Prism Launcher main window, press the option to add a new instance in the top-left labeled "Add Instance". This will open a new window that will let you create your instance and select your modpack. The window will open the `Custom` section by default. Do not edit any settings. Select the section `Modrinth`. On the search bar, enter "drehmal". You probably may not find the modpack at first. If this is the case, try re-entering "drehmal" or typing in "drehmal apotheosis" as well. 

At this point, you should have found the "Drehmal" modpack. Select the modpack and on the bottom-right, you should find a drop-down that allows you to select the version. Ensure `Drehmal 2.2.2f for 1.20.1 - [release]` is selected. Press OK. 

![drehmal modpack selection](/assets/drehmal%20modpack%20select.png)

After pressing OK, the modpack will download and install. After that finishes, your instance should be ready to play. Double click or highlight the icon and press Launch to play.

-->

## (OPTIONAL) Installing Additional Mods, Shaders, and Resource Packs
Although optional, you can also install a variety of client-side, quality-of-life mods through to make your experience better.

> [!NOTE]
> The full mod list for this modpack can be found [here](https://www.drehmal.net/2-2-mod-list). Performance boosting mods, dynamic lighting, zoom, and a shader engine is already included with the modpack.


To install additional mods, select your instance on the main Prism Launcher window by clicking on the instance icon once, and clicking "Edit" on the right side of the window. A window that changes the settings for this instance should open. On the left side of the window, select the "Mods" section. On this section, you will see the mods installed on this instance. To install more mods, press "Download Mods" on the right side of the window. A window opens that allows you to search for, download, and install mods easily. 

> [!WARNING]
> To maintain modpack consistency, it is highly recommended that you find and download your mods through Modrinth. However, if the specific mod you are looking for is exclusive to CurseForge, you can change that on the left side of the window.

Search for the mod using the search bar and select it by clicking on the desired mod. The details of the mod will appear on the pane at the right side of the window. Select the desired version of the mod using the drop-down menu at the bottom-right of the window if needed, and press "Select mod for download" to check the mod for download and installation. From here, you can install additional mods if you wish. 

![prism mod installer](/assets/mod%20installer.png)

> [!IMPORTANT]
> If you want to install a mod that is not found in Modrinth and CurseForge, you will have to manually download and install it through Prism. Download your desired `.jar` mod file and open the "Mods" section on the Console window found when editing your instance. Instead of opening the mod downloader using "Download Mods", click on "Add File". This will open the file picker window where you will need to locate and open the mod file you just downloaded. After selecting and opening your mod file through the file picker, you will then see the mod you installed within the list of installed mods. 


Some examples of QOL mods that can elevate your Minecraft experience:
<!--
* Distant Horizons - Allows you to render terrain at extreme distances using LODs without a significant performance hit. All shaders should be compatible with this mod.
* --OR--
* [Voxy](https://github.com/LunaticWasTaken/voxy) - Same as Distant Horizons, but LOD quality is much higher while still delivering exceptional performance. A backport is required and cannot be found using Prism, and must be installed manually through their repository. **Be warned!! Only certain shaders are compatible with this mod.** I have included a set of shaders pre-installed within the modpack that *should* work with Voxy.
-->
* Presence-Footsteps - Revamped sounds and audio for block interactions. 
* AmbientSounds - Adds a rich ambience to the minecraft world.
* Falling Leaves - Adds a neat little particle effect to leaf blocks.
* Sound Physics Remastered - Adds realistic sound effects.

Resource Packs and Shader Packs can be downloaded and installed similarly to how you install mods. Instead of opening the "Mods" section in your instance's console window, simply select Resource Packs or Shader Packs on the left and download and install them as you would with mods.

## Voxy/Distant Horizons - Dramatically extend your render distance! (HIGHLY RECOMMENDED)
Voxy and Distant Horizons are two very similar mods that try to achieve a similar goal&mdash;massively extend the render distance of Minecraft's landscape at a low performance cost by using LODs (level of detail). For a map such as this, it is highly recommend you install one of these mods so you can get a massive view of the map's beautiful landscape. 



### Voxy:
![voxy](https://cdn.modrinth.com/data/cached_images/480a6c99db0149653a13152e5247216b771f9ead.jpeg)

### Distant Horizons
![distant horizons](https://wsrv.nl/?url=https%3A%2F%2Fmedia.forgecdn.net%2Fattachments%2F880%2F249%2Fdh-512-rd.jpg&n=-1)

There are, however, a few distinct differences between the two mods, each presenting with its own benefits and drawbacks that are important to consider when you are choosing to enable one or the other.


| Feature | Voxy | Distant Horizons |
|----------|--------|------------------|
| Performance | ✅ Higher performance | ⚠️ Lower performance |
| LOD Quality | ✅ High resolution textured LODs | ❌ Lower resolution flat LODs |
| Shader Support | ❌ Limited – shaders must explicitly support Voxy | ✅ Full shader support |
| Development Status | ⚠️ Early development phase | ✅ Fully developed & established |

<br>For a more comprehensive comparison between the two mods, check out the video below.


<a href="https://www.youtube.com/watch?v=9kWQQUn6Sgc">
  <img src="https://cdn.discordapp.com/attachments/672480450144370691/1476327598253412515/eyTnTDxV3h7bweDzoOhARWltIKZFzRlWREBARVJUQAv8DtF6OUVdFQ50AAAAASUVORK5CYII.png?ex=69a0b8b8&is=699f6738&hm=6ac739867235b8c236e178bee279b09973256e8966ee20da619ef952a5cde38a&" alt="YouTube Video" width="600">
</a>

<br>Both mods are included in the modpack, but are disabled by default. If you want to use one of these mods, you can find them in the list of mods within the "Mods" section when you edit your modpack instance. 

> [!WARNING]
> Do not enable both mods at the same time. The mods may conflict with each other and may cause errors or prevent your instance from launching!

> [!NOTE]
> The modpack comes pre-installed with a set of shaders that should be compatible with Voxy. You can find a full list of compatible shaders [here](https://gist.github.com/appleneko2001/51dcf842c934db4c6201146f2e594953).

> [!TIP]
> Using Voxy? You can import the world file for Drehmal so you can get Voxy to start rendering far distances without needing to discover chunks! Download the world file [here](https://drive.google.com/file/d/14p5Z7mGCRNh5qkEt4wkOdtlu1rD4G7_Q/view?usp=sharing) and add it to your list of worlds when editing your instance within the "Worlds" section. You can then import the world map when joining the server by copying and pasting `/voxy import world "§6§lDrehmal： §6§lAPOTHEOSIS"` in the chat.


## Updating Modpack

In case the modpack is updated with more mods post-release, you will need to download the modpack and import it into your existing instance. Find the latest custom modpack release within the "Releases" section on the right side of the main repository webpage. 

> [!IMPORTANT]
> Unlike creating a new instance where you simply copy and pasted the file link, you are required to download the `.mrpack` modpack file to update your instance's modpack. 

Click on the file link to download the file. Once downloaded, open Prism and select your existing instance that contains your outdated modpack by single clicking on the associated icon, and click "Edit" on the right side of the main window. Once the Console window for your instance opens, select "Modrinth" on the left side of the window, and click "Update From File". A file picker window should have opened. Locate the updated `.mrpack` modpack file you just downloaded and open it. Prism will then automatically install the new mods and will then prompt you if the update is successful. From here, installation should be successful, and you can launch your instance and start playing with the updated modpack.

## Credits
* Drehmal - https://www.drehmal.net/
* Prism Launcher - https://prismlauncher.org/
* Modrinth - https://modrinth.com/
* Voxy Compatible Shaders - https://gist.github.com/appleneko2001/51dcf842c934db4c6201146f2e594953
* Images in the introduction section are taken from the Drehmal website and is rightfully owned by the Drehmal team and Lux Nova Studios.
