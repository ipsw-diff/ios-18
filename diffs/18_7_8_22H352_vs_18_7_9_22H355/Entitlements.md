## 🔑 Entitlements

### filesystem

### launchd

> `/sbin/launchd`

```diff

 	<true/>
 	<key>com.apple.security.network.server</key>
 	<true/>
+	<key>com.apple.security.script-restrictions</key>
+	<true/>
 </dict>
 </plist>
 

```
### adprivacyd

> `/usr/libexec/adprivacyd`

```diff

 		<string>com.apple.AdPlatforms</string>
 		<string>com.apple.AppStore</string>
 	</array>
+	<key>com.apple.security.script-restrictions</key>
+	<true/>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.ak.auth.xpc</string>

```
### appleaccountd

> `/usr/libexec/appleaccountd`

```diff

 	<true/>
 	<key>com.apple.security.personal-information.addressbook</key>
 	<true/>
+	<key>com.apple.security.script-restrictions</key>
+	<true/>
 	<key>com.apple.security.system-groups</key>
 	<array>
 		<string>systemgroup.com.apple.nsurlstoragedresources</string>

```
### audiomxd

> `/usr/libexec/audiomxd`

```diff

 		<string>com.apple.audio.piper</string>
 		<string>com.apple.coreaudio.device</string>
 		<string>com.apple.coreaudio</string>
+		<string>com.apple.coreaudio.private</string>
 		<string>com.apple.celestial</string>
 		<string>com.apple.coremedia.bag.airplay</string>
 		<string>com.apple.mediaexperience</string>

```
### replayd

> `/usr/libexec/replayd`

```diff

 	</array>
 	<key>com.apple.security.network.client</key>
 	<true/>
+	<key>com.apple.security.script-restrictions</key>
+	<true/>
 	<key>com.apple.selectivesharing.session_system</key>
 	<true/>
 	<key>com.apple.selectivesharing.system</key>

```
### symptomsd

> `/usr/libexec/symptomsd`

```diff

 	<array>
 		<string>RootDomainUserClient</string>
 	</array>
+	<key>com.apple.security.script-restrictions</key>
+	<true/>
 	<key>com.apple.security.system-groups</key>
 	<array>
 		<string>systemgroup.com.apple.osanalytics</string>

```
### symptomsd-helper

> `/usr/libexec/symptomsd-helper`

```diff

 	<array>
 		<string>RootDomainUserClient</string>
 	</array>
+	<key>com.apple.security.script-restrictions</key>
+	<true/>
 	<key>com.apple.security.system-groups</key>
 	<array>
 		<string>systemgroup.com.apple.osanalytics</string>

```


