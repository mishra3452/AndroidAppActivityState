# AndroidAppActivityState
The basic idea of this project is to learn how different activity states work in Android.  
Some of the basic Activity states are :  
  (1).onCreate()                  - is where you initialize your activity.  
  (2).onStart()                   - is used to start an activity.   
  (3).onResume()                  - works when you come back to your Intent or Activity by pressing the back button.  
  (4).onPause()                   - called once another activity gets into the foreground.  
  (5).onStop()                    - will be called when you leave the activity for some other activity.  
  (6).onRestart()                 - only called when the activity has gone in onStop state.  
  (7).onDestroy()                 - the final call you receive before your activity is destroyed.  
  (8).onSaveInstanceState()       - used to store instance state as a Bundle.(when you press the home button).  
  (9).onRestoreInstanceState()    - used to recreate the instance scope.(when you restart the app)  
  
Run the app on the emmulator and try to seen the 'logcat'. To get filtered output select 'Filter' available in the drop down in  
logcat and enter the desired filter name and set 'Log' as "MyMessage" (as used in the code).  
Try different configuration with the app(i.e. press the back button, press home button, restart app, etc).  
