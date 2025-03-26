# Long Shor-Term Memory


A LSTM is usually used for sequntial data like financial time series data or something similar. I think the best way to learn something is build it yourself. So this is repository contains a `main.ipynb` file which includes a LSTM without a deep learning library. 

There are three primary components in an LSTM:
- Forget Gate - In this phase, you're using the current input and preivous short term memory to determine how much of the previous long-term memory you want to preserve.
- Input Gate - In this phase, you're essentially determining new long-term memory with the input and calculating how much of that new long-term memory you want to preserve. 
- Output Gate - In this phase, you're essentially determining the new short-term memory with the previous short-term memory and calculating how much of that new short-term memory you want to preserve by the ouput of the previous 2 phases (long-term memories). 

This is my very simple explanation of how an LSTM module works. Obviously a little bit more complicated than this but this explanation covers the main idea. 

Here's a good image of the architecture:

<img src="image.png" alt="image of lstm" width="525" height="300" />