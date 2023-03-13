# Condition Based Maintenance Fault Database for Testing of Diagnostic and Prognostics Algorithms
Data assembled and prepared on behalf of [South Ural State University](https://www.susu.ru/en).

## Bearing Fault Dataset
A bearing fault dataset has been provided to facilitate research into bearing analysis. The dataset comprises data from a bearing test rig. The distinguishing feature of a data set is the way it is collected. A wireless sensor that measures linear and angular acceleration is mounted directly on a rotating shaft. The dataset is introduced and first analyzed in the [paper](https://www.sciencedirect.com/science/article/pii/S0888327022005714?via%3Dihub).

The linear and angular signals of all five bearings were collected with a sampling frequency of 31.175 kHz with the system operating at 1200 rpm (i.e. at 20 Hz).

The data set comprises the following
- normal condition
- fault in inner race
- fault in outer race
- fault in ball
- combination fault


![](https://github.com/ellkrauze/fault-data-sets/blob/main/bearing_picture.jpg?raw=true)

*Test bearings with inner race fault (left) and ball fault (right)*


**Note:** The data is stored in a [Matlab](https://www.mathworks.com/products/matlab.html) double-precision, binary format *.mat file. The data structure holds vectors of linear and angular acceleration data.
