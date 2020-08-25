# TextGridsFromSilence

This script reduces some of the donkey work involved in preparing speech
data for analysis and processing.

It does the following:

1. Cleans up the recording by remove low-freqency noise.
2. Automatically chunks the recording into separate phrases / repetitions based on regions of silence (using "To Textgrid ( silences)" function).
3. Displays the automatic textgrid annotation to allow for manual correction of errors.
4. Automatically labels each area of non-silence with a prefix + number(e.g. YNQ_1, BEAG_1)
5. Prompts the user to correct any errors
6. Backs up previous version of files.
7. Saves Chopped up large sounds into "SmallFiles" directory.

Note, the "buffer" options in the menu refer to extra time which will be added to the beginning and end of each interaval or short sound file. This is to make sure that the beginning and ends of each target utterance are not accidentally truncated.

Note also, this is a draft version. It has no "memory" (i.e., it will not remember you previous menu choices)

### To do
1. Convert to plug-in format
2. Add "memory"
3. Add extra error handling  
4. Add better instructions!
