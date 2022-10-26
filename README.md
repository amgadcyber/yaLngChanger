# yaLngChanger
 Ya LngChanger is tool that can change display language with country code for Android Devices via ADB - on Some Android Devices "Arabic" is hidden in settings.
  - for Ex, Motorola Phones. 
  - Tested on Moto G7.
  - works on Android 6 and newer.
  
# Requirements
- adb - ( For Communications :)
- an Android device
- a cable :)
- and some time :)


# NOTE
I made this script for personal use,just because I am tierd of doing it manually for each phone I flashed or upgrade, and anyone can use it - it's up to you :)

# Instructions
* clone the repo to have both auto and manual methods
 `git clone https://github.com/amgadcyber/yaLngChanger.git`

- **Automatic Method**
    - Just download the scipt 
    - `curl https://raw/github.com/amgadcyber/yaLngChanger/yaLngChanger.sh`
    - `chmod +x yaLngChanger.sh`
    - `bash yaLngChanger.sh -a`
    -  or :)
    - `./yaLngChanger.sh -a` :)
    - Simply Automatic Method means the language of your device will be changed autometically via adb
    
- **Manual Method Needs an app besides the scipt**
   - Simply Manual means, you change the language of your device using the installed app by **yaLngChanger**
 # USAGE
   Argument  | Explaination
   |  :---:    |---|
   |`-h`         | Print help message :) |
   |`-m`        | use **auto** method  :) |
   |`-m`         | use **manual** method :) |
   
   - `./yaLngChanger.sh -a`  **Automatic Method**
   - `./yaLngChanger.sh -m`  **Manual Method**
   
   * Enjoy :)
