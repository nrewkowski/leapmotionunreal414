# leapmotionunreal414
Blueprint code to get the Leap Motion working in Unreal 4.14. The code will work in previous version if you copy the nodes (assuming that the plugin is enabled or built).

Includes blueprint assets and classes needed to get stuff working. Keep in mind that you will need to enable the Leap Motion plugin in Plugins>Input Devices for any of this to work.

Much of this code comes from Getnamo's Leap Motion VR Jenga videos on Youtube. His base code from that video is modified here to allow each hand to grab a different item. Also, I have added support for the more realistic floating hands (as opposed to the riggedhandscharacter), which I did not see any tutorials for.
Additionally, there is support for magnetism at a certain range. By default, the range is 10cm. This can be changed in LeapFloatingHandsCharacter_Child.

I have shared this repo because it does not seem like there are many people using the Leap Motion in newer versions of Unreal (probably because it is difficult to get working correctly). Hopefully, we see more projects that use this awesome device!
