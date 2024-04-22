# OhmVR
## Introduction
Open Haptics Manager for VR (Abbreviated as Ohm or OhmVR) is a software service that is meant to enable VR/XR application developers to create hardware-agnostic basic spacialized haptic feedback events. Ohm recieves Relative Coordinates from an application for a specific "field", calculates the appropirate haptic motors to activate, then sends the appropriate API calls to flip them on. The output API is intended to be modular: Ohm's "backend" communicates to haptic devices through protocols such as OpenXR, or loading in a 3rd party "driver". 

Ohm also allows user haptic device management through a dedicated UI front end. This is where the user will specify as needed locations of the haptics. TODO: explain this better

(note for later: techincally, is this a compatibility layer?)
## Things to Strive For
 - **Fast:** We need to strike a balance between Good and Fast. 
 - **Modularity:**
 - **Compatibility:** Due to the expanding role that the XR industrty takes on, we must ensure that this code works on a wide range of architectures. 

## How to Contribute
80 character line limit in source code, for consistency. 
TODO: this section

TODO: wiki documentation, should really explain what a field is.