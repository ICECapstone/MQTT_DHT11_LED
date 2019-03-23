# MQTT_DHT11_LED

In this lecture, you will learn to publish DHT11 readings from NodeMCU using MQTT, and control LED by listening to a published message.

<H2>Step1: Connect NodeMCU, DHT11 and LED </H2>
DHT11 - GPIO5
LED - GPIO4
![IMG-8462](https://user-images.githubusercontent.com/11530521/54859738-8e79b800-4d43-11e9-8e4f-55dd2902818b.jpg)

<H2>Step2: Upload the code to your NodeMCU </H2>
Please change your SSID, password, pubTopic and subTopic as follows:
* pubTopicT = "GROUPNAME/temperature"
* pubTopicH ="GROUPNAME/humidity"
* subTopicLED = "GROUPNAME/LED"

Please use the following group names
 * vCANTEEN
 * LOCKER
 * PARKING
 * CUMAP
 * HYPERBORA
 * MONKOL
 
 <H2>Step3: Connect your MQTT broker and subscribe to the messages</H3>
 * Please subscribe to your published temperature/humidity topics. You should see the message appearing on the MQTT broker
 * Please publish a control message from your MQTT broker to your LED. Your LED should be turned ON/OFF accordingly.
