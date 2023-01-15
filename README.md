# macOS Ventura 13
# OpenCore v0.8.8
# ASUS-PRIME-Z590-P-I5-11600K-Hackintosh


#### 2. BIOS Settings

- Use following BIOS settings (DEL/F2 on boot):

  Advanced Mode (F7)

  ```sh
  Advanced
    - System Agent(SA) Configuration
      - VT-d: Enabled
    - Onboard Devices Configuration
      - Serial Port Configuration
        - Serial Port: Disabled
  Boot
    - CSM (Compatibility Support Module)
      - Launch CSM: Disabled
    - Secure Boot
      - OS Type: Other OS
      - Key Management
        - Clear Secure Boot Keys: Execute
    - Boot Configuration
      - Fast Boot: Disabled
      - Wait For 'F1' If Error: Disabled
  ```

---
