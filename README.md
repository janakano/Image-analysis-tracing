# Image-analysis-tracing

This macro will allow you to trace brain regions and measure the signal area within each brain region. Your images must be composed of 2 channels: 
+ A channel with a fluorescent signal that tags a specific neuron type (here, tyrosine hydroxylase to tag dopamine neurons)
+ A channel with the fluorescent signal you want to measure (here an injected green fluorescent protein)

## How to use

+ Put all pictures in a file called "_images"
+ Select the correct threshold for the second channel (the one that you want to measure) before running the macro
+ After running the macro, make sure all thresholds were appropriate in the "_masks" file. Remove any pictures from your analysis that had an inapropriate mask. 
***Note***
If too many images have to be removed, readjust your threshold and rerun the macro.
