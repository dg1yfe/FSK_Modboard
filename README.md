# FSK_Modboard
A little amplifier board for Demodulator &amp; Modulator access in Motorola MC micro transceivers 

The board provides uses a dual OP-Amp to do the following:

1) Transmit Path
   - Provide an external input for direct (wide-band) modulator access
   - Amplify the signal supplied via the external input by a factor of 2.7
   - Add microphone audio signal and (amplified) external signal and route the mix to the modulator
     (be sure to disconnect or mute your microphone when using the external input)
 
2) Receive Path
   - Pick-up the demodulated signal right after the demodulator and amplify it by 10
   - Provide the amplified signal (amplitude about ~500 mV) at an external output
   
