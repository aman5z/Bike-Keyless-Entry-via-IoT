# Bike-Keyless-Entry-via-IoT

https://aman5z.blogspot.com/2024/09/projects.html

This project uses a 4-channel relay and a NodeMCU ESP8266, connected via Sinric Pro (which allows for up to 3 devices for free). Power is supplied by a 12V to USB charger connected to the bike's battery (or a power bank can be used). The system is connected to the bike's ignition, kill switch (to turn the engine on/off without turning off the ignition), and self-start switch.
For added fun, I also connected the high beam light switch and horn switch (as a car unlock method), but these are limited due to Sinric Pro’s 3-device limitation. The bike can be controlled via Alexa and Google Assistant. I’ve DIYed a Bluetooth receiver into my helmet, allowing me to turn on the bike while wearing it, giving me a Tony Stark/Iron Man-like experience!

Additionally, I installed an RF module salvaged from an old RC car, which I transformed into a remote keychain. This makes the bike fully keyless—automatically unlocking when I’m near and locking when I move more than 10 meters away. Since I’m usually out and about, I activate my phone’s mobile hotspot (with the same SSID as my home network) to make the system work, although Bluetooth is another option with more limited range.

I can also control the system via the Alexa app on my WearOS watch for a futuristic touch!
