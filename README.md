# cordova-ios-security
`cordova plugin add https://github.com/medipudipoojitha/cordova-ios-security.git`

It will add the following part to the `*-Info.plist` file during build process:

    <key>NSAppTransportSecurity</key> 
    <dict>
      <key>NSAllowsArbitraryLoads</key> <false/> 
    </dict>
