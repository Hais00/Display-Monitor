<div align="center">
  <img src="media/logo1.png" alt="Logo" width="100" style="vertical-align: middle; margin-right: 10px;">
  <h1 style="display: inline; font-size: 2em; vertical-align: middle;">Display Monitor</h1>
</div>

### How to Use

This app is designed to provide an informative overlay, always visible on the screen, displaying information about sensors. The overlay is currently non-clickable to avoid interfering with other windows.

![Screenshot 1](media/screenshot1.png)  
![Screenshot 2](media/screenshot2.png)  
![Screenshot 3](media/screenshot3.png)

---

### Fan Management

The new fan management system offers three modes of operation:  

1. **Curve Mode**:  
   - Dynamically adjusts fan speeds based on the temperature of the monitored sensor.  
   - This mode is active only while the app is running; closing the app restores the fans to their default behavior.  

2. **Forced Mode**:  
   - Sets the fan speed to a fixed value, ensuring consistent performance.  

3. **Automatic Mode**:  
   - This is Apple’s default fan management system. Fans operate based on system firmware and thermal sensors.  

When the app is closed, all fan settings automatically revert to **Automatic Mode**, ensuring seamless transition back to Apple's default management.  

#### Detailed Fan View  
To access the detailed fan management interface, simply click on the **fan text** displayed below the graphs. This will open a comprehensive view of fan-related metrics and controls.  

---

### Requirements and Permissions

To fully utilize the app, ensure the following requirements are met:

1. **Apple Silicon or Intel**: Tested on M1/M4 (base models), but it may work on other Apple Silicon models.
2. **Accessibility Permissions**: Go to `System Preferences > Security & Privacy > Accessibility` and add the app to allow the overlay functionality.

---

### Key Features

- **Persistent Overlay**: The overlay remains visible at all times, providing continuous monitoring of system metrics.
- **Metal Overlay Integration**: While the app is running, it activates Metal's overlay to show information on FPS and GPU metrics on Metal games.
- **Extensive Personalization**: Customize the overlay to suit your preferences and needs:
  - **General Overlay Customization**:
    - Adjust **background color**, **size**, **position**, **border rounding**, and **opacity**.
    ![Screenshot 5](media/screenshot5.png)

  - **Category Customization**:
    - Create and manage **categories** to organize sensors.
    ![Screenshot 6](media/screenshot6.png)

    - Customize each category's **name**, **color**, and decide whether to display the **category name**.
    ![Screenshot 8](media/screenshot8.png)

    - Choose how categories are displayed: **new row** or **same row**.
  - **Sensor Customization**:
    - Personalize individual sensors with options to modify the **name**, **color**, and choose whether to display the sensor **name**.
    ![Screenshot 7](media/screenshot7.png)

This app was developed for fun and is not intended for professional use, though it can be useful for keeping an eye on system performance.

---

### Installation Instructions

To install the app, follow these steps:

1. Navigate to the [Releases](https://github.com/Hais00/Display-Monitor/releases) section of this repository.  
2. Download the `.dmg` file for the latest version.  
3. Open the `.dmg` file, and you'll find the app alongside a shortcut to the Applications folder.  
4. Drag and drop the app into the **Applications** folder shortcut to complete the installation.  
5. Launch the app from your Applications folder.  

---
