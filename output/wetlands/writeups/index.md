<!--
.. title: Write Ups
.. slug: writeups
.. date: 2018-12-15 11:07:52 UTC-05:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->
# Abstract

To not repeat myself in the write-ups, please refer to the [info page](/wetlands/info) of the repo for the introduction, methods, and materials.

# 2016 Write-Up

## Analysis

Analysis will start from [June of 2016](/wetlands/timeline), as I did not collect data and notes.

### Big Pond

In the beginning of my data collection, I noted that Ammonia was at 0.25 parts per million (ppm) seven (7) weeks with two weeks of 0.5 ppm in between the weeks of the 0.25 ppm levels. The pH levels stayed around 7 with two (2) weeks of 7.5 and a week of 8. Luckily the Nitrite and Phosphate levels stayed at zero (0) ppm.

### Small Pond

In the beginning of my data collection, I noted that Ammonia was at 0.25 ppm in the small pond for eight (8) weeks. Near the end of the season, the Phosphate levels peaked at two (2) ppm but within two weeks, it went back down to zero (0). The pH levels ranged from 6 to 7.5, mostly the 7 to 7.5 range with a week of 6 and two (2) with 6.5. Luckly the Nitrite levels stayed at zero (0) ppm.

## Conclusions

### Big Pond

The reason why the Ammonia stayed at 0.25 ppm then dropped is because (as noted in the [timeline](/wetlands/timeline)the cattle nearby the pond were moved further away from it.

### Small Pond

I have no explaination to the Ammonia levels in the small pond in the summer months of June and July and the first week of Auguest. But for the rest of the data collection, there might be a correlation with weather because it rained those days where there were spikes.  Same for the Phoshate levels for those two weeks. As for the pH levels, the plants that were put in could of made a difference but that is only a guess.

### Other Notes

I found out that LirbeOffice handles .csv files better than Microsoft Office. I also did not think on how to format when I started to data collect the .csv file in terms of formating the date as a three colum seprated entry instead of a simple mm-dd-yy format. If I did the date in the correct format, I would of had charts to show, either from LibreOffice or from R. Because of this, there are no charts for this write-up. Plus, most of the deviations from 7 pH and zero (0) ppm respectfully of the values measured will show correlation with weather, mostly when it rains, and other factors, like the cattle being moved away from the big pond.

Due to me getting a new job just as the data collection season ended and then a bad case of winter blues, I did not get to do that much research on solutions. Because of this, I think I will collect data for the first half of the season and work on figuring out what plants could be placed in the small pond (the big one will be untouched).

# 2017 Write-Up

## Analysis

### Big Pond

So far this year, the pH started at 8 with a few times going down to 7.5 but in most of May and the first week of June. After that first week of June, the pH stayed stable with some fluctuations between 6 and 7.5.

![big.png](/images/bigRemoved.png)

I decided to focus on analyzing pH out of all the elements because it's the one that changes the most. The average pH over the years rose while the min went down and the max stayed the same.

There was only two ammonia level spikes but they didn't raise above 0.25.

Like last year, the nitrite and phosphate levels stayed down at 0 ppm.

### Small Pond

So far for this year, the pH has mostly stayed between 6.5 and 7.5, only one time reaching to 8; that was when the data collection season started.

![small.png](/images/smallRemoved.png)

I decided to focus on analyzing pH out of all the elements because it's the one that changes the most. The average pH over the years rose while the min and max changed through the years.

The ammonia levels were high in the start of the data collection season going from 0.25 ppm to 1 ppm then going down to 0, then again from 0.5 to 0. Until August, the levels stayed at 0, and at two moments rose to 0.25.

Only once, in June, the nitrite levels rose to 0.25 ppm but they quickly came down.

Like last year, the phosphate levels stayed down at 0 ppm.

## Conclusions

### Both Ponds

While I'm aware that the number of sample per year don't match, I still think the pH is slowly raising but not to a dangous level as this grahpic shows:

![](http://www.fondriest.com/environmental-measurements/wp-content/uploads/2013/11/ph_levels.jpg)

Once again, I think there might be a correlation with weather because it rained those days/weeks (before or that week) where there were spikes.

### Big Pond

Nothing can be said about the big pond, I think it's stable even though there is duckweed in the pond.

### Small Pond

Like the small pond, I think it's stable even though there is duckweed in the pond.

### Other Notes

N/A

# 2018 Write-Up

## Analysis

### Big Pond

![](/images/wetlands/big.png)

### Small Pond

![](/images/wetlands/small.png)

## Conclusions

The pH levels are stable in both ponds but it's hard to say if the levels are stable since these are once a week data point, at almost the same time, collections not 24/7 sensor collection.

### Other Notes

I realized my mistake on how I formatted the date data and fixed into week number, yy instead of mm,dd,yy. I used LibreOffice Calc to convert the date into week number based on the year and concatenating the year to 20yy, as I only had it in the two digit format. Function used: ```=WEEKNUM(DATE(CONCATENATE(20,D2),A2,B2))```
