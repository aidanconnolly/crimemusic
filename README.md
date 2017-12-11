# crimemusic
In an effort to explore other methods of data visualization (or in this case data sonification), the goal of this project was to create a program that could turn University of Nebraska-Lincoln Police Department crime data into music, or at least sound.

The data was taken from the [UNLPD Daily Crime and Fire Log](https://scsapps.unl.edu/policereports/MainPage.aspx), which contains data back to 2005. The program was written in Python, using Chris Groskopf’s [agate](https://github.com/wireservice/agate) library and a modified version of the Center for Investigative Reporting’s [MIDITime](https://github.com/cirlabs/miditime) library.

The program offers three main functions: allcrime\_onemonth(), samecrime\_twomonths() and onecrime\_allmonths(). 

### allcrime_onemonth()
This will take all the crime events from a specified month and turn them into a MIDI file, with each crime in a separate track.

### samecrime_twomonths()
This will take two specified months, present the common crime types and create a MIDI file for a selected crime type with each month in a different track.

### onecrime_allmonths()
This will show the crime types present in the dataset and create a MIDI file for all instances of a selected crime type.

