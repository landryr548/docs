{{Page_Title|Media Capture and Streams}}
{{Flags
|Checked_Out=No
}}
{{Standardization_Status|W3C Working Draft}}
{{API_Name}}
{{Summary_Section|Enables access to local devices (video cameras, microphones, Web cams) that can generate multimedia stream data (video, audio, or both).}}
{{API_Listing}}
{{Concept_Listing
|Query=[[Category:Media_Capture_and_Streams]][[Category:API_Objects]]
|Use_page_title=No
|List_all_subpages=No
}}
{{Notes_Section
|Usage=The MediaStream interface is used to represent streams of media data, typically (but not necessarily) of audio and/or video content, e.g. from a local camera. Each MediaStream object can contain zero or more tracks, in particular audio and video tracks. And each track in a MediaStream object has a corresponding MediaStreamTrack object.

A MediaStreamTrack represents content comprising one or more channels, where the channels have a defined well known relationship to each other (such as a stereo or 5.1 audio signal).

A new MediaStream object can be created from accessible media sources using the MediaStream() constructor, or generated by a [[dom/methods/getUserMedia|getUserMedia()]] call. After calling navigator.getUserMedia the user is asked for permission to let the browser access the camera or the microphone.
}}
{{See_Also_Section
|Topic_clusters=Mobile, WebRTC
|External_links=* [http://www.w3.org/TR/mediacapture-streams/ Media Capture and Streams API]
* [http://www.w3.org/TR/2013/WD-mediacapture-streams-20130516/ Media Capture and Streams API - W3C Working Draft 16 May 2013]
* [http://www.w3.org/2009/dap/ Device APIs working group]
* [http://www.w3.org/2011/04/webrtc/ WebRTC working group]
* [http://www.w3.org/wiki/Media_Capture Media Capture Wiki]
}}
{{Topics|API, WebRTC, Media Capture and Streams}}
{{External_Attribution
|Is_CC-BY-SA=No
|MDN_link=
|MSDN_link=
|HTML5Rocks_link=
}}