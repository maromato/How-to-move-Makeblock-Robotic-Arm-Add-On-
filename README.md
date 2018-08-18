# Robotic-Arm-Add-On-Pack-For-Starter-Robot-Kit
This is a revised code probided by mBlock (https://github.com/Makeblock-official/Robotic-Arm-Add-On-Pack-For-Starter-Robot-Kit)
Demo.ino is the revised code for the mBlock Robotic-Arm-Add-On-Pack-For-Starter-Robot-Kit.
Some Important tips as follws.
1. We need to download several libraries for this code: MeOrion.h, SoftwareSerial.h
2. MeOrion.h is included mBlock libraries deposited in the official Github (https://github.com/Makeblock-official/Makeblock-Libraries)
3. SoftwareSerial.h can be downloaded by elsewhere(https://www.robot-r-us.com/e/995-softwareserial.html)
4. There libraries can be installed by Ardiuno software.(Scatch/Inclued libraries/).
5. The board "Ardiuno/Genuino Uno"should be selected, otherwise the compile will not be finished sucessfully and give error as below:
    avrdude: error: programmer did not respond to command: exit bootloader
6. The IR receiver module connect on port 3! Port 5 is not working by some reason.
You could control the robot arm and the tank by this code as shown in the twitter as follows:
https://twitter.com/tokitky/status/1021260418453573633
https://twitter.com/tokitky/status/1022338370729590784
