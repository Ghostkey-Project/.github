![image](https://github.com/user-attachments/assets/55fba3c8-7398-4c51-9b31-5ccd9eb6b09e)

The Ghostkey project initially started as a remote replacement for the [USB RUBBER DUCKY](https://shop.hak5.org/products/usb-rubber-ducky) made by Hak5, as I could not afford it. I discovered that I could replicate some of its capabilities using a XIAO SAMD21 board from Seeed Studio. This led me to explore how I could make it modular by adding other boards with Wi-Fi, like the ESP32C6, which allows triggering payloads and custom key injections remotely.

This development expanded to include creating C2 (command and control) servers for the Ghostkey hardware and implementing new payloads with more advanced capabilities. I added C2 nodes to the server system and storage-only servers for collecting data extracted from target systems. As I observed the potential of the server structure, it became clear that it could be compatible with any hardware, enabling new implementations and enhancements to the servers.

These resoulted on the new Ghostkey suite of tools
- https://github.com/Ghostkey-Project/Ghostkey
- https://github.com/Ghostkey-Project/Ghostkey_Server
- https://github.com/Ghostkey-Project/Ghostkey_Depo
- https://github.com/Ghostkey-Project/Ghostkey_Client


## 🚨 Disclaimer

The **Ghostkey project** is an **educational tool** created to study and demonstrate concepts in hardware exploitation, payload delivery, and command-and-control (C2) systems. While its functionality is similar to tools like the USB Rubber Ducky, this project is intended solely for ethical research, educational purposes, and controlled cybersecurity demonstrations.

### Important Notes:
- **For Ethical Use Only**: This project is designed to assist **cybersecurity professionals** in understanding attack techniques and improving defenses. It is strictly prohibited to use this tool for unauthorized activities or against systems you do not own or have explicit permission to test.
- **Not Deployment-Ready**: Ghostkey is an experimental project and has not undergone extensive testing or security hardening. Deploying it in real-world environments can lead to unpredictable results and potential legal consequences.
- **No Responsibility for Misuse**: 
  - I, the creator, do not condone or support the use of this tool for illegal, unethical, or malicious purposes.
  - Any misuse of this project, including activities that violate local laws or ethical guidelines, is entirely the responsibility of the user.
- **Understanding the Risks**: 
  - Unauthorized use of tools like Ghostkey can cause **serious legal repercussions**, including criminal charges.
  - Users must ensure compliance with local laws and ethical standards when using or modifying this project.

By cloning, modifying, or using any part of the Ghostkey project, you agree to use it responsibly and understand the potential consequences of misuse.
