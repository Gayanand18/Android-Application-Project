# Reminder-App
This is a basic reminder app which takes in data(Date, Time and Message) from the user and notifies the user on the given date and time.
<br><br>
In this app, I have used ***Room Database*** for storing the data of the reminders. The user is being notified by a notification which contains the message entered by the user. 
We have been using ***AlarmManager*** which fires a ***PendingIntent*** which in turn call a ***BroadcastReciever*** that creates a notification for the user with the message.
<br>
* Adding Reminder<br>![Screenshot from 2019-06-13 11-58-39](https://github.com/Gayanand18/Android-Application-Project/assets/99050396/b7dc32db-31f7-4635-9f52-514262d0a7bb)
* All the reminders which haven't been notified<br>![Screenshot from 2019-06-13 12-06-28](https://github.com/Gayanand18/Android-Application-Project/assets/99050396/75b444c1-eca5-4a0c-be5d-803f6739723b)

