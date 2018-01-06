**Changes or fixes for StretchDog after 10.10.2017:**

**1.** Symlinks (in /usr/local/bin) to default applications need to be fixed in next release, see [Report here](http://murga-linux.com/puppy/viewtopic.php?p=971227#971227)  

**2.** Security patch for wpasupplicant, see [Here](http://murga-linux.com/puppy/viewtopic.php?p=971197#971197)   

**3.** Most recent version of pfind added to repository, install:  
```      
apt-get update     
apt-get install pfind  # will install v6.3     
```      

**4.** Upgrade of "youtube-get2" (v0.1.9) fixed "download from url", didn't work anymore because of some changes in youtube-dl (on which it depends, updated version included in the package)   
```      
apt-get update     
apt-get install youtube-get2     
```      

   