---
layout: post
title:  "New Program Thoughts"
date:   2015-06-22 18:58:19
categories: ruby sql
---

## New Program thoughts.
We have three animals at our house and I am horrible at remembering when the last time 
we put frontline on them or when we last got them groomed. I’d like to create program 
that tracks all of my animals events (medicine, vet, grooming). Often, our 
animal events are done to one or multiple of our animals the same day, and also, many animals 
have several animal events done to them in a year. The ideal functionality in future 
iterations would have the user pick the animal event and the animals involved and it records a 
time stamp for that day, instead of them having to enter a date, and also pick an 
increment of when they should have this event next. It would then send a push notification to 
them when the specific or multiple animals next event should be done. 
 
The one to many relationship is the user (me) has several animals. 
 
The many to many relationship is that the animal has many animal events 
throughout the year, and each event could have many animals involved. 