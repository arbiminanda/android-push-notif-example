# android-push-notif-example

- Apps will connected to FCM services when being opened and return FCM token that can be used to sent notif from other services.

- Make sure place google-services.json that you get after setting up firebase project on app/ directory

- Push notif will be received when apps on background

- When apps in foreground, notif will be received on log cat, still need improvement by utilize that messages to display any notif when apps on foreground

```
D/MyFirebaseMsgService: Message Notification Body: You have a new message in the chat.
```
