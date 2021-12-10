### FRA502-Service-Robot
Keedita Chaihetphon ID : 62340500003

# How to run this project?
1. roscore
2. roslaunch project project.launch
3. roslaunch project navigation.launch
4. roslaunch project goal.launch

![image](https://user-images.githubusercontent.com/78614938/145610787-56b789b5-912e-4493-a74c-4b61cf5d103e.png)

# How to command this robot?
Command example : ไปที่ ...
เช่น ไปที่ห้องครัว ไปที่ห้องน้ำ เป็นต้น

# Summary the project and explain about problems or challenges 
  การทำโปรเจกต์ครั้งนี้ ทำให้ได้เข้าใจถึงกระบวนการทำงานของ ROS มากยิ่งขึ้น 
  
  พบปัญหาค่อนข้างเยอะระหว่างการทำงาน
  1. แบ่ง RAM ให้ Ubuntu น้อยเกินไป ทำให้เวลาทำงานค่อนข้างจะนาน และบางครั้งโปรแกรมก็ดับไปเอง
  2. มีปัญหาตอนการสร้าง World หลายครั้งที่สร้าง World อยู่แล้ว Gazebo ก็ดับไปเอง
  3. มีความยากลำบากในการทำ gmapping เนื่องจากเส้นทางมีขนาดเล็กเกินไป ทำให้หุ่นไม่สามารถเดินเข้าไปทำแผนที่ได้ และควบคุมหุ่นยนต์ด้วย teleop ค่อนข้างลำบาก
  4. มีปัญหาระหว่างการทำ Speech Recognition เนื่องจากเสียงไมค์เบาไป
  5. ในบางครั้ง ในการรัน roslaunch project goal.launch บางครั้งก็ขึ้นให้ทดสอบไมค์เร็ว บางครั้งก็ขึ้นในทดสอบไมค์ช้ามาก และในบางครั้งก็ไม่ขึ้นเลย ซึ่งยังหาสาเหตุไม่ได้
  
