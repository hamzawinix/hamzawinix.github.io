# running Zathura under wsl

## Introduction (you can skip)
Zathura is a great pdf viewer, unfortunately it ain't available for windows natively (yet), here is hopefully an easy way to run it under wsl using VcXsrv.

## Assumptions

### you downloaded and installed 

- [ ] [VcXsrv](https://sourceforge.net/projects/vcxsrv/)
- [ ] [wsl](https://docs.microsoft.com/en-us/windows/wsl/install)

## VcXsrv section

### There isn't much to do here just go with the defaults

<img src="https://user-images.githubusercontent.com/34142795/134903197-550f11fd-7268-4f16-bbc4-caa73a6ed253.png" width="40%" height="40%">
## wsl section

``` bash 
$ export DISPLAY=127.0.0.1:0.0
$ vim .config/zathura/zathurarc
set sandbox none
:wq
```

<img src="https://user-images.githubusercontent.com/34142795/134903542-51d5bb4d-3480-49bb-b4d1-0b3b314abff2.png" width="20%" height="20%">

```bash
$ zathura yourpdf.pdf
```

<img src="https://user-images.githubusercontent.com/34142795/134903711-3b1c8eea-cae2-47e3-8e2b-62ba61aae816.png" width="20%" height="20%">
<p align=center style="color : #ab67ab; font-family: 'Sofia';font-size: 44px;">Happy zathura-ing</p>


<link href='https://fonts.googleapis.com/css?family=Sofia' rel='stylesheet'>


<p style= "font-family: 'Sofia';font-size: 22px;">abcdefghijklmnopqrstuvwxyz</p>
