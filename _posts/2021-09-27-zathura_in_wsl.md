
# running Zathura under wsl

## Introduction (you can skip)
Zathura is a great pdf viewer, unfortunately it ain't available for windows natively (yet), here is hopefully an easy way to run it under wsl using VcXsrv.

## Assumptions

### you downloaded and installed 

- [ ] [VcXsrv](https://sourceforge.net/projects/vcxsrv/)
- [ ] [wsl](https://docs.microsoft.com/en-us/windows/wsl/install)

## VcXsrv section

### There isn't much to do here just go with the defaults

![Pasted image 20210927114032](https://user-images.githubusercontent.com/34142795/134903197-550f11fd-7268-4f16-bbc4-caa73a6ed253.png)

## wsl section

``` bash 
$ export DISPLAY=127.0.0.1:0.0
 
$ vim .config/zathura/zathurarc
```
```vim
set sandbox none
:wq
```

![image](https://user-images.githubusercontent.com/34142795/134903542-51d5bb4d-3480-49bb-b4d1-0b3b314abff2.png)

```bash
$ zathura yourpdf.pdf
```
![Pasted image 20210927135228](https://user-images.githubusercontent.com/34142795/134903711-3b1c8eea-cae2-47e3-8e2b-62ba61aae816.png)

