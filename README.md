# community.livecode.library.GMIDILib
LiveCode Builder Lib of General MIDI Utilities

I've started this LiveCode builder library for General MIDI Utilities. Right now it only contains functions for converting some MIDI Numbers (0-127) into human readable names. I intend to expand it in the near furture. 

For one thing there are no flats used for note names. MIDI has no real flats or sharps, nor does most keyboard instrument tuning (since the harpsichord was invented?). In modern times you would probably need a fretless type string instrument to actually the diffence between sharp of flat. The frequencies produced are actually somewhere between sharp and flat and for convenience MIDI was designed that as well when the protocol was created back in the early 1980s.

So far there are functions for:

Note Names (GM C4=60 C-1=0 vs Yamaha C3=60 C-2=0)

GM2/GS standard Instrument Names

GM2/GS Standard DrumKit Names

DrumKit Drum Note Names (GM2/GS standard kit, I will add other GM2/GS kit variations in the future)

Standard Controllers / Channel Mode Message Names
