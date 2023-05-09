# Time Sync ROS Node

Simple node that listens to a stamped ROS topic and then syncs system time. You will need password-less sudo or sudo exception for the `date` command.

# Usage
```
rosrun time_sync time_sync.py [STAMPED_TOPIC]
```
