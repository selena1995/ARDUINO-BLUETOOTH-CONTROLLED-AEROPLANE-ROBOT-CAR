# ARDUINO-BLUETOOTH-CONTROLLED-AEROPLANE-ROBOT-CAR
Here in this instructable, l am going to make a simple Arduino Bluetooth-controlled robot car. Though I have made several Arduino robot cars this time I have made a little few changes to this robot model. I have added two wings which are like an Aeroplane. This is a concept for future cars. Hope this instructable will help you as previously.
![m main](https://user-images.githubusercontent.com/79990158/185332010-9edaea85-c1a8-4d75-879d-58c88353183d.jpg)

## Supplies
To make this, the following Components will be needed

- Arduino Nano![Screenshot (7)](https://user-images.githubusercontent.com/79990158/185365650-942343a8-f872-47df-afe1-f3e6d558837b.png)
- L293D Motor Driver![Screenshot (3)](https://user-images.githubusercontent.com/79990158/185365796-27c017ad-5200-4d06-bd75-00c2fb7f347a.png)
- capacitors![Screenshot (6)](https://user-images.githubusercontent.com/79990158/185365984-9fe6f781-dc4a-4178-ba9b-4da3c0cb5894.png)
- resistors
- diode![Screenshot (4)](https://user-images.githubusercontent.com/79990158/185366433-e213855b-b7b2-41bd-b452-8a4ce34fd5e9.png)
- Voltage Regulator![Screenshot (5)](https://user-images.githubusercontent.com/79990158/185366598-eace29ae-72bd-4193-bf66-c30c976c3271.png)
- Male Header Pin![Screenshot (2)](https://user-images.githubusercontent.com/79990158/185366679-5c76699e-c7cf-48d4-9beb-2ab012d7c75f.png)
- LED![Screenshot (1)](https://user-images.githubusercontent.com/79990158/185366744-8147ae2e-0960-4b32-b3f8-de8a5d36f295.png)
- Terminal Block![Screenshot (8)](https://user-images.githubusercontent.com/79990158/185366882-bffc3255-1948-45e1-b0cc-649bc96502f9.png)
- DC Motor
- Micro Coreless Motors![Screenshot (20)](https://user-images.githubusercontent.com/79990158/185367051-c2b1a731-ea68-498f-aa18-0beed582cb33.png)
- Propellers
- PCB Board![Screenshot (14)](https://user-images.githubusercontent.com/79990158/185367145-fc31497f-f98d-4226-9409-7f66b10542de.png)

## WHY DO WE NEED a FLYING CAR?
Flying cars could help reduce congestion on the roads and emissions from ground transport, and lower the risk of road accidents. A more immediate use for flying cars could be in improving emergency services such as ambulances, fire engines, and so forth.
##  PCB MAKING
I almost always prefer to make PCB while making a robot.

Obviously, there have some reasons to invest in Customised PCB Boards. A printed circuit board can contain a number of parts and elements. Because they utilize copper tracks rather than actual wires, it allows for the same types of results without using current-carrying wires. The boards are smaller and they are not as bulky.

Almost every time I prefer to make prom [JLCPCB](https://jlcpcb.com/IYB) for their quality of products and services & also for the low cost. I also get coupons for every purchase like $2 for 5pcs PCBs, PCBA from $0, Register to Get Free Coupons here: https://jlcpcb.com/IYB. I really liked the PCB Boards as they are very high in quality.

To make PCB Boards, you will need a Gerber file which I have already attached with this instructable. Simply download The zip file and upload it to [there]( https://jlcpcb.com/IYB) website and place the order successfully.

Once you get the PCB, assemble every component on the PCB board and make it ready.

then you have to attach the motors with the dedicated port for motors on your PCB board and then the electronics part will be ready.

Though I have bought a toy car from the market to mechanical part in this project is very less. but if you want to change the design according to your choice then it will also be very appreciable.

The last part is Uploading Arduino code to the robot and controlling it from your smartphone. Now we will discuss on this topic

![Screenshot (18)](https://user-images.githubusercontent.com/79990158/185369261-e14182f7-6b8e-44ec-a49b-9cf594cdfdb1.png)
![Screenshot (13)](https://user-images.githubusercontent.com/79990158/185369370-3328c075-2c2f-411c-8814-c7aa2d8af992.png)
![Screenshot (14)](https://user-images.githubusercontent.com/79990158/185369402-b02f8421-9573-4dd0-930a-80641433c1ef.png)
![Screenshot (16)](https://user-images.githubusercontent.com/79990158/185369436-49cba76a-2a72-41bd-96fb-3f7870f4a7aa.png)
![Screenshot (10)](https://user-images.githubusercontent.com/79990158/185369484-bf926822-a987-479e-a876-e292e43e91ea.png)
![Screenshot (12)](https://user-images.githubusercontent.com/79990158/185369535-d02a07c0-af91-49b5-b687-d541d81f0d57.png)
![Schematic_l298n nano hc05 bot_2022-08-18](https://user-images.githubusercontent.com/79990158/185369586-a7ae67df-f847-4f9e-9da9-3122974d664a.png)
[BackupProjects_mideas.monalisa_personal_0_20220818.zip](https://github.com/selena1995/ARDUINO-BLUETOOTH-CONTROLLED-AEROPLANE-ROBOT-CAR/files/9372526/BackupProjects_mideas.monalisa_personal_0_20220818.zip)

## Assemble Mechanical Parts Together
This is a very simple step for this robot. You can watch this video to get a clear idea of every step to making this robot

![Screenshot (19)](https://user-images.githubusercontent.com/79990158/185370483-eb0b23c8-1f4f-4403-baee-48ba65b16453.png)
![Screenshot (21)](https://user-images.githubusercontent.com/79990158/185370547-cc0af98f-12e0-42b3-8216-a2a160e16f47.png)
![Screenshot (22)](https://user-images.githubusercontent.com/79990158/185370636-63022f2d-e0df-4fe4-844d-b383d96b7658.png)
![Screenshot (23)](https://user-images.githubusercontent.com/79990158/185370657-e5422159-cbf9-4078-b513-062345fd5c53.png)
![Screenshot (24)](https://user-images.githubusercontent.com/79990158/185370676-4d8cea71-e0a6-4c52-99a2-67741f436b13.png)
![Screenshot (25)](https://user-images.githubusercontent.com/79990158/185370701-8a01d26b-5d4b-4081-8946-fc6a1173ede1.png)
![Screenshot (27)](https://user-images.githubusercontent.com/79990158/185370741-5ace333d-0a02-44d1-b658-9a862478bc76.png)
![Screenshot (28)](https://user-images.githubusercontent.com/79990158/185370770-4a75b5ac-e205-4bd3-9154-c1667ea7513e.png)
![Screenshot (29)](https://user-images.githubusercontent.com/79990158/185370810-04f43fa0-cab6-4433-8cd5-e33a21acd459.png)

## Arduino Codeing & Communicating by Android Mobile

[ARDUINO BLUETOOTH CAR 4 DC MOTOR.txt](https://github.com/selena1995/ARDUINO-BLUETOOTH-CONTROLLED-AEROPLANE-ROBOT-CAR/files/9372690/ARDUINO.BLUETOOTH.CAR.4.DC.MOTOR.txt)
![Screenshot (31)](https://user-images.githubusercontent.com/79990158/185375072-8d96481a-53ac-4e08-a72a-81ba809b6a13.png)
![Screenshot (26)](https://user-images.githubusercontent.com/79990158/185375111-22742579-8afe-474d-a76a-634170a8789c.png)

## YOUTUBE VIDEO LINK
https://www.youtube.com/watch?v=uu7UQjebLqM
