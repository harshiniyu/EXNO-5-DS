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
## Name:Harshini 
## reg no:212223240050
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
```
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
```
```
 plt.plot(x,y,label='line1')
```
![image](https://github.com/user-attachments/assets/af8d8045-f81b-4a67-89f7-ff19d1f2ce66)
```
 x1 = [1,2,3]
 y1 = [2,4,1]
 x2 = [1,2,3]
 y2 = [4,1,3]
 plt.plot(x1,y1,label='line1')
 plt.plot(x2,y2,label='line2')
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('Two lines on same graph!')
 plt.legend()
 plt.show()
```
![image](https://github.com/user-attachments/assets/42719dd1-30f7-4b61-bff8-f44eabd6b63b)
```
 import matplotlib.pyplot as plt
 x=[1,2,3,4,5,6]
 y=[2,4,1,5,2,6]
 plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('Some cool customizations!')
 plt.show()
```
![image](https://github.com/user-attachments/assets/cf93b2c2-f8b5-410e-8926-255d47035c0d)
```
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/900c3fe4-3c85-4b7a-aefd-5b36767b2633)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/efbb3b6b-325a-47fa-9a06-a2918a3afcc2)
```
 years=range(2000,2012)
 apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
 oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
 plt.plot(years, apples)
 plt.plot(years, oranges)
 plt.xlabel('Year')
 plt.ylabel('Yield (tons per hectare)')
 plt.title('Crop Yields in Kanto')
 plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/7b348321-aa8d-411d-a522-7b73489860fe)
```
 plt.figure(figsize=(12,6))
 plt.plot(years,oranges,marker='o')
 plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/24660f70-4b4c-473f-9e03-d89bdd671772)
```
 import matplotlib.pyplot as plt
 import numpy as np
 import pandas as pd
 x=np.arange(0,10)
 y=np.arange(11,21)
 x
```
![image](https://github.com/user-attachments/assets/a80287f6-175e-4146-a4d2-4f05026305da)
```
y
```
![image](https://github.com/user-attachments/assets/35917a0b-8a82-41f2-a243-6ce3fd2c74ec)
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/3ce2ce5d-4a8e-4fa1-8f91-a064a0e0e7fd)
```
 y=x*x
 y
```
![image](https://github.com/user-attachments/assets/916b5761-604a-4529-89f2-cd0a4c07315c)
```
 plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
 plt.xlabel('X axis')
 plt.ylabel('Y axis')
 plt.title('2d Diagram')
 plt.legend(['y-values']);
```
![image](https://github.com/user-attachments/assets/934098ae-d645-45f3-8c74-313ece881b61)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/4e831b37-8b56-422c-9b57-e433aaa65e0b)
```
 import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
```
![image](https://github.com/user-attachments/assets/c4506fff-9192-45c0-b3da-37a6a126f25c)
```
 import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
 plt.plot(x,y1,color='red')
 plt.plot(x,y2,color='black')
 plt.legend(['y1','y2'])
 plt.show()
```
![image](https://github.com/user-attachments/assets/298f9992-b449-48ec-97c8-4c3e677d4744)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/5103774b-f5a1-4f05-b30f-f717d1db9855)
```
 x=[2,8,10]
 y=[11,16,9]
 x2=[3,9,11]
 y2=[6,15,7]
 plt.bar(x,y,color='r')
 plt.bar(x2,y2,color='g')
 plt.title('Bar graph')
 plt.ylabel('Y axis')
 plt.xlabel('X axis')
 plt.show()
```
![image](https://github.com/user-attachments/assets/896396b7-92a3-4e03-8eda-9930fa932f91)
```
 import matplotlib.pyplot as plt
 ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
 range=(0,100)
 bins=10
 plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
 plt.xlabel('age')
 plt.ylabel('No. of people')
 plt.title('My histogram')
 plt.show()
```
![image](https://github.com/user-attachments/assets/e3f0b48f-96d0-4e3f-bdf8-11176306e555)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/a4ab5f4b-17cb-4222-a079-1f9bd67c4380)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/67ca78ac-9670-4da5-8d66-9a68ac8e943d)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/876f78a8-e2bf-4348-9fbb-0685b62fc5f8)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/user-attachments/assets/7c3a86e7-6ccd-4d78-8c03-1a0e2906f8cd)

# Result:
To Perform Data Visualization using matplot python library for the given datas is successful.
