# HW1 of Machine Learning - PM2.5 Prediction
* It is a regression problem
* 18 air features in 9 hours to predict PM2.5 in the next hour 
* dim(x) = 18*9 dim(y)=1 y is one of 18 feature  
* Ranked 18 place in class

There are two version of this homework:

hw1.py equals to hw1_best.py

They can directly use the trained model in w_mt_vt.npy 

To use those script, you need to insert two address:
```
./xxx.sh <testfile address> <output file address>
```
For example:
```
./hw1_best.sh test.csv ans_best.csv
 ```
If you meet the permission problem, you can use this command:
```
chmod 777 xxx.sh
```
or use following to run the script.
```
bash xxx.sh
```
