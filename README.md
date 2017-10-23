# webrtc-based-android-aecm
Java API for android acoustic echo cancellation.
=========================
Update from  BillHoo. https://github.com/lhc180/webrtc-based-android-aecm


webrtc-based-android-aecm
=========================

  Java API for android acoustic echo cancellation.
  
  I already tested and using it on a LAN demo several monthes ago, it worked well most of the time but sometimes with little squeal, I know there must have something todo to make it better.
To make it better
=========================
  1. Maybe I should build the whole VOE and using the C++ interface proveded by apm? I'll try this later. 
  2. The API is a low level one, most of them are just wrappers of native WebRTC aecm interface. We should handle so many things by ourselves, like estimate the echo tail,handle capture/render threads etc. I'm planning to provide a higher level of the API, which can handle those things for us automatically.

TODO List
=========================
  1. Build the apm interface.
  2. Provide a higher level of the API.
  3. Provide a VoIP demo to show how to use this API instead of doing AECM on PCM files.
