##How to Open a Minecraft Server on Your Phone 📱⛏️

1. Install Termux 📝
Download the Termux app from Play Store.
(Not sure if it's available on App Store)


2. Download Minecraft Server 💾
Open Google Chrome and search for the server.jar file you want
(Java, PaperMC, UTC, etc.)


3. Create a Folder on Your Phone 📂
Make a new folder in your phone’s internal storage (don’t use SD card)
Name it whatever you like, e.g., MC or MinecraftServer.


4. Move Server File 🚚
Put the server.jar file you downloaded into the folder you just created.


5. Install Java in Termux ☕
Open Termux and type:

pkg update
pkg install openjdk-17


6. Go to Your Server Folder 🗂️
Use the cd command to navigate to your server folder:

cd /path/to/your/folder


7. Run the Server ▶️
Start your server with this command:

java -Xmx1024M -Xms1024M -jar minecraft_server.1.21.8.jar nogui


8. Test Your Server ✅
Use the IP localhost to connect and test the server on your phone.

---
Tech by B dev
