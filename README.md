# Jquery-SingleImagePopup

This is a simple Image popup Jquery plugin. With a very simple configuration, you can show a popup on your webpage. By the way, this plugin works after page load.

**If you want to see, click the [DEMO](https://github.com/rajankarmakar/jquery-singleimagepopup).**

**Or you can see the screenshot below.**
![Single Image Pupup Jquery Plugin Screenshot](/assets/images/sample.jpg)

---

## Getting Started

Before you get started I want to mention, no complex thing to do. Just a few simple steps to do. Follow the following steps and you are ready to go.

### Step #1

Just download the [repo](https://github.com/rajankarmakar/jquery-singleimagepopup.git) or clone it from this command below :

```tsx
git clone https://github.com/rajankarmakar/jquery-singleimagepopup.git
```

After downloading the zip file, just unzip it into your desire location.

### Step #2

Place this block of code before closing the </head> tag into your desire HTML file.

```tsx
<link rel="stylesheet" href="assets/css/singleimagepopup.min.css" />
```

Into the <body> tag place the code below.

```tsx
<div id="singleimagepopup"></div>
```

And finally, before closing the </body> tag place this block of code as well.

```tsx
<script src="assets/js/jquery.min.js" crossorigin="anonymous"></script>
<script src="assets/js/jquery.singleimagepopup.min.js"></script>
<script>
  $(document).ready(function () {
    $("#singleimagepopup").singleImagePopup();
  });
</script>
```

The final code should look something like the below.

```tsx
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="assets/css/singleimagepopup.min.css" />
  </head>
  <body>

    <div id="singleimagepopup"></div>

    <script src="assets/js/jquery.min.js" crossorigin="anonymous"></script>
    <script src="assets/js/jquery.singleimagepopup.min.js"></script>
    <script>
      $(document).ready(function () {
        $("#singleimagepopup").singleImagePopup();
      });
    </script>

  </body>
</html>
```

And you are done, awesome. Just visit the page, you should see the popup after the page load.

## Default options

```tsx
$("#singleimagepopup").singleImagePopup({
  width: "560px",
  height: "400px",
  imageUrl: "/assets/images/sample.jpg",
  stop: false,
});
```

These are the default options of the plugins.

### # Change Image

If you want to change the image, which you will do just change the imageUrl value as you want. Please see the example below.

```tsx
$("#singleimagepopup").singleImagePopup({
  imageUrl: "https://unsplash.com/photos/hzHQR0mHKQg/download?force=true&w=640",
});
```

### # Change Image Width

If you want to change the image width just change the width value as you want. Please see the example below.

```tsx
$("#singleimagepopup").singleImagePopup({
  width: "560px",
});
```

### # Change Image Height

If you want to change the image height just change the height value as you want. Please see the example below.

```tsx
$("#singleimagepopup").singleImagePopup({
  height: "400px",
});
```

### # Stop Popup

If you want to stop the Popup, just a single line of code. Please see the example below.

```tsx
$("#singleimagepopup").singleImagePopup({
  stop: true,
});
```
