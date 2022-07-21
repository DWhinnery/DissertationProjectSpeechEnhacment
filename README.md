# DissertationProjectSpeechEnhacment
This was my final year project which I used fast Fourier transform algorithm in order to convert a .WAV file into its spectral representation. After which spectral analysis takes place where an average of the magnitude of the wave is taken during the first 20 frames where there is only background noise, the average is taken away from every frame reducing the amount of unwanted background noise. The wave is then converted back into a .WAV file and outputted with cleaner speech. 

The focus of this project is speech enhancement, more specifically to use spectral analysis to
accomplish speech enhancement for a sound file. This system allows the user to choose a .wav file,
convert it into it's spectral representation, and then apply spectral subtraction to produce cleaner 
speech with reduced noise relative to the input .wav file.

