# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
```

<img width="751" height="572" alt="image" src="https://github.com/user-attachments/assets/a5c233bc-4632-450e-833c-306befa12aff" />

```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="715" height="542" alt="image" src="https://github.com/user-attachments/assets/e4ae05e5-6c29-4c03-96eb-4d5ed0a198e8" />

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
```
<img width="742" height="542" alt="image" src="https://github.com/user-attachments/assets/064ae2fa-bdcd-4ffc-b2e4-6207a9c1cc61" />

```
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
<img width="740" height="571" alt="image" src="https://github.com/user-attachments/assets/9d877ed6-51c8-4ea3-b2ae-4daa761e721d" />

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="628" height="544" alt="image" src="https://github.com/user-attachments/assets/5b2bc2fd-ffc7-4702-855c-79373187bce4" />

```

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="613" height="520" alt="image" src="https://github.com/user-attachments/assets/1da6737a-8ea7-4e57-9ee6-1f1ae89fa0a8" />

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
<img width="714" height="526" alt="image" src="https://github.com/user-attachments/assets/224592d3-4d09-424b-bc00-7ed2076fab2b" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
<img width="737" height="579" alt="image" src="https://github.com/user-attachments/assets/7c93d2d6-483d-4a20-afc9-d3ec478fde03" />

```

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
<img width="673" height="526" alt="image" src="https://github.com/user-attachments/assets/ead358bf-e02e-4434-abec-3a4444131b71" />

```

np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```
<img width="743" height="458" alt="image" src="https://github.com/user-attachments/assets/ef608e31-5d45-4033-b2aa-662810edd1da" />

```

fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')

```
<img width="729" height="595" alt="image" src="https://github.com/user-attachments/assets/734f4a1d-b145-4732-82f1-e574afe8bc12" />











# Result:
Thus, all the data visualization techniques of matplotlib has been implemented

