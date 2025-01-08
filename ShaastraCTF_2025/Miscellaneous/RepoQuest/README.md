# RepoQuest

Can you navigate the twists and turns of the file and find flag?

## Step1:-

We have given a zip file. lets open it in terminal.
use this command to unzip the file

```bash
unzip smallfolder.zip
```

<p align="center">
  <img src="image1.png" alt="Description" width="500" height="500">
</p>

## Step2:-

After extracting the file, we got <b>gitquestion</b>. As name suggest we might need to use git command or something similar.

<p align="center">
  <img src="image2.jpeg" alt="Description" width="500" height="500">
</p>
Yes!! we need to use git command.
<p align="center">
  <img src="image3.jpeg" alt="Description" width="500" height="500">
</p>

## Step3:-

We will be using the<b> VS Code</b> extension <b>Git Graph </b>to analyze what exactly is happening.<p align="center">
<img src="image4.png" alt="Description" >

</p>
here we got the second part of the flag . In Fourth commit user id is bit diffrent than other i.e.

`ster_!n`

## Step4:-

Therefore starting part of flag is `Shaastra{M@`

<p>
  <img src="image5.png" alt="Description" >
</p>

## Step5:-

sixth commit says something about flag. lets investigate more in sixth commit.

  <p><img src="image6.png" alt="Description" >
</p>
Check weather there is any branch or not??<br>
yes!!!
<p align="center">
  <img src="image7.png" alt="Description" width="300" height="300">
</p>
Final flag is

`Shaasta{M@ster_!n_g1t_commit}`
