# litterdrone
Design for a drone based on Ardupilot which can pickup and deposit litter in an electric pickup van.
This project aims to built a autonavigating drone which is able to recognise litter in road berths, approach it, pick it up and subsequently fly back to a slow driving pickup van in which it can deposit the catched litter.
Since the drone has to be navigated autonomously without any human intervention, there are no ready-to-use drones commercially available which can easily be modified to accomplish this task.
Hence we have to rely on DIY-kits to build a suitable drone, equipped with an open source flight controller.
The minimal needed necessary components to build such a drone are:
1. 4 electromotors (best suited is the T-motor F40 from Tiger)
2. 4 electronic speed controllers (ESCs), also from Tiger
3. 4 propellers
4. 4 propeller protectors
5. a 6 inch quadcopter frame
6. 2 landing struts
7. a 14,8V LiPo-accu with capacity of 5400mAh, giving approximately 25' flying time
8. an accu charger with inductive coupling between the van and the drone to be charged
9. last but not least, the open source Pixhawk controller, on which the Ardupilot SW is ruuning.

The Pixhawk controller has a lot of interfaces, which are essential for autonomous navigation, like a GPS-module, an accelerometer, a gyroscope, ultrasonic sensors and of course a hires camera. Moreover, a servo-controlled robotic stick is also necessary, which is connected to an elastomer slurf. This slurf is open-ended at one side and connected to a small air compressor at the other side, so that the slurf can snap tightly to the litter in order to pick it up and carry it until the collection hub of the van is reached.
The aim of this project is to modify and enhance the Ardupilot SW with the abovementioned features and to make a little step towards a more litterfree world.
