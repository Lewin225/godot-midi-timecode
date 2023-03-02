Project to implement missing MIDI messages in godotengine 

*MIDI_MESSAGE_SYSTEM_EXCLUSIVE = 240*

MIDI system exclusive message. This has behavior exclusive to the device you're receiving input from. Getting this data is not implemented in Godot.

*MIDI_MESSAGE_QUARTER_FRAME = 241*

MIDI quarter frame message. Contains timing information that is used to synchronize MIDI devices. Getting this data is not implemented in Godot.

*MIDI_MESSAGE_SONG_POSITION_POINTER = 242*

MIDI song position pointer message. Gives the number of 16th notes since the start of the song. Getting this data is not implemented in Godot.

*MIDI_MESSAGE_SONG_SELECT = 243*

MIDI song select message. Specifies which sequence or song is to be played. Getting this data is not implemented in Godot.
