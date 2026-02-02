# VistaServer — User Manual

VistaServer is an optional companion app for Vista. It runs on macOS and allows Vista on iPhone or iPad to browse and stream videos stored on your computer over your local network.

VistaServer is designed to keep your media local, private, and under your control—no cloud services or uploads required.

---

## 1. What VistaServer Does

VistaServer turns a folder on your Mac into a browsable video library that Vista can access over your local network.

With VistaServer, you can:
- Keep large video files on your computer
- Browse and select videos from Vista on iPhone or iPad
- Stream and seek videos without copying them to your device
- Avoid cloud storage and external servers

VistaServer is optional. Vista works fully with local files even if VistaServer is not running.

---

## 2. Requirements

- macOS computer
- VistaServer running on the same local network as your iPhone or iPad
- Vista app installed on your iOS or iPadOS device

Both devices must be connected to the same local network (Wi-Fi or wired LAN).

---

## 3. Choosing a Library Folder

When you first launch VistaServer, you will be asked to select a folder.

### Selecting a Folder
- Click **Choose Folder** (or **Grant Access**)
- Select a folder that contains your video files
- VistaServer will scan the folder and build a video library

You can change the selected folder at any time.

### Folder Permissions
VistaServer uses macOS security-scoped access:
- Access is limited to the folder you choose
- No other files or folders are accessed
- Permissions are stored securely by macOS

---

## 4. Starting and Stopping the Server

### Start the Server
- Click **Start Server**
- VistaServer will begin running and sharing your library
- The server status will change to **Running**
- One or more server addresses will be shown

### Stop the Server
- Click **Stop Server**
- Network access will stop immediately

The server can be started and stopped at any time.

---

## 5. Discovering VistaServer from Vista

When VistaServer is running, Vista can find it automatically.

### Automatic Discovery
- Vista uses local network discovery
- Available VistaServer instances appear automatically in the Server browser

### Manual Connection
If automatic discovery does not work:
- Enter the server address shown in VistaServer
- Example: `http://192.168.1.10:8080`

---

## 6. Browsing and Playing Videos

From Vista:
1. Tap **Server**
2. Select a VistaServer
3. Browse the library list
4. Tap a video to play

Videos stream directly from your computer to your device. Files are not copied unless you choose to copy them yourself outside of Vista.

---

## 7. Authentication (Optional)

VistaServer can optionally require an access token.

### Enabling Authentication
- Turn on **Require Authentication**
- VistaServer will generate a token automatically
- You may regenerate the token at any time

### Using the Token in Vista
- Enter the token when connecting to the server
- The token is sent only to your local server
- No credentials are sent externally

Authentication is optional and intended for shared or less-trusted networks.

---

## 8. Network Behavior

- VistaServer runs a lightweight local HTTP server
- All traffic stays on your local network
- Videos are streamed with support for seeking and scrubbing
- No internet connection is required once devices are connected locally

VistaServer does not connect to external services.

---

## 9. Privacy

- VistaServer does not collect analytics
- VistaServer does not track usage
- No personal data is transmitted
- No video content is uploaded to the cloud

All data stays between your devices on your network.

---

## 10. Troubleshooting

### Vista Can’t Find the Server
- Make sure VistaServer is running
- Confirm both devices are on the same local network
- Try manual connection using the server address

### Videos Don’t Appear
- Confirm the selected folder contains supported video files
- Restart the server to rescan the library

### Playback Issues
- Ensure network connection is stable
- Try stopping and restarting the server
- Confirm the file plays locally on your Mac

---

## 11. Intended Use

VistaServer is intended for:
- Streaming large VR180 or 2D videos from a computer
- Reviewing footage without copying files
- Private, local-network media access

VistaServer is not intended as a public or internet-facing media server.