# TTGO-esp32-Wifi-pager- PlatfromIO Build

TT-GO T-DISPLAY ESP32 to make a Wi-Fi Pager 

![IMG20210228091147](https://user-images.githubusercontent.com/20719445/109411957-a9301f00-79a5-11eb-90a8-c9d538a823ef.jpg)
![IMG20210228091157](https://user-images.githubusercontent.com/20719445/109411956-a8978880-79a5-11eb-9652-7599aabc3ae6.jpg)
![IMG20210228091203](https://user-images.githubusercontent.com/20719445/109411958-a9301f00-79a5-11eb-8b57-4100799379fa.jpg)
![IMG20210228091226](https://user-images.githubusercontent.com/20719445/109412062-36737380-79a6-11eb-8543-86d99bb5525e.jpg)

i used a TT-GO T-DISPLAY ESP32 to make a Pager style look a like Wi-Fi Pager.
It can pull text from pages or API pages setup using Thingspeak , ( or your own ).
i like to follow police traffic Pager communications so i provide its pulling Pager messages from a P2000 pager site (P2000 = GOV Pager trafic )
, also News and weather messages , it can handle 4 servers setup in the program , could ad more !
Its just handy to put on your desk .

just mod these lines ! inside the sketch to setup your Wifi 

#define APPNAME "YOUR WIFI SSID"    //Acces point name 

#define WPAKEY "YOUR WIFI KEY HERE"      // WPA KEY  

When holding 2 buttons at start it will have AUTO READ .
So if there is a new message it will show it on the screen !
hold top button wil select other server ,
lower button wil read the message 

its build using IDE ARDUINO , so easy 2 Upload the sketch , you need some Library's ,to make it al work ,
i bought my TTGO here , 

https://nl.aliexpress.com/item/4000272109285.html?spm=a2g0z.12010610.8148356.9.13ca1fccr53nWs

![IMG20210212120737](https://user-images.githubusercontent.com/20719445/109412080-41c69f00-79a6-11eb-811a-eea297da18fe.jpg)

https://www.youtube.com/watch?v=Kon4jTut7Ec&t

