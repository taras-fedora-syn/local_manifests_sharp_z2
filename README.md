<?xml version="1.0" encoding="UTF-8"?>
<manifest>

  <remote  name="gitlab" 
           fetch="https://gitlab.com/"
           revision="cm-14.1" />

  <project name="taras-fedora-syn/android_device_sharp_z2" path="device/sharp/sharp_z2" remote="gitlab" />
  <project name="taras-fedora-syn/android_vendor_sharp_z2" path="vendor/sharp/sharp_z2" remote="gitlab" />

</manifest>

version="1.0" encoding="UTF-8"?>
<manifest>
	<remote fetch="git://github.com/" name="gh" /> 
	<project name="Moyster/o_vendor_mediatek" path="vendor/mediatek" remote="gh" revision="los-15.0" />
	<project name="taras-fedora-syn/android_device_sharp_z2" path="device/sharp/sharp_z2" remote="gh" revision="cm-14.1" />
	<project name="taras-fedora-syn/android_vendor_sharp_z2" path="vendor/sharp/sharp_z2" remote="gh" revision="cm-14.1" />
</manifest>
