# Network adapter information

### You will need to create 3 network adapters

#### The next few step need to be redo but each time with the different IP one for the LAN, DMZ, and WAN. 

### First step
- Go to File then Preferences in windows 
- On macbook book go to VirtualBox on top right corner like the picture and click on Preferences

![NAI](https://i.imgur.com/tM1dVVB.png)

### Second Step
- Go to Network on the Preference windows

![NAI](https://i.imgur.com/y4Wkuub.png)

- Then go to Host-only Networks and Adds 3 new Networks

![NAI](https://i.imgur.com/P7k0FNz.png)

![NAI](https://i.imgur.com/Azw5QWp.png)

- Then on those 3 go to Edits selected to change setting.

![NAI](https://i.imgur.com/IZnwt0d.png)

- On the Adapter seting use the IP address bellow for each adapter. 

## LAN
- Network cards (2 on Windows, 0 on Macbook) is LAN 0
- 172.20.240.1
- 255.255.255.0

## DMZ
- Network cards (3 on Windows, 1 on Macbook) is DMZ 1
- 172.20.241.1
- 255.255.255.0

## WAN
-Network cards (4 on Windows, 2 on Macbook) is WAN 2
- 172.31.1.1
- 255.255.255.248

![NAI](https://i.imgur.com/qzgNuUK.png)

- Make sure that you disable DHCP Server because is always enable by default to make it work disable it like the picture bellow. 

![NAI](https://i.imgur.com/4qZfgaq.png)
