# Coverright Widget Setup
## Setup instructions
### Widget 1
This code should be pasted in your page layout, where you want to place the CoverRight widget:
```
<script id="cover-right-widget-script" src="https://widget1.partners.coverright.com/js/iframe.js"></script>
```
The widget will take a full container width. We suggest you to don't use a container smaller than 360px in width.
---
### HERO WIDGET
This code should be pasted in your page layout, where you want to place the CoverRight widget:
```
<script id="cover-right-widget3-script" src="https://widget3.partners.coverright.com/js/iframe.js"></script>
```
The widget will take a full container width. We suggest you to don't use a container smaller than 360px in width.
---
### MEDIGAP RATE TABLE
This code should be pasted in your page layout, where you want to place the CoverRight widget:
```
<script id="cover-right-widget4-script" src="https://widget4.partners.coverright.com/js/iframe.js"></script>
```
The widget will take a full container width. We suggest you to don't use a container smaller than 870px in width.
---
### STICKY FORM WIDGET
This code should be pasted in your page layout, where you want to place the CoverRight widget:
```
<script id="cover-right-widget5-script" src="https://widget5.partners.coverright.com/js/iframe.js"></script>
```
The widget will take a full container width. We suggest you to don't use a container smaller than 420px in width.
---
### CARRIER REVIEW WIDGET
This code should be pasted in your page layout, where you want to place the CoverRight widget:
```
<script id="cover-right-widget6-script" src="https://widget6.partners.coverright.com/js/iframe.js"></script>
```
The widget will take a full container width. We suggest you to don't use a container smaller than 420px in width.
---
## Add custom parameters to a resulting url:
We set UTM tags automatically, but sometimes you might want to set the `subid2` or some other parameters in the resulting url. There is way to do that:
```
window.CoverRightWidgetParams = {subid2: '1234567'};
```
The `var1=1234567` would be added to url and tracked by affiliation link rule.
## Full example:
```
<!DOCTYPE html>
<html lang="en">
<head></head>
<body>
<div style="width: 360px">
    <script>
        window.CoverRightWidgetParams = {subid2: '1234567'};
    </script>
    <script id="cover-right-widget-script" src="https://widget1.partners.coverright.com/js/iframe.js"></script>
</div>
</body>
</html>
```