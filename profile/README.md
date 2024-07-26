![image](https://github.com/user-attachments/assets/55fba3c8-7398-4c51-9b31-5ccd9eb6b09e)

The Ghostkey project initially started as a remote replacement for the [USB RUBBER DUCKY](https://shop.hak5.org/products/usb-rubber-ducky) made by Hak5, as I could not afford it. I discovered that I could replicate some of its capabilities using a XIAO SAMD21 board from Seeed Studio. This led me to explore how I could make it modular by adding other boards with Wi-Fi, like the ESP32C6, which allows triggering payloads and custom key injections remotely.

This development expanded to include creating C2 (command and control) servers for the Ghostkey hardware and implementing new payloads with more advanced capabilities. I added C2 nodes to the server system and storage-only servers for collecting data extracted from target systems. As I observed the potential of the server structure, it became clear that it could be compatible with any hardware, enabling new implementations and enhancements to the servers.

These resoulted on the new Ghostkey suite of tools
- https://github.com/Ghostkey-Project/Ghostkey
- https://github.com/Ghostkey-Project/Ghostkey_Server
- https://github.com/Ghostkey-Project/Ghostkey_Depo
- https://github.com/Ghostkey-Project/Ghostkey_Client
