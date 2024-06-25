# BCHJam

Root repository of the **_BCHJam_** project.  
**_BCHJam_** that won the 1st place in the 2024 [br41n.io](https://www.br41n.io/) for the category BCI Programming & Arts.
**_BCHJam_** is a BCMI for Live Music Performance in Shared Mixed Reality Environments.
Thanks to its distributed OSC components it allows networked music performance according to the Internet of Musical Things paradigm.

[<img src="https://github.com/BRomans/BCHJam/bchjamdemo.png" width="75%" >](https://drive.google.com/open?id=1RQcWFBTibWkZL6v_cuhEFP-T4ZM4Qv7w&usp=drive_fs)

## Architecture
**_BCHJam_** features a distributed architecture that communicates over the network using the Open Sound Control (OSC) protocol.
![architecture]([http://url/to/img.png](https://github.com/BRomans/BCHJam/bch-schema.drawio.pdf))
The musician is represented on the left, with both their instrument and their BCI device. The signals from the BCI
are streamed via Bluetooth and processed by a computer running the BCI-console, where active and passive signal processing is performed. Signals from the
active BCI selection of targets are sent via the OSC protocol over Wi-Fi to a DAW running a number of virtual audio effects. The audio signal from the
musician’s instrument is also sent to the DAW for processing. Passive BCI signals (alpha and beta waves) are sent to both the DAW and one or more XR
headsets, worn by audience members. Finally, the audio reaches the audience member either through acoustic propagation from a set of speakers (in the case
of a co-located performance) or through an audio transmission system over the network (for remote performances).

## Awards

[<img src="https://github.com/BRomans/BCHReaperOSC/assets/23708296/bbe2ecca-6689-49b7-b484-8d6287cb2774" width="45%" >]([https://www.youtube.com/live/Gvx00c3obz0?si=iE1wbVgK_octDKxP&t=21693](https://www.youtube.com/live/Gvx00c3obz0?si=OuJIG-r6ZcV2c6XE&t=15624))

https://www.youtube.com/live/Gvx00c3obz0?si=OuJIG-r6ZcV2c6XE&t=15624

[<img src="https://github.com/BRomans/BCHReaperOSC/assets/23708296/8df36e46-44c1-4e47-b6f3-e177221300c3" width="45%" >](https://www.youtube.com/live/Gvx00c3obz0?si=iE1wbVgK_octDKxP&t=21693)

https://www.youtube.com/live/Gvx00c3obz0?si=2BEH6Bxqbo8EHCO-&t=21693

<img src="https://github.com/BRomans/BCHReaperOSC/assets/23708296/db012531-cb59-403c-8a80-fb466fea2fea" width="40%">



## Repository Content

This repository contains the control interface developed in Unity.

The project depends on the _Unicorn Unity Interface_ to build the Brain-Computer Interface commands and data stream.

Finally, we used Open Sound Control (OSC) to communicate between the BCI and the audio effects.  The OSC property senders can be customized and redirected to multiple receivers.

The project is tested on Unity 2022.3.xx

**CIMIL Underground Team, 2024**  
_Alberto Boem_  
_Gregorio Andrea Giudici_   
_Michele Romani_  
_Domenico Stefani_  
_Devis Zanoni_  
