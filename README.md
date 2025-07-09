# catWhatsapp

**catWhatsapp** is a lightweight Windows desktop application designed to automate WhatsApp messaging using `.xml` files. It allows users to send bulk messages through WhatsApp by simply placing message files into a designated folder.

---

## Features

- Secure WhatsApp login via QR code scanning.
- Automatic monitoring of a `watch_folder` for incoming message `.xml` files.
- Persistent session—no need to scan the QR code again after initial login.
- Uses a personal `hash.dat` file for secure identification.
- Simple, plug-and-play setup with minimal configuration.

---

## Installation & Usage

1. Download the ZIP package from the [official website](http://twostars.co.in/whatsapp/pages).
2. Obtain your personal `hash.dat` file from [here](https://twostars.co.in/whatsappApi.html).
3. Create a base folder and extract the ZIP contents into it.
4. Place your `hash.dat` file inside the base folder.
5. Run `catWhatsapp.exe` and scan the QR code with your WhatsApp mobile app.
6. Place `.xml` message files inside the automatically created `watch_folder`.
7. After initial setup, simply rerun the executable and drop new `.xml` files into `watch_folder`—no need to scan the QR code again.

> **Important:** Do not rename or move the default folders; the app relies on their names to function properly.

---
