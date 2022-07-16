# week2Tasks_IoT
In this repository, I will share HTML, JS, and CSS code for Recognition Speech to Text in Arabic. Also, there will be explained of how we turn on the "wisdom ESP32"
# week-2Task1 IoT
In this repository, there is an explain of how we turn on the "wasdom ESP32"" 
## **1) Prerequisites: Arduino IDE Installed**
Before starting this installation procedure, make sure you have the latest version of the Arduino IDE installed in your computer.
## **2)Installing ESP32 Add-on in Arduino IDE**
To install the ESP32 board in your Arduino IDE, follow these next instructions:
### **1.2)In your Arduino IDE, go to File> Preferences**
![image](https://user-images.githubusercontent.com/107868626/179354729-f3a3e50c-5047-415c-bdcc-cba9eadc05c6.png)
### **2.2)Enter the following into the “Additional Board Manager URLs” field:**
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
Then, click the “OK” button:
![image](https://user-images.githubusercontent.com/107868626/179354780-a96a287c-443a-4496-a15e-c4f4a55aee72.png)
### **3.2)Open the Boards Manager. Go to Tools > Board > Boards Manager**
![image](https://user-images.githubusercontent.com/107868626/179354792-65bd5f6b-edf4-4e91-8d56-946300077f05.png)
### **4.2)In your Arduino IDE, go to File> Preferences**
Search for ESP32 and press install button for the “ESP32 by Espressif Systems“:
![image](https://user-images.githubusercontent.com/107868626/179354813-89391196-5252-4243-8604-63171a10a287.png)
### **5.2)That’s it. It should be installed after a few seconds.**
![image](https://user-images.githubusercontent.com/107868626/179354823-05e5a181-e342-4a29-81c6-e7b6d56b58de.png)
## **Testing the Installation**
Plug the ESP32 board to your computer. With your Arduino IDE open, follow these steps:
## **1. Select your Board in Tools > Board menu (in my case it’s the DOIT ESP32 DEVKIT V1)**
![image](https://user-images.githubusercontent.com/107868626/179354866-4ca0775d-8cb4-44b3-88dc-81a9b1eb16c7.png)
## **2. Select the Port (if you don’t see the COM Port in your Arduino IDE, you need to install the CP210x USB to UART Bridge VCP Drivers):**
![image](https://user-images.githubusercontent.com/107868626/179354875-f23be7e6-ce80-462f-a5bc-910bb9849c85.png)
## **3. Open the following example under File > Examples > WiFi (ESP32) > WiFiScan**
![image](https://user-images.githubusercontent.com/107868626/179354886-91fcf4e8-dfd4-4159-80e2-aca21490a157.png)
## **4. A new sketch opens in your Arduino IDE:**
![image](https://user-images.githubusercontent.com/107868626/179354891-71d4c1b6-51e6-4377-8e2a-eed981ee5648.png)
## **5. Press the Upload button in the Arduino IDE. Wait a few seconds while the code compiles and uploads to your board.**
![image](https://user-images.githubusercontent.com/107868626/179354899-0f16e0f0-6bc0-4101-9b4c-b4b6e831f115.png)
## **6. If everything went as expected, you should see a “Done uploading.” message.**
![image](https://user-images.githubusercontent.com/107868626/179354918-a9d9822d-caba-488b-abde-946aff8d7909.png)
## **7. Press the ESP32 on-board Enable button and you should see the networks available near your ESP32:**
![image](https://user-images.githubusercontent.com/107868626/179354936-373e82cd-ee24-4882-8270-a12ce1edbab1.png)
