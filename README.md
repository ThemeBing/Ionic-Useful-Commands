
<h2>Ionic Useful Commands</h2>

<ul>
  <li>npm i @ionic/lab</li>
  <li>ionic serve --lab</li>
  <li>ionic cordova build android</li>
  <li>ionic cordova run android</li>
  <li>ionic cordova emulate android</li>
  <li>ionic login example@gmail.com Password</li>
  <li>ionic cordova resources android</li>
  <li>ionic cordova build android --prod --release</li>
  <li>(Error When Creating the Keystore)
    Go to Control Panel > System > Advanced System Settings > Environment Variables.
Look for the PATH variable under System Variables and highlight it.
Click Edit.
In the Variable Value field, add a semicolon at the end of the values listed and the path to Java’s bin folder on your computer. For example: C:\Program Files\Java\jre6\bin</li>
  <li> keytool -genkey -v -keystore NAME_TO_CHANGE.keystore -alias alias_name -keyalg RSA -keysize 2048 -validity 10000</li>
  <li>After generate keystore copy and paste unsigned app to root folder</li>
  <li>jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore KEY_NAME_TO_CHANGE.keystore app-release-unsigned.apk alias_name</li>
  <li>./zipalign -v 4 app-release-unsigned.apk MY_APP_NAME.apk</li>
  *error*
  <li>npm install</li>
  <li>npm view ionic-native</li>
</ul>
<br>
<br>
<p>Here are the typical steps to set JAVA_HOME on Windows 10.</p>
<ol>
  <li>JAVA_HOME = C:\Program Files\Java\jdk1.8.0_221</li>
  <li>ANDROID_HOME/ANDROID_SDK_ROOT = C:\Users\Tashfin\AppData\Local\Android\Sdk</li>
<li>Search for Advanced System Settings in your windows Search box. Click on Advanced System Settings.</li>
<li>Click on&nbsp;<strong>Environment variables</strong>&nbsp;button: Environment Variables popup will open.</li>
<li>Goto&nbsp;<strong>system variables session</strong>, and click on New button to create new variable (HOME_PATH), then New System Variables popup will open.</li>
<li>Give&nbsp;<strong>Variable Name: JAVA_HOME</strong>, and Variable value : Your Java SDK home path. Ex:&nbsp;<strong>C:\Profram files\java\jdk1.8.0_151</strong>&nbsp;Note: It should not include&nbsp;<em>\bin</em>. Then click on OK button.</li>
<li>Now you are able to see your JAVA_HOME in system variables list.</li>
<li><strong>Select Path</strong>&nbsp;(from system variables list) and&nbsp;<strong>click on Edit button</strong>, A new pop will opens (Edit Environment Variables). It was introduced in windows 10.</li>
<li>Click on New button and give&nbsp;<strong>%JAVA_HOME%\bin</strong>&nbsp;at highlighted field and click Ok button</li>
</ol>
