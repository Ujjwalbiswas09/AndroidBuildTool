# AndroidBuildTool

Dont use these library as a part of your application.<br>

Paste library files in private Data directory.(.getFilesDir());


<h2>Bundle-android.jar</h2>
<ul>
  <li>bundle-android.jar is the combination bundletool, R8, D8.</li>
  <li>bundle tool helps to create .aab file(bundle).</li>
  <li>playstore don't allow APK anymore, it replace by .aab file<br>
  You need to export your project as .aab if you want publish your on Play Store</li>
</ul>
  
<h2>Aapt</h2> <ul>
<li>Aapt Tool Stands For Android Asset Packaging Tool.</li>
<li>aapt uses to compile resources, manifest and Generating Resource id class (R.java)</li>
<li>aapt also build apk (unsigned).</li>
<li>It also can modify existing apk(dump).</li>
</ul>

<h2>D8</h2> <ul>
<li>D8 uses to convert .class (Java ByteCode) into .dex(Dalvik Executable Code).</li>
<li>Android Supports Dalvik Code Not Java Code</li>
<li>It also can convert .Jar to .Dex. </li>
<li>D8 Supports Java 8 Code Conversation. </li>
</ul>

<h2>EJC Compiler</h2> <ul>
<li>EJC Compiler is a java code compiler.(.java to .class)</li>
<li>EJC Compiler used to compile java byte within JVM.</li>
<li>EJC Compiler support Upto java 1.7.</li>
</ul>

<h2>Aapt2</h2> <ul>
<li>Aapt2 is the Upgarded Version of Aapt.</li>
<li>Aapt2 can compile resource into protobuf format.</li>
<li>Aapt2 is necessary for aab building.</li>
</ul>

<h2>Zipalign</h2> <ul>
<li>Zipalign is used align Uncompressed Files</li>
<li>Zipalign helps to reduce ram usage of appplication which Align by it.</li>
<li>Zipalign helps to reduce application starting time.</li>
<li>Zipalign helps to reduce post installation Application Size.</li>
</ul>

<a href="https://youtube.com/@I-D0NT-KNOW">Youtube</a>
