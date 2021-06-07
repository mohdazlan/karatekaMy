##CONFGIURATION FOR BUILD
 mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/Karateka   main ● ls /Library/Java/JavaVirtualMachines//

jdk-14.jdk       jdk1.8.0_271.jdk

Only use jdk1.8!!!

 mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/Karateka   main ●  cordova requirements

Requirements check results for android:
Java JDK: installed 1.8.0
Android SDK: installed true
Android target: installed android-30,android-29,android-28
Gradle: installed /usr/local/Cellar/gradle/6.7/bin/gradle

Requirements check results for ios:
Apple macOS: installed darwin
Xcode: installed 12.4
ios-deploy: installed 1.11.3
CocoaPods: installed 1.9.1

# karatekaMy
1st step: ✘ mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/cordova create Karateka my.edu.pmu.Karate KaratekaMy

2nd step:  ✘ mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/Karateka  cordova platform add android
cordova platform add ios

 3rd step: insert jquery mobile and jquery in the header
 <link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>

it is better to host these scripts offline especially when deploying to your device

4th step: delete  <meta http-equiv="Content-Security-Policy"
        content="default-src 'self' data: gap: https://ssl.gstatic.com 'unsafe-eval'; style-src 'self' 'unsafe-inline'; media-src *; img-src 'self' data: content:;">

5th step: remove everything from the body

6th step: creating pages

7th step: mohdazlanabaziz@Mohds-MBP  ~/Documents/Web Development 2021/Karateka   main  cordova serve

<foreignObject width="100%" height="100%">
<!-- JPEGbay.com GALLERY START -->
<div gt="r" clear="all">&nbsp;</div>
<div id="jb-gallery8268543" style="max-width:500px;text-align:left; margin: 0 auto">
<div id="jb-images8268543" style="position:relative">
<div style="width:430px; height:300px; float:left">&nbsp;</div>
<a target="_blank" id="jb-link1" href="https://jpegbay.com/gallery/008268543-.html#1"><img class="jb-preview" style="opacity:1; " src="https://img1.jpegbay.com/gallery/008268543/1_m.jpg"><img class="jb-thumb" src="https://img1.jpegbay.com/gallery/008268543/1_t.jpg"></a>
<a target="_blank" id="jb-link2" href="https://jpegbay.com/gallery/008268543-.html#2"><img class="jb-preview" src="https://img1.jpegbay.com/gallery/008268543/2_m.jpg"><img class="jb-thumb" src="https://img1.jpegbay.com/gallery/008268543/2_t.jpg"></a>
<a target="_blank" id="jb-link3" href="https://jpegbay.com/gallery/008268543-.html#3"><img class="jb-preview" src="https://img1.jpegbay.com/gallery/008268543/3_m.jpg"><img class="jb-thumb" src="https://img1.jpegbay.com/gallery/008268543/3_t.jpg"></a>
<a target="_blank" id="jb-link4" href="https://jpegbay.com/gallery/008268543-.html#4"><img class="jb-preview" src="https://img1.jpegbay.com/gallery/008268543/4_m.jpg"><img class="jb-thumb" src="https://img1.jpegbay.com/gallery/008268543/4_t.jpg"></a>
<a target="_blank" id="jb-link5" href="https://jpegbay.com/gallery/008268543-.html#5"><img class="jb-preview" src="https://img1.jpegbay.com/gallery/008268543/5_m.jpg"><img class="jb-thumb" src="https://img1.jpegbay.com/gallery/008268543/5_t.jpg"></a>
<a target="_blank" id="jb-link1" href="https://jpegbay.com/gallery/008268543-.html#1"><img class="jb-preview jb-preview1" src="https://img1.jpegbay.com/gallery/008268543/1_m.jpg"></a>
<br clear="all">
<img src="https://jpegbay.com/gallery/008268543-.html#1" style="width:1px;height:1px;visibility:hidden">
</div>
<img style="border:none" src="https://jpegbay.com/static/jpegbay_com/gallery_icon.png"><style type="text/css"><!--
#jb-images8268543 a { text-decoration:none; }
#jb-images8268543 img { margin: 5px; border:1px solid #444; box-shadow:4px 4px 8px 0px #444; border-radius:10px; }
#jb-images8268543 a:hover img.jb-thumb {border:1px solid #444; box-shadow:4px 4px 8px 0px #888;}
#jb-images8268543 a img.jb-preview {width:384px; height:288px; margin:0; position:absolute; top:5px; left:5px; opacity:0; transition:opacity 0.5s ease-in;}
#jb-images8268543 a:hover img.jb-preview { opacity:1; transition:opacity 0.7s ease-out;#jb-images8268543 img { float: left; }}
--></style>
</div>
<!-- JPEGbay.com GALLERY END -->



</foreignObject>