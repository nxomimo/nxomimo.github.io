---
title: "Program for Filtering Noise from Ice Sheet Radar Data"
excerpt: "*Applying signal processing techniques to boost signal-to-noise ratio in a data set.*<br/><img src='/images/102b.png' width='350'>"
collection: portfolio
---
## Overview
![POV](/images/spectrogram.png){: .align-center width="500"}

The final project in my Signal Proceessing and Linear Systems II class was to analyze a given data set of ice sheet radar scans and, using signal processing techniques taught in the class, filter out any noise that was impeding the radar return signal. The ultimate goal was to obtain a clear radargram of where the bed of the ice sheet lived, and to boost the signal-to-noise (SNR) ratio as much as possible. 

We were provided .scipy starter code that accessed the data, as well as displayed a corresponding spectrogram and radargram. My group focused on boosting the SNR ratio by implementing a dynamic band-stop filter that changed its bandstop frequency range with time, depending on where the heart of the noise lived. I also tried to implment a bandstop filter that dynamically adjusted its bandstop range depending on which frequencies displayed the greatest spectral densities at given moments in time, as these frequencies indicated high noise.

## Repository
If you'd like to access the project repository to observe our code, you can find it all [here](https://github.com/nxomimo/EE102B-Final-Project/tree/main). The final project report can also be accessed [here as a .pdf](/files/EE102BFinal.pdf).