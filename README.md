# Android Tablet Security and Optimization Project

## Project Objective
Secure and optimize an ONN brand Android tablet for a non-technical user, ensuring usability, performance, and security.

## User Requirements
- **Ease of Use:** No immediate login password required. The tablet remains stationary, accessible from a recliner.
- **Essential Applications:**
  - Email
  - Facebook
  - Google Docs
  - Browser with secure bookmarking capability
- **Security:** Install Proton Password Manager.
- **Safety:** Browser and installed games secured against accidental clicks.
- **Performance:** Lightweight OS optimized for low-spec tablet hardware.

## Technical Choices
- **ADB:** Utilizing Android Debug Bridge (ADB) from Windows PC to manage device.
- **Launcher:** KISS Launcher chosen for its simplicity, no widget support, and protection against accidental app rearrangements.
- **Security:**
  - **NextDNS:** Implemented for advanced DNS filtering and security without requiring a local VPN (opted out of Blokada for battery efficiency and memory usage).
- **Browser:** Brave browser selected for its Android optimization, built-in ad-blocking, and security features.
- **Family-Link:** Opting out of Google's Family-Link; relying instead on implemented security measures.
- **Performance Optimization:** Removal of unnecessary animations, termination of unused processes, and deletion of bloatware from Walmart and Google to enhance performance and battery life.

## Primary Applications Retained
- Outlook
- Walmart
- NewPipe
- Frameo (digital photo frame)
- Brave Browser
- NextDNS
- Proton Password Manager
- Facebook Lite (installed via F-Droid)
- Amazon
- Solitaire (ad-free version)
- Candy Crush
- eBay
- Google Drive
- Simple Gallery Pro (installed via F-Droid as a lightweight photo viewer)

## Software Sources
- Apps installed and managed through F-Droid for transparency and security.

## Implementation Summary
### **Configuration and Installation Process**
1. **Set up ADB on Windows PC** for remote management and debugging.
2. **Established ADB connection** to the tablet and ensured proper communication.
3. **Installed essential applications**:
   - **F-Droid** (for open-source app management)
   - **KISS Launcher** (lightweight launcher for ease of use)
   - **Brave Browser** (privacy-focused browsing)
   - **NextDNS** (for DNS-based ad and tracker blocking)
   - **Simple Gallery Pro** (photo viewer alternative to Google Photos)
   - **Facebook Lite** (low-resource social media app)
4. **Set KISS Launcher as default** to streamline user experience.
5. **Disabled/Uninstalled bloatware** using ADB to free up resources:
   - Chrome Browser
   - Find My Device
   - Google Partner Setup
   - Kids Space
   - Google Maps
   - Sound Recorder
   - YouTube Music
   - YouTube
   - Google Keep Notes
6. **Disabled Google Password Manager functionality** to ensure reliance on Proton Password Manager.
7. **Optimized performance** by:
   - Reducing background processes
   - Disabling unnecessary animations
   - Removing unused system apps
   - Implementing NextDNS for filtering without a local VPN

### **Testing and Verification**
After completing optimizations, the following tests were conducted:
- **App Functionality Test:** Confirmed all essential apps launched and performed as expected.
- **Internet & Connectivity Check:** Verified Wi-Fi stability and browsing functionality.
- **Security & Privacy Verification:** Ensured NextDNS filtering was active and Proton Password Manager was set as the default autofill provider.
- **Performance & Battery Efficiency:** Confirmed reduced background activity and improved responsiveness.

### **Project Completion & Final Notes**
The ONN tablet has been fully configured to meet the needs of the non-technical user. With a focus on security, usability, and performance, the following improvements were achieved:
- A simplified, distraction-free interface via **KISS Launcher**.
- A secure and private browsing experience using **Brave Browser** with **NextDNS filtering**.
- Removal of unnecessary Google services, optimizing battery life and memory usage.
- Reliance on **Proton Password Manager** for secure credential storage.

The tablet is now optimized for long-term stability, requiring minimal maintenance. Future changes can be easily implemented using ADB as needed.

---

This concludes the **Android Tablet Security and Optimization Project** documentation. Any further modifications or updates will be documented as needed.

