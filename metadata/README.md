# Metadata


Here, we show how we generated the metadata for the dataset, which for now just includes creating the word timings from the sentences and the audio (that has been generated as explained in the other folder

For this, we use WebMAUS, to which we give the audio and the text and it automatically extracts the word onsets.

The code is located in generate\_words.ipynb where we do the API calls, and the logic of extracting the TextGrids generated into a dataframe 
