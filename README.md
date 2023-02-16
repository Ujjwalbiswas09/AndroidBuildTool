# AndroidBuildTool

Dont use these library as a part of your application.<br>

Paste library files in private Data directory.// .getFilesDir();


<h2>Bundle-android.jar</h2>
<ul>
  <li>bundle-android.jar is the combination bundletool, R8, D8.</li>
  <li>bundle tool helps to create .aab file(bundle).</li>
  <li>playstore don't allow APK anymore, it replace by .aab file<br>
  You need to export your project as .aab if you want publish your on Play Store</li>
</ul>
  
<h2>Aapt</h2> <ul>
<li>Aapt Tool Stands For Android Asset Packaging Tool.</li>
<li>aapt uses to compile resources, manifest and Generating Resource id class //R.java</li>
<li>aapt also build apk (unsigned).</li>
<li>It also can modify existing apk(dump).</li>
</ul>

<h2>D8</h2>
D8 uses to convert .class (Java ByteCode) into .dex(Dalvik Executable Code).(Android Supports Dalvik Code Not Java ByteCode)<br>
It also can convert .Jar to .Dex.
D8 Supports Java 8 Code Conversation.

<a href="https://youtube.com/@I-D0NT-KNOW">Youtube</a>
