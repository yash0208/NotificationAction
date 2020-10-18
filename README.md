# NotificationAction
we will add a tap action to our notification that will open an activity, and we will add an action button that will trigger a BroadcastReceiver to execute some code in it’s onReceive method.
In both cases we have to create an Intent and wrap it into a PendingIntent, which we pass to our NotificationCompat.Builder. We define the tap action with setContentIntent and add our action buttons with addAction.
Also we will change the color of our notification content with setColor and specify it’s behavior with setAutoCancel and setOnlyAlertOnce.

- Documentation about back stack & navigation:
developer.android.com/training/notify-user/navigation
developer.android.com/guide/components/activities/tasks-and-back-stack
