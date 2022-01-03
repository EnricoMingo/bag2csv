bag2csv
=======
Porting to Python 3 of the ```bag2csv``` script to convert bag files into csv files, from Nick Speal.

Usage:
------
```python bag2csv rosbag1.bag rosbag2.bag ...``` 

Known issues:
-------------
Some topics are not correcty saved in the scv file, for example the filed ```names``` in the ```/joint_states``` topic, resulting in an empty column.

