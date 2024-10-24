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
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/00e58d39-d5e9-438d-b4aa-a1e2e25e9daf)

```
import matplotlib.pyplot as plt
x_values=[1,2,3]
y_values=[2,4,1]
plt.plot(x_values,y_values)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
![image](https://github.com/user-attachments/assets/27662a6c-87e6-4347-b1d3-05f288a7f203)

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')

x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/fdf5d4c7-4f8f-4224-84dc-462b161e4168)

```
import matplotlib.pyplot as plt
x_values=[1,2,3,4,5,6]
y_values=[2,4,1,5,2,6]
plt.plot(x_values,y_values,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlim(1,8)
plt.ylim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![image](https://github.com/user-attachments/assets/8a457cdc-ddd2-4b39-923e-719134212c43)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/912f6632-e6bd-44ba-bad0-5fea663bd20f)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
years=[2010,2011,2012,2013,2014,2015]
plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/ec4e830f-c073-45d7-b1d0-79d22c3ccb77)

```
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
```
![image](https://github.com/user-attachments/assets/a2c4c676-8b35-4231-a0cb-5af283f32cfd)

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yield in Kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/6788b1e3-0377-46d3-98f8-0c7b0fae2dc5)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
years=[2010,2011,2012,2013,2014,2015]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
```
![image](https://github.com/user-attachments/assets/7566b91a-0037-4ea1-8140-e0fa3003fbcf)

```
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons of hectares)")
```
![image](https://github.com/user-attachments/assets/2e3e44dc-6feb-4c76-b2ea-d659d9553fa1)
```

plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yield in Kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/14998b33-20b3-4142-b81d-7593fe922503)
```

import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color='blue')
plt.show()
```
![image](https://github.com/user-attachments/assets/4129a713-222b-4bb1-804e-4343daa3cedc)

```
import matplotlib.pyplot as plt
x1=[1,2,3,4,5,6,7,8,9,10]
y1=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x1,y1,label='stars',color='green',marker='*',s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/c5807941-d35d-42a7-b5e1-af69fe027f68)
```

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/c34ba4b0-267b-4bc1-895b-c10fe271d578)

```
y
```
![image](https://github.com/user-attachments/assets/95e2f5f7-7125-4fd2-8ded-55dcea942673)
```

plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graphs in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/9ff66837-2f4d-4f96-8e45-ebaab5213302)

```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/090b9831-6385-4d0e-b9a8-149807ddc2ed)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d diagram')
```
![image](https://github.com/user-attachments/assets/e9c12efc-f038-4e53-a155-3b7fc51a4764)

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![image](https://github.com/user-attachments/assets/806d0ac3-9926-4f8c-b482-f0e97558783d)

```
np.pi
```
![image](https://github.com/user-attachments/assets/7360eaa6-64c1-49a9-bf0c-73956c3453d7)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title('Sine wave form')
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/4d97f6e3-9b45-49d1-8b10-e79b4ad93b4e)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/2971cf24-daa3-4e86-9eb1-053e7fda2ff6)
```

x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.stackplot(x,y1,y2,y3,labels=['Line1','Line2','Line3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()
```
![image](https://github.com/user-attachments/assets/48ae1fcc-d6bf-4b5a-8229-5fc4ea0894de)

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x = np.array([1,2,3,4,5,6,7,8,9,10])
y = np.array([2,4,5,6,7,8,8,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/c8ff9b9d-1557-4b6e-bc30-a9e59593ae57)

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=['A','B','C','D','E']
plt.bar(names,values,color='green')
plt.show()
```
![image](https://github.com/user-attachments/assets/1ed34b0f-18cb-45fe-b185-ecc7af85b3f2)

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=['A','B','C','D','E']
plt.barh(names,values,color='yellowgreen')
plt.show()
```
![image](https://github.com/user-attachments/assets/90ce15de-fa5a-430f-8b1c-f4f8e3f2b24f)
```

import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/df14f6a8-2b67-41b7-ad7f-264220f54103)

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
![image](https://github.com/user-attachments/assets/cb5855a2-a611-4cd3-b7e9-26b856920e92)

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
![image](https://github.com/user-attachments/assets/7dbfd7e7-d7e9-4722-bf0b-51c9fba8fb52)

```
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/3b6a3ab4-fae3-4001-97b6-c93677c2c354)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/ba198b64-b050-489f-8e1f-21a30633bff5)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/ddcd57f8-b28f-4f2b-8a9f-20acbb22d4f9)
```

import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/b3ee428c-6798-4fc4-b926-d4b5d0f5face)
```

labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct="%1.1f%%",shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/e3455128-80c6-4a10-bd16-7015cae0c291)

# Result:
Data Visualization using matplot python library for the given data is successful.
