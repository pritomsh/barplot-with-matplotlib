
# What is Barplot ?

A barplot shows the relationship between a numeric and a categoric variable. Each entity of the categoric variable is represented as a bar. The size of the bar represents its numeric value. 
# 
plt.bar(data.Area.unique(), data.Area.value_counts(), width=.3, color=['black', 'red', 'green', 'blue', 'cyan'])     
#
![](https://github.com/pritomsh/barplot-with-matplotlib/blob/master/image/bar.png)
#
plt.barh(data.Area.unique(), data.Area.value_counts(), color=(0.2, 0.6, 0.6, 0.6))
#
![](https://github.com/pritomsh/barplot-with-matplotlib/blob/master/image/horizontal.png)
#
- plt.xlabel('category', fontweight='bold', color = 'green', fontsize='18')
- plt.ylabel('values', color = 'red', fontsize='18')
- plt.xticks(color='orange')
- plt.yticks(color='orange')
#
![](https://github.com/pritomsh/barplot-with-matplotlib/blob/master/image/labelcorolchange.png)
#
Label  socre 
#
![](https://github.com/pritomsh/barplot-with-matplotlib/blob/master/image/labelscoretop.png)
#
plt.bar(data.Area.unique(), data.Area.value_counts(), color=['green'],  edgecolor='red')
#
![](https://github.com/pritomsh/barplot-with-matplotlib/blob/master/image/borderandedge.png)
#
fig.text(.6, -0.15, '© Pritom Saha', fontsize = 12,color ='red', ha ='right', va ='bottom',alpha = 0.7)
#
![](https://github.com/pritomsh/barplot-with-matplotlib/blob/master/image/watermark.png)

Ref : <a href="https://www.python-graph-gallery.com/barplot/"> The Python Graph Gallery Barplot</a>


