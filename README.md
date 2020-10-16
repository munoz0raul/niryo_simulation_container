# Niryo One ROS Docker Simulation

Niryo One ROS stack is download from https://github.com/NiryoRobotics/niryo_one_ros

It is licensed under GPLv3 (see [LICENSE file](https://github.com/NiryoRobotics/niryo_one_ros/blob/master/LICENSE))

## How to use Niryo Container?

```
git clone https://github.com/munoz0raul/niryo_simulation_container.git
cd niryo_simulation_container
docker build --tag niryo_simulation_container:1.0 .
docker-compose up
```

After the container startup, connect your Niryo Studio to your local IP: 127.0.0.1  port: 9090

