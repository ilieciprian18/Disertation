# Disertatie-Lucrare-Finala

My dissertation project is an IoT application, an intelligent assistant (powered by ChatGPT) with both hardware and software components, designed to help a user take care of a plant to a greater or lesser extent.  
The system integrates several modern technologies – sensors connected to a Raspberry Pi board from which data is retrieved using a Python script. This data is stored in a Firebase instance and a user application developed with Java in Android Studio, which is integrated with ChatGPT.  
Here it is a short summary.

![image](https://github.com/user-attachments/assets/a11d952e-693a-4474-b313-3c7b565cc92d)


## Hardware Part

The Raspberry Pi circuit has the following modules conected to it: AM2320( sensor for temperature and humidity), BMP280 ( sensor for temperature and atmospheric preassure), BH1750FVI ( sensor for light intensity), resistive soil moisture sensor, resistive rain sensor, water pump, 3VDC Relay, aditional power source, LED, comparator module LM393, BreadBoard, cables.

![image](https://github.com/user-attachments/assets/497aff9b-68d2-4987-8cf1-944514d652a1)


## Software Part

### Python Script

Flow of the Python Script

![image](https://github.com/user-attachments/assets/206e6610-f36b-4bfb-92ec-35a1d427366c)



### Database Structure

The application uses a Firebase real-time database, which is a NoSQL database type. It has two tables stored in JSON format. Another feature is authentication based on unique tokens implemented through Firebase.

### Android Application
