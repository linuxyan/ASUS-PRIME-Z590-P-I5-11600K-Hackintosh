# macOS Ventura 13
# OpenCore v0.8.8
# ASUS-PRIME-Z590-P-I5-11600K-Hackintosh


#### 2. BIOS Settings

- Use following BIOS settings (DEL/F2 on boot):

  Advanced Mode (F7)

  ```sh
  Boot
    - CSM (Compatibility Support Module)
      - Launch CSM: Disabled
    - Secure Boot
      - OS Type: Windows UEFI mode
      - Key Management
        - Clear Secure Boot Keys: Execute
    - Boot Configuration
      - Fast Boot: Disabled
      - POST Delay Time: 0 sec
      - Wait For 'F1' If Error: Disabled
  ```

---
