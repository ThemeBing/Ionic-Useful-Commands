
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
  <li> keytool -genkey -v -keystore NAME_TO_CHANGE.keystore -alias alias_name -keyalg RSA -keysize 2048 -validity 10000</li>
  <li>After generate keystore copy and paste unsigned app to root folder</li>
  <li>jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore KEY_NAME_TO_CHANGE.keystore app-release-unsigned.apk alias_name</li>
  <li>zipalign -v 4 app-release-unsigned.apk MY_APP_NAME.apk</li>
  *error*
  <li>npm install</li>
  <li>npm view ionic-native</li>
</ul>
