# Stalking

Find the flag by stalking the user add underscore before and after n in id.

<p align="center">
  <img src="image1.png" alt="Description" width="500" height="500">
</p>

## Step:-1
We are given a file named Anonymous.webp. Since WebP is a modern image format, we should inspect its metadata to check if any hidden information is embedded within it.

Using the terminal, let's analyze the file details.


<p align="center">
  <img src="Anonymous.webp" alt="Description" width="500" height="500">
</p>

## Step:-2
We use the exiftool command, which is a tool used for extracting metadata from various file formats, including images, videos, and documents.<br>
```bash

exiftool Anonymous.webp
```
<p align="center">
  <img src="image2.jpeg" alt="Description" width="900" height="500">
</p>
This command reveals the metadata, and within the extracted details, we find an Instagram user ID: 

```n.o.l.o.v.e._```

## Step3:-
As per the challenge instructions, we need to modify the username by adding underscores before and after the letter n. This transforms the username into: `_n_.o.l.o.v.e._`
By searching for this user on Instagram and checking their comments or posts, we find the hidden flag embedded within the comments section.






