 
# Introduction
*--- <font size=3>A Brief Overview</font>*

The sudden COVID-19 in 2020 disrupted our life order. So far, the global new crown epidemic has caused a total of more than 67 million infections and more than 1.53 million deaths. With an efficient real-time statistical system, the growth of these numbers is particularly shocking.
<br>
![Origin img](https://img-blog.csdnimg.cn/20201211114316525.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RpbmdqdzE4,size_16,color_FFFFFF,t_70#pic_center)

We chose visual work to describe the process of the COVID-19 outbreak in China. As can be seen from the figure, China’s daily number of confirmed cases has experienced many abnormal fluctuations, which makes more and more people suspect that China is falsifying official COVID-19 statistics. So has China really manipulated official statistics on COVID-19?
# Dive into the Visual work
*--- <font size=3>Detailed description of the Visual work </font>*
## Story of the Chart
EVER SINCE the new coronavirus started to spread beyond China’s borders, the country’s official tally of infections has served as a grim benchmark for the outbreaks that followed. On March 26th the count in China was surpassed by that in America, now the center of the pandemic. Since then China’s total, close to 83,000, has also been overtaken by those of Italy, Spain, Germany, and France. 

 - **Data are Volatile**
Across the nine Chinese provinces with serious outbreaks, we identified 15 episodes in which new cases of covid-19 jumped by more than 20% in a single day, before quickly returning to earlier levels. Although such spikes can occur in any dataset—because of erratic record-keeping, for example—we found that other countries and regions with covid-19 outbreaks, of a similar size to these provinces, have experienced fewer. 

 - **Peaks are Accompanied by the Government's Decision**
Take Hubei, the province hit hardest by covid-19. On February 9th the region reported a 27% increase in new infections. On the next two days, new cases declined by 20% and 22%, respectively. Then on February 12th, they surged by a whopping 742% to almost 14,000, before immediately falling back sharply. Chinese authorities say the spike was caused by revisions to the government’s methodology for counting cases. But these changes were introduced nearly a week earlier and were reversed seven days after the spike (see chart). An alternative explanation for the surge in new cases on February 12th was another event, announced the next day: the sacking of the party chiefs of both Hubei and its capital city, Wuhan. <br>
Other spikes in new covid-19 cases have also coincided with changes in personnel or policy announcements. On January 27th officials in Zhejiang province held a press conference detailing the opening of 335 clinics and a 1,000-bed hospital to accommodate a surge of patients. The next day, new cases nearly tripled to 123, before declining sharply in the next few days. On February 20th authorities in Shandong province sacked the chief of the provincial justice department. That same day new covid-19 cases at a local prison jumped from two to 200, and then immediately returned to two the next day.

 - **Ending**
Do these data prove that China manipulated its covid-19 data, or that the country’s official tally of cases and deaths is lower than it should be? No. Most of these events happen independently. For these jumpy changes in the figure, conclusions can be drawn from the figure. The Chinese government's timely response to emergencies and timely control of the epidemic led to such a leap in data changes. The reason why it is different from other countries in the world is that each country has a different political system and different national ideology and culture.

## Visual Variables
 - position
 - color of polylines

## Cognitive theory
From the perspective of cognitive theory, the chart has two characteristics that can be explained by cognitive theory.

 - **Attention Resources**
 In static images, people's attention is more focused on line segments with dynamic effects. In monotonous colors, attention is more focused on colorful line segments.
 

 - **Stroop effect**
  If the color and meaning are not in harmony, we must consciously decide which stimulus we will pay more attention to. In this visualization, a wide range of gray is used, and most of the polylines are gray, so that the reader may think that all gray polylines have the same meaning, which will confuse the reader and subconsciously think that these gray polylines have no meaning. But this is contrary to the facts. This will reduce the readability of the visualization.

## Context

 - **Purpose**
The figure plots the number of daily infections of China's new crown epidemic, which can reflect the development trend of China's epidemic. This picture is to explain the reasons for the fluctuation of China's new crown epidemic data, and to study whether Chinese officials have falsified the new crown epidemic data.
 - **Readership**
 Researchers, medical practitioners, politicians, ordinary people, readers of The Economist
 
 - **Media**
Magazines, articles


<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">


# Replicate  Charts
*--- <font size=3>Replicate the information visualization via Matplotlib </font>*

 - **Original chart**
![Original chart](https://img-blog.csdnimg.cn/20201211145816498.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RpbmdqdzE4,size_16,color_FFFFFF,t_70#pic_center)

 - **Replicate**
![Replicate chart 1](https://img-blog.csdnimg.cn/20201211121853570.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RpbmdqdzE4,size_16,color_FFFFFF,t_70#pic_center)
![Replicate chart 2](https://img-blog.csdnimg.cn/20201211121912226.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RpbmdqdzE4,size_16,color_FFFFFF,t_70#pic_center)
<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

# Inadequacy & Improvement
*--- <font size=3>Constraint with visual standards </font>*
## Inadequacies of Graphs
 - **X-axis label**
The x-axis label only shows three areas: January, February, and March. It can not allow readers to easily obtain useful information.
 - **Color usage**
In the map with multiple provinces, only the data of two provinces can be distinguished, other provinces cannot be distinguished. According to Attention Resources in cognitive theory, in monotonous colors, attention is more focused on brightly colored line segments, and in static images, people's attention is more focused on line segments with dynamic effects.
 - **Reference line**
Reference lines do not specify a specific date.


## Improvements of Graphs
 - **X-axis label**
Change the x-axis label to the date format and place it diagonally for easy reading.
 - **Color usage**
Add the dynamic effect of mouse hovering. When the mouse is hovering over a certain province, city and city map, it will be highlighted and bold, and the name of the province will be displayed in the map. So that readers can better see the data trends of different provinces.
 - **Reference line**
Add a specific date to reference lines.

<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

#  Implement the changes
*--- <font size=3>Achieve perfect visual work</font>*
![figure 2](https://img-blog.csdnimg.cn/20201211153135160.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RpbmdqdzE4,size_16,color_FFFFFF,t_70#pic_center)

![dynamic picture](https://img-blog.csdnimg.cn/2020121113585385.gif)

# Conclusion
We added dynamic effects to the original visualization to make the pictures vivid and interesting so that readers can quickly obtain the information. Good visualization is usually should be concise, inspiring, and most importantly, must be strict, accurate, and faithful, which can make our visualization effectively convey information to readers. Now readers only need to combine the new information visualization to quickly understand the specific meaning of the visualization chart and easily obtain information.


<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">


# *Working Notes*
*--- <font size=3>Tell about the difficulties in the work process </font>*
 - **Mouse move event**
Trying to use the mouse event in matplotlib is pretty hard. At first, we wanted to use the mouse pressed event to select a specific line, but for some reason, it doesn't work and we couldn't figure it out. 
Then we decided to use a mouse move event, but there is another problem. That when the mouse moves out of the canvas, it will start to print tracebacks and warnings. We can't limit the mouse on the canvas, that will make users' experience pretty bad, so we had to use try-except structure to ignore the tracebacks and warnings. 

 - **Method of detection**
To detect whether the mouse is on the specific line, we tried to use the x coordinator to locate the line and then compare the y coordinator, but the data of x is pandas.DateTime. It shows a normal date like '2020-02-10', but when we use mouse event to print the fig.event.xdata, it appeared to be a very strange number as 7000000 or something. Data like this can't match the data of datetime, so we changed the method to y coordinator. 
But here comes another problem. Without x coordinator, we could only match the y data to the whole line, if there is one dot in the line matched the data, it'd be bold and change color, but maybe this dot matched many lines. This problem we can't solve.
If you select a line, the province name of it will appear on the graph title.

 - **Plot drawing**
If the mouse matched the line, the line will be changed to black and bold. At first, we forgot what will happen if selecting many lines at one time, so if you move the mouse till it matched many lines, it was a pretty disaster, the whole graph is filled with black and bold lines. We quickly solved the problem by re-draw the other lines before bold the specific line. 
We re-considered the output, it seems very messy with colorful lines and a bold line. So we made all the other lines grey when one line is bold. And the very one line will be red and bold.!


