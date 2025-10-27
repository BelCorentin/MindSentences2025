# Dataset creation


Here is logged all the steps taken to generate the stim dataset as it is, also explaning the origin of the different versions (explained more in details in the other folder

Basically, we run a grid search (function in utils) to generate sets of sentences with different parameters (tense, numerosity, etc..).

Same for the controlled dataset, but with syntactic constraints.

Finally, we organize the final dataset to have overlapping controlled sentences between subjects, and different natural sentences.

TODO: reexpalin / copy paste previous explanations

Then we generate the audio: we add clicks at the beginning and end of each sound that we use as triggers.



