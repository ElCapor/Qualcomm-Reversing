# Qualcomm-Reversing
Reverse of the qsc 6270 / qsc 6240 firmware, with the end goal of writing an os.

WARNING : This is the first time I do this kind of stuff with mobile phones. I'm doing it for learning and educational purposes only.

I currently own a samsung GT-B2710 , which is what i base myself on to reverse. I'll leave a link for the firmware files so that everyone interested can take a look at it [here from the dumbphone repo](https://mega.nz/folder/2aoVnJJJ#ovZJG4cbvIOqLVEJBHrQSQ/folder/DaIwDLKT)
(You can take any one of the 4 firmwares)

I'm currently reversing the cpu firmware based on this repository : https://github.com/chinahby/1110

Ill try to have this repositry as much as organized as possible. For now it will only hold writings of what i found.

For now I didn't attempt anything hardware-side on the phone , but i found out that it has a jtag port (i think they call it test points ?) , i will attempt connecting to it with an arduino bridge in 2 weeks.

The phone also has a Test mode that allows to go into EDL mode and do some stuff which seems interesting.

For now ill try to gather as much informations on the system as i can.