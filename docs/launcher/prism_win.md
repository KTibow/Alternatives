# Migrating from SkyClient in the official launcher to Prism

Recently, the default Minecraft launcher has been having a lot of issues. Almost every week it feels like Mojang manages to break something. Since SkyClient is a modded version of an already old version, Mojang probably won't care, so it's recommended to switch to Prism Launcher since the devs care about modding and old versions of Minecraft.

Note: Despite this guide looking long, this is a simple process and will only take a few minutes.

## 1: Install Java

In order to launch SkyClient you need Java. Unlike the default Minecraft launcher, Prism does not come bundled with Java, so we must install it ourselves. We'll be downloading Java from [Adoptium](https://adoptium.net/temurin/releases/) (an open source JRE made by a reputable source).

Filter the dropdown boxes with these options:
- Operating System: Windows
- Architecture: x64
- Package Type: JRE
- Version: 8 or 18 (it's a good idea to get both so you can use new and old versions of Minecraft; download one of them, then download the other after)

For each version of Java, download and run the `.msi` option, and go through the installation process.

### Step 2 - Installing Prism

[Download Prism Launcher](https://prismlauncher.org/download/). You will most likely want to download the `Installer (.exe)` version. Once it is finished downloading, it may give a warning screen saying "Windows protected your PC". Simply press the "More info" button, then "Run anyway"

Continue the installation process until you get to the "Java" screen. Here, you will decide which Java you want to set as the default for new instances. Click on the version that says "1.8" at the beginning of the version and has "Eclipse Foundation" in the path name. This is your Java 8 and it will be the default version of Java for every new instance you create on Prism. Of course, you can always change this later and can still manually specify a different version of Java whenever you want.

For the Minimum and Maximum memory allocation, leave them at 512 MiB and 4096 MiB respectively, unless you only have 8GB of ram or less, in which case you may want to cchange the maximum to 2048 MiB.

After this, continue with the installation process as normal.

### Step 3 - Logging in

Now that we've installed Prism, let's log in. Once Prism has launched, you should see a Steve head and "Profiles" text in the top right. Click on this and press "Manage Accounts". From here, click "Add Microsoft" on the right side menu. This will open a popup window, which will have a button to open the link to verify yourself and also copy the code. Simply paste the code into the window that opens up. Note, you may need to sign in to your Microsoft account first.

Once this is completed, you can exit back to the main Prism Launcher menu. Click on the button at the top left that says "Add Instance".

### Step 4 - Creating an Instance

This guide will focus on 1.8.9, but steps for other versions should also be obvious.

Click on the button on the top left that says "Add Instance". Name it whatever you want and giving a group for it is optional, but I do not recommend giving a group name until you need to better organize your instances.

Under the `Version` selector, scroll down till you find 1.8.9 and select it. Then in the `Mod Loader` tab underneath, choose Forge. It will automatically choose the latest version of Forge for 1.8.9 for you. Simply click "OK" to proceed. You should now be back on the main Prism page.

## Step 5 - Installing our mods

Now that we've installed Forge 1.8.9, we need to move all our mods to the new Prism Launcher folder. To do that, we'll right click our new instance and press `Edit`. Now, we'll go to the `Mods` tab. On the bottom right, there will be a button called `View Folder`. Click on this and you should be redirected to a file explorer tab. Now, open a new file explorer by either pressing `Win + E` on your keyboard or right clicking the file explorer icon and pressing "File Explorer". Navigate to your old .minecraft folder, which is `C:\Users\USER\AppData\Roaming\.minecraft` (change USER to your computer's name, or if you don't know it, navigate there manually). Open the `.minecraft` file, then open the `skyclient` file if you were using Skyclient. Simply move everything in the skyclient folder into the Prism Launcher .minecraft folder that you opened earlier. Once this is done, you should be able to see all your mods in the Mods tab, and can launch the instance.

### Step 6 - Explore

Prism Launcher has a lot of things to offer, such as themes if you don't like the look of it, as well as a lot of options for your instances, including the ability to see all your mods, resource packs, and worlds in the launcher before launching. You can use these menus to install mods and resource packs, and even update mods if they are hosted on Modrinth or CurseForge!

## Step 7 - Updating Prism

- WIP
