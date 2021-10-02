# Meters' readings recognition

Simple program for recognizing the readings of water and electricity meters.

Algorithm:
1. Finding the dial using the canny filter

![alt text](https://github.com/niobeus/meters_reading/blob/main/imgs/1.png?raw=true)
![alt text](https://github.com/niobeus/meters_reading/blob/main/imgs/2.png?raw=true)

2. Four-point-transform for dial extraction

![alt text](https://github.com/niobeus/meters_reading/blob/main/imgs/3.png?raw=true)

3. Image normalization (gamma correction, gray world algorithm etc.)

![alt text](https://github.com/niobeus/meters_reading/blob/main/imgs/5.png?raw=true)

4. Finding contours of numbers on dial

![alt text](https://github.com/niobeus/meters_reading/blob/main/imgs/6.png?raw=true)

5. Contours recognition using neural network
