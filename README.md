# DroidFiles v1.0
## Author: https://github.com/thelinuxchoice/droidfiles
## IG: https://www.instagram.com/linux_choice
### Don't copy this code without give me the credits, nerd! 

Get files from Android directories

![df](https://user-images.githubusercontent.com/34893261/49698790-b3408a00-fbaf-11e8-86aa-470e8b2eb519.png)

### Features:
#### Port Forwarding using SSH Tunneling with Serveo.net
#### Obfuscated URL by Tinyurl
#### Fully Undetectable

## Legal disclaimer:

Usage of DroidFiles for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 


### Installing on Kali Linux:
```
Install dependencies:
# apt-get update
# apt-get install default-jdk apksigner

For x86:
# apt-get install libc6-dev-i386 lib32z1

For AMD64:
# apt-get install lib32z1 lib32ncurses6 lib32stdc++6

Download SDK-Tools:
# wget https://dl.google.com/android/repository/sdk-tools-linux-4333796.zip
#mkdir -p $HOME/Android/Sdk
# unzip sdk-tools-linux* -d $HOME/Android/Sdk

Install SDKMAN
# curl -s "https://get.sdkman.io" | bash
# source "$HOME/.sdkman/bin/sdkman-init.sh"
# echo "Y" | sdk install java 8.0.191-oracle
# sdk use java 8.0.191-oracle
# sdk install gradle 2.14.1
# sdk use gradle 2.14.1

# echo "y" | $HOME/Android/Sdk/tools/bin/sdkmanager "platforms;android-25" "build-tools;25.0.1" "extras;google;m2repository" "extras;android;m2repository"

# git clone https://github.com/thelinuxchoice/droidfiles
# cd droidfiles
# bash droidfiles.sh
```

### Donate!
Support the authors:

<noscript><a href="https://liberapay.com/thelinuxchoice/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
