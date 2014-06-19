# SIMPLE OFFLINE CHECKING FOR HTML5 APP

This is a simple implementation to check if you have gone offline. This is used to replace the view of certain areas on your app with an alternative content, ie, replacing YouTube embed with an offline message, or a Save button with a disabled version.

It's pretty simple actually. Just check the codes to understand how it works. Basically, what you need is a block like this.

```html
<div class="offline-check">
    <div class="offline">offline content</div>
    <div class="online">online content</div>
</div>
```

For desktop app (i.e. Node-Webkit) or mobile app (i.e. Phonegap), you need to use a URL that allows cross-origin access or CORS.
