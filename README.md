# custom_audio_dataset
At this repository the one can find custom audio dataset of following noise classes: vehicle noise, industrial noise, big engine noise, background noise, silence.

# Background
The dataset presented in this repository was recorded, processed and created as part of the ["Smart City and Critical Infrastructure Protection Technologies ISC2PT II"](https://www.etis.ee/Portal/Projects/Display/96569b7f-a42a-422f-bd8f-97cbb3a483b1?lang=ENG) project. This dataset has the potential for further use to train a neural network on SiLabs Mighty Gecko EFR32MG12 microcontroller.

# Dataset description
Initial aim of creating dataset was to creation of noise pollution classes consisting of man-made noise and road/traffic noise that have the same frequency characteristics as further equipment (8000Hz).

# Used processing methods


# Data collection procedure
The noise recording sessions took place from July 15, 2021 to September 14, 2021 to collect noise data for the "industrial noise" and "road noise" classes. The sound recording procedure was carried out using a SiLabs Mighty Gecko EFR32MG12 microcontroller and Knowles SPU0410HR5H-1 microphone with a signal output to a computer. 
For recording, a ready-made program written in the Java Script language, launched from the console, was used. The program is based on recording values read from an analog-to-digital converter or ADC using the UART protocol. Thus, the process of sequential creation of text files containing information about the sound of the required duration (should be given as an program input parameter) takes place.
A total of 4 recording series were produced, 3 of which for the purpose of recording road sound and one for recording construction noise. At the end of the recording, 4548 sound files each 3 second long were received, requiring further sorting. 
