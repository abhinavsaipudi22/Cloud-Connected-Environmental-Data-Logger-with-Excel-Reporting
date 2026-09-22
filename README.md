# Cloud-Connected-Environmental-Data-Logger-with-Excel-Reporting
# Overview
This project is an IoT-based Environmental Data Logger developed using the LPC2148 ARM7 Microcontroller. It continuously monitors environmental parameters such as temperature and gas leakage, displays the readings on an LCD, stores configuration data in EEPROM, and uploads sensor data to the ThingSpeak Cloud through the ESP-01 Wi-Fi module. The collected data can be viewed online and exported to Microsoft Excel for analysis and reporting.
# Features
Real-time temperature monitoring using LM35 sensor.\
Gas leakage detection using MQ-2 sensor.\
16x2 LCD display for live sensor readings and system status.\
ESP-01 Wi-Fi module for cloud connectivity.\
Uploads sensor data to ThingSpeak.\
Buzzer/LED alert when gas is detected or temperature exceeds the set limit.\
EEPROM (AT24C256) stores the temperature set point.\
Cloud data can be exported to Excel for reports and analysis.\
# 📊 Project Block Diagram

<img width="1043" height="697" alt="image" src="https://github.com/user-attachments/assets/9497861e-855e-495f-bcc2-1dfbd1059368" />
