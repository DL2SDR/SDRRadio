# SDR Radio for macOS X

This application is compatible with SDR frontend hardware which is available as
audio device (Softrock, Funcube Dongle, Funcube Dongle Pro, Funcube Dongle Pro+, Lima SDR, FiFi SDR and many more).
It is NOT compatible with RTL chip based SDR frontends.

To set up SDR Radio open the Audio Devices window and select an Audio Device for Input and Output.
Depending on your hardware setup it may be useful to make an "Aggregate Device" first.
You can do this by launching the "Audio Midi Setup", which you can find in the Application/Utilities folder.
You have to set all used Audio Devices at the same (and highest) sample rate.
Then open the Configurations window and add one (for Rx only) or two (for Rx and Tx operation) Configurations.
Make one a Rx and one a Tx configuration and make them active. Select the corresponding channels for the I and Q signals and for the Sidetone. The Sidetone is the sound you hear when you hit the morse key.
If the setup was done correctly you can use the GUI window to operate your software transceiver!