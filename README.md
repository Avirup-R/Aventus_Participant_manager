﻿# Aventus_Participant_manager
 
 # A website that can be used to register the status of the participants in an Hackathon for easy management of the participants in the campus.
 
## A Flask app that creates API end-point, that if scanned by mobile phone(google lens) or any other device redirects(to the hosted site). THen based on the condition updates the values.

### It uses firebase for storage of the data.

## For the first time scanned. It registers as a Master CHeck in and for the next consecutive scans it registers as check in/ check out.

## Create a .csv file with details for entering the data into firebase for the first time and create a column count which checks for the master checkin status.

## Also remember to create a authentication user for the system so that the participants could not do the same as the event manager. Firebase usually uses the concept of session tokkens. This makes sure that you would not have to enter password every time. Just once in a hout.

### Porbably try to host on render. Quite simple to do it.

### For local host run $ python app.py
