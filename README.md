# ESP32drivers

A collection of drivers and libraries for ESP32 boards.

---

## Installation Instructions
(imgs/foldersgit.png)
---
### CP210x Driver

1. Download the ZIP file (Click the download icon labeled as "download raw file").
   (imgs/cp210.png)
   (imgs/dlzipcp210.png)
3. Extract it to your preferred folder.
4. Locate `silabser.inf`.
   (imgs/silab.png)
6. Right-click and select **Install**.

---

### CH34x Driver

1. Download the `CH341SER.EXE` file.
2. Open the file.
   (imgs/ch34.png)
4. Click **Install**.

---

## Arduino IDE Installation

1. Download the Arduino IDE from:  
   [https://www.arduino.cc/en/software/](https://www.arduino.cc/en/software/)

2. Choose **Windows 10 and newer**.
   (imgs/arsite.png)

> ⚠️ Do not download anything under *Nightly Builds*. These versions are unstable and may contain bugs.

---

## Boards Manager Setup

1. Open the Arduino IDE.
2. Go to **File** > **Preferences** > **Additional Board URLs**.
4. Click the green icon next to the input field.
5. Add this URL, then click **OK**:  
   [https://dl.espressif.com/dl/package_esp32_index.json](https://dl.espressif.com/dl/package_esp32_index.json)
   (imgs/prefer.png)
   
7. Go to the **Boards Manager** (click the board icon on the left sidebar).
8. Search for **ESP32 by Espressif Systems** and install it.
   (imgs/board.png)

---

## Setting Up the ESP32 Board

1. Go to **Tools** > **Board** > **ESP32** > **ESP32 Dev Module**.
   (imgs/boardsel.png)
3. Go to **Tools** > **Port** and select the COM port number shown in *Device Manager*.
   (imgs/portsel.png)

