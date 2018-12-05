# iOSCodeSign
macho edit resign is a tool running under windows/linux/MacOS write c#

# macho editor
  1. add/remove/extract entitlements.xml from macho
# IPA resign
  1. multi-macho codesign support
  2. frameworks, xpc, dylibs ...etc support
# embededfile
  inorder to make your APP works well, you shoud specify embedded file and provide the right privilege


# usage
  iOSCodeSign original.ipa new.ipa embeddedpath pkcs.p12 ent.xml
  
  original.ipa is the source IPA you want to resign
  new.ipa is the filename of new IPA
  embeddedpath is the filename you applied from devloper.apple.com
  pkcs.p12 pkcs12 file exported from Xcode without password. 
  
