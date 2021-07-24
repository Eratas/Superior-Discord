# Superior-Discord
A new theme design for a Better Discord experience.
Based on Gibbu's [SimplyDark](https://discordstyles.github.io/SimplyDark/) (thank you!)

# Screenshots


Normal:

![normal](https://user-images.githubusercontent.com/62240722/126868102-30ec27ee-5110-4491-a75f-b6265416e5e3.png)



2 Columns:

![columns](https://user-images.githubusercontent.com/62240722/126868229-f1396d8b-8e74-4b2d-9229-051b0a68d1cb.png)



Settings 1/3:

![settings1](https://user-images.githubusercontent.com/62240722/126868279-2461f5a1-0c2c-47cb-9aa7-bf7e201226a0.png)



Settings 2/3:

![settings2](https://user-images.githubusercontent.com/62240722/126868307-bfb4ccf1-ceda-441d-a798-8fc4c6f9c725.png)



Settings 3/3:

![settings3](https://user-images.githubusercontent.com/62240722/126868330-d202085a-8a7d-404f-a81b-4b537dda5d35.png)



Horizontal Server List top/bottom settings are disabled by default, you can enable them anytime:

![settings4](https://user-images.githubusercontent.com/62240722/126868402-78fd7853-67b1-4dd2-8937-cf71708c1cf1.png)



# BetterDiscord Installation
1. [Download BetterDiscord](https://betterdiscord.app/) and the Theme file.
2. Drag the installer outside of your Downloads folder and run as Administrator.
3. Agree to the license.
4. Check Install and click next.
5. Click the Discord builds you wish to install BetterDiscord on.
	- For most users this will be Stable.
6. Click Install.
	- BetterDiscord will auto restart Discord for you. And if all is well you have BetterDiscord installed.
	- If you get errors or BetterDiscord isn't showing up. Join these servers and ask for help in the respective channels.
		- [BetterDiscord Primary Server](https://discord.gg/0Tmfo5ZbORCRqbAd)
		- [BetterDiscord Secondary Server](https://discord.gg/2HScm8j)
7. Open your User Settings page.
8. Scroll down and open your Themes tab.
9. Click the Open Themes Folder button.
10. Drag the "SuperiorDiscord.theme.css" file that you just downloaded into your themes folder (C:\Users\%user%\AppData\Roaming\BetterDiscord\themes).
11. Go back to your Themes tab in Discord and enable the Superior Discord theme.
12. Review the settings for a better personnal experience.

You can reload Discord anytime with <kbd>CTRL</kbd> + <kbd>R</kbd> while Discord is focused.

# Disable Discord Smooth Scrolling Bat file:
Create a text file in your discord folder and just copy past that inside, rename the file extention into .bat; you can replace the path with your own if it doesn't launch.
You can then create a shortcut of that .bat and pin it in the start menu.


cd C:\Users\%user%\AppData\Local\Discord

FOR /F "delims=" %%i IN ('dir /b /ad-h /t:c /od') DO SET a=%%i

start Update.exe

start %a%\Discord.exe --disable-smooth-scrolling


Thanks to r/u/Holycraplol for the bat.
Thanks to TabularElf for the testings.
