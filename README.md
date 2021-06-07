# karatekaMy
1st step ✘ mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/cordova create Karateka my.edu.pmu.Karate KaratekaMy
2ns step  ✘ mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/Karateka  cordova platform add android
cordova platform add ios

 3rd step insert jquery mobile and jquery in the header
 <link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>

it is better to host these scripts offline especially when deploying to your device
4th step delete  <meta http-equiv="Content-Security-Policy"
        content="default-src 'self' data: gap: https://ssl.gstatic.com 'unsafe-eval'; style-src 'self' 'unsafe-inline'; media-src *; img-src 'self' data: content:;">

5th step remove everything from the body

6th start creating pages

7th  mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/Karateka   main  cordova serve