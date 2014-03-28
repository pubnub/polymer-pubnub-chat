# PubNub Chat Polymer Element

```html
<!DOCTYPE html>
<html>
<head>
    <script src="bower_components/platform/platform.js"></script>
    <link rel="import" href="elements/pubnub-chat.html">
</head>
<body>

    <!-- =-=-=-=-=-=-=-=-=-= -->
    <!-- PubNub Chat Element -->
    <!-- =-=-=-=-=-=-=-=-=-= -->
    <pubnub-chat
          publish-key="demo"
        subscribe-key="demo"
             presence="User {action}: {uuid}"
            chat-room="seahorse-flavor"
           auto-focus="true"
    ></pubnub-chat>

</body>
</html>
```
