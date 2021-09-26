# Visualizing mail data

In this section, we work with an application that is the most complex so far and pull down nearly a gigabyte of data and visualize it.
We will be using data from a free email list archiving service called http://www.gmane.org. This service is very popular with open source projects because it provides a nice searchable archive of their email activity. They also have a very liberal policy regarding accessing their data through their API. They have no rate limits, but ask that you don’t overload their service and take only the data you need. You can read gmane’s terms and conditions at this page:

http://www.gmane.org/export.php

It is very important that you make use of the gmane.org data responsibly by adding delays to your access of their services and spreading long-running jobs over a longer period of time. Do not abuse this free service and ruin it for the rest of us.

## OUTPUT

![WordCloud-Output](Word_Cloud.png?raw=true "Word_Cloud")

A Word Cloud from the Sakai Developer List

You can download this application from:

https://www.py4e.com/code3/gmane.zip


## A second visualization is produced by gline.py. It computes email participation by organizations over time.

Its output is written to gline.js which is visualized using gline.htm.

## OUTPUT

### Sakai Developer Email Participation by Organization

![EmailData-Output](Sakai_mail_activity.png?raw=true "Email_data")
 
 Sakai Mail Activity by Organization

### Sakai Developer Email Participation by Organization With One Year Gap

![EmailData_1_year_gap-Output](mail_data_with_one-year-gap.png?raw=true "Email_Data_with_one_year_gap")

### For more info visit : [Week 4-6_Readme.txt](Week4-6_README.txt)

