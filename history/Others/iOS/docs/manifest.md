### 企业级应用发布所需的.plist文件:
```xml 
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>items</key>
	<array>
		<dict>
			<key>assets</key>
			<array>
				<dict>
					<key>kind</key>
					<string>software-package</string>
					<key>url</key>
					<string>.IPA-FILE-PATH(https)</string>
				</dict>
				<dict>
					<key>kind</key>
					<string>display-image</string>
					<key>url</key>
					<string>display-image-path</string>
				</dict>
				<dict>
					<key>kind</key>
					<string>full-size-image</string>
					<key>url</key>
					<string>full-size-image-path</string>
				</dict>
			</array>
			<key>metadata</key>
			<dict>
				<key>bundle-identifier</key>
				<string>APP-IDENTIFIER</string>
				<key>bundle-version</key>
				<string>1.2.7APP-VERSION</string>
				<key>kind</key>
				<string>software</string>
				<key>title</key>
				<string>APP-NAME</string>
			</dict>
		</dict>
	</array>
</dict>
</plist>
```
