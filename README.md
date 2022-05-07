# nn_synth_patch
 
This is This is a combination of cross feedback and concatenative synthesizers in one performance environment. This patch was the first of many that came from my time learning the flucomatoolkit for Max. That time, in combination with inspiration from Sam Pluta, lead me down the path of creating this performance patch. Each synth in the patch is a continuation of the example patches from the flucoma documentation. In this patch, each instrument interface allows for the player to load predetermined training data for each neural network. A easy way to think about it, you can design many "presets" that are drastically different from one another. Then you can quickly switch between them to explore all the possibilities of the synth. You also have the ability to step in and override any parameter in the environment and control it while everything else morphs around it. The end result is a very expressive and fun instrument that I recommend trying out for yourself. The majority of the audio processing is being handled by objects from Rodrigo Constanzo's confetti. They have been edited to send and receive float values for each corresponding parameter.

Dependencies:
    Fluid Manipulation Toolkit (FluCoMa) - https://www.flucoma.org/download/
    CNMAT External Objects for Max & MSP - https://cnmat.berkeley.edu/downloads
    ml-lib Machine Learning Library for Max and Pure Data - https://github.com/irllabs/ml-lib
    Max for Live - https://www.ableton.com/en/shop/#max-for-live
    confetti - Rodrigo Constanzo - https://rodrigoconstanzo.com/confetti/ 
