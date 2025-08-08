# Firefox Vertical Tabs Auto-Expand  

This tweak enables vertical tabs in Firefox to automatically expand when hovering over them, displaying full tab titles with a smooth animation.  

<img src="/demonstration.gif" alt="Demostración" width="450" />


>*To make this modification work, a small configuration in the browser is required, as described below:*

## 🛠️ Enable Legacy Toolkit and Set Up the `chrome` Folder  

To apply this style in Firefox, follow these steps:  

### 1️⃣ Enable `userChrome.css` Support  
1. Open Firefox and type in the address bar:  
`about:config`
2. Accept the warning message if it appears.  
3. Search for the preference:  
`toolkit.legacyUserProfileCustomizations.stylesheets`
4. Double-click it to set its value to `true`.  

### 2️⃣ Find the User Profile Folder  
1. Type in the address bar:  
`about:support`
2. Look for the **"Profile Folder"** section and click **"Open Folder"**.  
3. Inside the profile folder, locate (or create if it doesn't exist) a folder named `chrome`.  

### 3️⃣ Apply the Style  
1. Copy the `userChrome.css` file into the `chrome` folder.  
2. Restart Firefox for the changes to take effect.  

That's it! Now your vertical tabs will automatically expand when hovered over. 🚀  

>[!INFO]
>This repository is now deprecated, as Firefox has natively implemented this functionality.
However, I’ve included an additional stylesheet (userContent.css) that provides a cleaner, more minimalist look for the Firefox homepage and improves the current tab indicator in vertical tab view, as shown below.

<img width="1919" height="1041" alt="image" src="https://github.com/user-attachments/assets/10727147-7f74-4eff-9a66-aca2c8681e19" />
