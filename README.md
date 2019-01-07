# LiveCode Library for General MIDI(GM) & General Standard(GS) Names and Numbers
LiveCode Builder Lib of General MIDI Utilities

I've started this LiveCode builder library for General MIDI Utilities. Right now it only contains functions for converting some MIDI Numbers (0-127) into human readable names. I intend to expand it in the near furture.

# So far there are functions for:

Note Names with Sharps Only for "Keyboard Black Keys notes" (GM Standard: C4=60 C-1=0 vs Yamaha XG C3=60 C-2=0)

Note Names with Flats Only for "Keyboard Black Keys notes" (GM Db4=61 vs sharps only C#4=61)

Coming Soon: Note Names with slash delimited Flats/Sharps "Keyboard Black Keys notes" (Db4/C#4=61)

GM2/GS standard Instrument Names

GM2/GS Standard DrumKit Names

DrumKit Drum Note Names (GM/GS standard kit only, I will add other GM2/GS kit variations in the future)

Standard Controllers / Channel Mode Message Names

# NOTE:
MIDI has no real flats or sharps, nor does most keyboard instrument tuning (since the harpsichord was invented?). In modern times you would probably need a fretless type string instrument (and superhuman pitch detection skill to actually know) to play the diffence between a sharp or a flat. The frequencies produced are actually somewhere between sharp and flat. MIDI (and Keyboard instrument tuning way before that) protocols was designed that way back in the early 1980s. One could acheive the proper frequencies using MIDI pitchbend messages.
