# Burp-Suite-Professional-latest-version

# burp-suite install linux

1. downloads JDK-18
2. open the downloads directory ====>> cd Downloads
3. file permutation ====>> chmod +x *
4. dpkg -i (JDK file name)
5. sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-17/bin/java 1
6. sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-17/bin/javac 1
7. sudo update-alternatives --config java
8. select the option 2 then
9.Run ====>> java -jar burploader.jar

++++++++ Run BurpLoader Run error+++++++++++

--> java -jar burploader.jar
--> If any error > open CMD and enter this
          rd /s /q "%userprofile%\AppData\Roaming\BurpSuite\"
          reg delete "HKEY_CURRENT_USER\SOFTWARE\JavaSoft\Prefs\burp" /f
          
Follow us___

1. https://www.facebook.com/devmehedi101
2. https://www.linkedin.com/company/securitytalent   
3. https://twitter.com/devmehedi101
4. https://www.instagram.com/devmehedi101/
5. https://www.youtube.com/@SecurityTalent/ 

Free Hacking Course Download__
https://t.me/Securi3yTalent
