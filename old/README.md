#ejam

current state: draft

ejam allow you to create session to play music on the internet via the MIDI music protocol.

Every peer in the session play directly with all the others.

ejam use MIDI to send message over the internet, so it need a MIDI input device to connect with.

MIDI is a protocol to code music like in a score.
Not all instrument sounds are easy to convert into MIDI.

* virtual instruments to play midi exists

* Synthetizer and electric drums mostly have a midi output.

* Other electric instrument such as guitar, bass,
  electric violin etc... can be converted in real time.
  I don't know if the convertion is rapid enough.

* voice, and other intrument cannot be converted as far as I know.

ejam also need a soundfont to play MIDI (MIDI just encode note and effect)

Some are provided but it is possible to upload your own while creating a session


It use miditip to spread midi message on the network quickly while being able to resolve packet loss

