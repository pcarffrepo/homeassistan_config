# My Home Assistant Configurations

This repository has the main goal of reporting and serve as a guide to my own main configuration of Home Assistant.
Since I'm a absolute beguinner I found that the internet and particulary the GitHub community has an absloute abundance of information to how get the most of your connected divices, but the information is scatered all around the place and it's not easy to get all thing working as i needed and intended.

And most of all, I saw the same questions I had with no response to find in another source my answer, so I wil try to document my process the best I can no just by posting my files but also sharing my process to get there, and hopefully get some feedback and also improving my own server.

# History

My first contact with the "smart home" concept was with the necessity of control the acess of my home so I bought an Aqara Zigbee Hub and a Zigbee Magnetic Sensor. Anf after a month I ended up and bought a Xiaomi camrea since the all could funtion in the same ecosystem.

Time has passed and I started to experiment with some real solutions to some self hosted home automation like Domoticz, OpenHAB and Home Assistant but at the time I ended up feeling that the process was to much envolved for my needs and actually having a server 24h was not in my plans.

In the start of this year two things happend of my 3 Xiaomi cameras, ony 2 now work... Not because the hardware has any problem but because Xiaomi simpli stopped allowing it to function outside of China, also made me realize that all my data is being sent to some random server to China (or some where else)

### Version 1 (10/2022)

So I gave Home assistant again a new shot... But I was not ready to fully commit!

I went to [Home Assistant Website](https://www.home-assistant.io/) and started to studie my choices. My home computers run on Windows (different versions of it) but I have some basic knowledge of sone linux code from University so I thought it shoudn't be so hard (I was wrong) but actually setting up the server is not that difficut.

My chosen metod of instalation was Home Assistant Operating System running on Oracle VM Virtual Box in my 2 years old laptop (probaly not the best choice but it was the machine the was easier to work with at the moment)

I downloaded the windows hosts from the [Oracle Virtual Box](https://www.virtualbox.org/wiki/Downloads) and complete de installation and the downloaded the vdi image on the [windows download section of Home Assistant](https://www.home-assistant.io/installation/windows).

To prevent some problems (I ran out of storage in my VM, thaks to [Kiril Peyanski's Blog](https://peyanski.com/) for the solution) a few steps shoud be considered!

![Passo 1](https://user-images.githubusercontent.com/118359759/202221853-08e5aec3-1553-45ce-941d-95fca2b1a8a9.jpg) ![Passo 2](https://user-images.githubusercontent.com/118359759/202224015-87b2b6de-a9ad-4188-b822-c4c8fcee727b.jpg)



