# piSys
Open terminal prompt, ssh to your **Raspberry Pi** device and use this script sys.sh to quickly view system information about the Raspbian OS running on your Raspberry Pi 

### Screenshot 
![Screenshot](source/screen.png)


### Installation
ssh to your Raspberry Pi device and run the following command to install the script
```bash
$ git clone https://github.com/ffares/piSys.git
$ cd piSys
```


### Usage
Using this script is very simple, just run this from the commnd line:

```bash
$ ./sys.sh
```

You may wish to run this script on login, you will need to edit .bash_profile file `nano ~/.bash_profile` and add this like: 
`/home/pi/piSys/sys.sh`



> Terminal theme used in the screenshot can be downloaded from here http://color.smyck.org
