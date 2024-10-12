This project aims to create a digital audio workstation (DAW) using python from the ground up. 
Users can choose waveforms, envelopes, scales, rhythm, note lengths, key, and tempo in order to create unique songs.
Scale degrees, frequency, rhythm, and note lengths can be inputed as python lists or numpy arrays.

keyword:      parameter:         type:                 default value:

'F'           frequency          list/np.array         None; overrides 'D' if both are present
'R'           rhythm             list/np.array         One note per beat
'L'           note lengths       list/np.array         Notes each last one beat
'D'           scale degrees      list                  None
'scale'       scale              list                  Major (just 5-limit tuning)
'key'         key                float                 440 Hz
'tempo'       tempo              float                 120 bpm
'wav'         waveform           func [0,1)->[-1,1]    sine wave
