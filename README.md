# ENGO 651 lab5


In this task, we connect to a MQTT broker over WebSockets using the Paho JavaScript client, and then utilize the MQTT protocol to send and receive location updates and any other messages that the user chooses.


Initially, the user is asked to provide their name, course, MQTT broker address, and port. The default topic used for location sharing is defined by the course and name, both of which are arbitrary. We advise using test.mosquitto.org and port 8081 as the host and port. A map and a number of input forms show up on the website after the connection is made. 

Users can enter a subject and a message in the "Publish" section, then click the "Publish" button to have their message published to the designated topic on the linked MQTT broker. When a user clicks "Subscribe" after inputting a topic in the "Subscribe & Unsubscribe" section, the app subscribes to that topic, and messages posted to it show up in the section below. Likewise, users can click "Unsubscribe" after entering a topic and choosing to unsubscribe from it.


