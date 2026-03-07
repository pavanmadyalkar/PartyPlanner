# Media Library Guide

1. Add your image files to `assets/media/photos/`.
2. Add your video files to `assets/media/videos/`.
3. Open `js/script.js`.
4. Update the `mediaLibrary` array with each new file path, title, and description.

Example:

```js
{
    type: "photo",
    src: "assets/media/photos/haldi-setup.jpg",
    title: "Haldi Setup",
    description: "Morning function with yellow floral decor."
}
```

Use `type: "video"` for video entries.
