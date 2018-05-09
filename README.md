# ICP7

##Objectives:
Using the provided source code, modify the native Android application to do the following:
1)	Add a Calendar to the activity
2)	Project the Calendar to the current date
3)	Upon clicking a date, it should be displayed above the Calendar in a TextView
4)	Create a Signed APK

##Solution
1)	I added a Calendar via XML to the View and instantiated the Calendar by ID in the Activity; simpleCalendarView.
2)	To set the current date, simply call the Calendar method getIntance()
3)	And to display the date that was clicked, I created a Calendar.OnDateChanged listener and set the TextView’s text.
4) Generated a Signed APK through Android Studio.