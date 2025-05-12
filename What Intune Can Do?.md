# What you can do with Microsoft Intune

**1. Device Management (Enroll and Configure Devices)**
   - Automatically enroll Windows devices using `Windows Autopilot`, so they configure themselves right out of the box.
   - Enroll macOS via Apple Business Manager (ABM) and iOS/iPadOS devices using ADE (Automated Device Enrollment).
   - Enroll Android devices via Zero-Touch or Samsung Knox.

📌 Example: A new laptop arrives → it connects to Wi-Fi → Autopilot enrolls it into Intune → device is configured with company policies, apps, and settings automatically.

**2. App Management (Push Company Apps)**
   - Deploy apps like Zoom, Slack, Microsoft 365, Chrome, or internal tools.
   - Use required installs (forced) or available installs (user can install from Company Portal).

📌 Example: You can push Microsoft Teams and a custom VPN app silently to all employee laptops.

**3. Endpoint Security (Enforce Security Policies**
   - Require BitLocker encryption for Windows laptops.
   - Block jailbroken/rooted devices from accessing company data.
   - Enforce Windows Hello PIN, firewall settings, and antivirus (Defender).

📌 Example: If a device doesn’t have a secure password or BitLocker enabled, it’s marked non-compliant and access to Outlook is blocked.

**4. Manage Device Configurations**
   - Set up Wi-Fi, VPN, and email profiles without touching the device.
   - Apply PowerShell scripts for advanced customizations.

📌 Example: Configure a Wi-Fi profile with SSID and credentials so users don't have to enter them manually.

**5. Monitor and Support Devices**
  - See real-time device status (OS version, compliance, last check-in).
  - Use remote actions like wipe, restart, sync, or locate (for iOS/Android).

📌 Example: A user loses their phone — you wipe it remotely to protect company data.

**6. Conditional Access with Azure AD**
  - Block access to Outlook, SharePoint, or Teams if the device is not compliant.
  - Ensure only company-managed devices can access sensitive resources.

📌 Example: A user tries to access email from a personal device — they are prompted to enroll the device or are denied access.

**7. Reporting and Alerts**
  - View reports like "Devices not updated to the latest OS" or "Devices failing compliance".
  - Set alerts when devices fall out of compliance.

📌 Example: Get a weekly report of laptops with outdated antivirus definitions or missing updates.


