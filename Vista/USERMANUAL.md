# Vista Player — User Manual

Vista is a lightweight viewer for immersive and standard video on iPhone and iPad. It is designed for inspecting VR180 side-by-side (SBS) footage, fisheye captures, and regular 2D video with precise, responsive controls.

This manual explains how to open videos, navigate the view, and use each playback mode.

---

## 1. Opening Videos

Vista supports two ways to open videos:

### A. Open Local Files
Tap **Open** to choose a video from your device using the system Files picker.

- Supported formats include `.mp4` and `.mov`
- Files may come from local storage or supported Files app locations
- Videos are played entirely on-device

### B. Open from Vista Server (Local Network)
Tap **Server** to browse a video library shared by a Vista Server running on your local network.

- Vista automatically discovers available servers
- You can also connect manually by entering a server address
- Videos stream over your local network without being copied to your device

> Vista Server is optional. If you do not use it, you can ignore the Server option and use local files only.

---

## 2. Playback Controls

### Play / Pause
- Tap **Play** or **Pause** to control playback
- Playback automatically starts after a video is loaded

### Scrubbing
- Drag the timeline slider to scrub through the video
- While scrubbing, Vista shows preview thumbnails to help you find a frame precisely

### Reset View
- Tap **Reset** to return the view to its default orientation and zoom

---

## 3. Viewing and Navigation

Vista uses direct touch gestures to explore the video.

### Orbit (Look Around)
- **Drag with one finger** to rotate the view
- Horizontal drag controls yaw (left/right)
- Vertical drag controls pitch (up/down)

### Zoom
- **Pinch** to zoom in or out
- Zoom adjusts the effective field of view rather than scaling the image
- This preserves correct geometry and avoids distortion

### Reset Gesture
- **Double-tap** anywhere on the view to reset yaw, pitch, and zoom

---

## 4. Projection Modes

Vista supports multiple projection types depending on the source video.

### Equirectangular (VR180 SBS)
For 180° side-by-side equirectangular video.

- Designed for VR180 cameras
- Uses correct hemisphere sampling
- Supports eye selection and stereo preview

### Fisheye
For equidistant fisheye captures.

- Intended for circular fisheye footage
- Includes a **Lens FOV** slider
- Match the slider to your camera’s lens specification (e.g. 180° or 190°)

### 2D
For standard flat video playback.

- Displays video as a normal rectilinear image
- Eye selection and stereo preview are disabled in this mode

---

## 5. Eye Selection and Stereo Preview

### Eye Selection
When supported by the projection mode, you can choose:

- **Left Eye**
- **Right Eye**

This selects which half of a side-by-side source is rendered.

### Stereo Preview
Enable **Stereo Preview** to view both eyes side-by-side at the same time.

- Useful for checking stereo alignment and consistency
- Eye selection is disabled while stereo preview is active

---

## 6. Aspect Ratio and Field of View Handling

Vista automatically adjusts its field-of-view calculations based on the screen size and orientation.

- Portrait and landscape orientations are handled correctly
- Vertical stretching is avoided on tall displays
- Field of view remains physically consistent across devices

---

## 7. Privacy and Data Handling

- Vista does not require an account
- No analytics or tracking services are used
- Videos opened locally stay on your device
- Videos streamed from Vista Server remain on your local network

---

## 8. Troubleshooting

### Video Won’t Play
- Confirm the file is a supported video format
- If streaming from a server, ensure the server is reachable on your network

### No Server Found
- Make sure Vista Server is running
- Ensure both devices are on the same local network
- Try manual connection if automatic discovery does not appear

### View Looks Distorted
- Confirm the correct projection mode is selected
- Adjust the Lens FOV when using fisheye sources
- Reset the view if needed

---

## 9. Intended Use

Vista is designed for:

- Reviewing VR180 footage
- Inspecting stereo video
- Checking fisheye captures
- Exploring immersive video without a headset

It is not intended for video editing or publishing.