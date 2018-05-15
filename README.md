# Music-Generation
## Music generation project using recurrent neural networks (RNN)

Download the MIDI tar file from [this link](https://github.com/IraKorshunova/folk-rnn/tree/master/data) and put it in the folder named "chorpus" at the same level of this notebook. Those were the files that we used to train and test the neural network.

All the files provided can be computed from the notebook but might take some times (e.g. around 10 hours to train one GRU model), so we saved the best models such that you can load it directly in the notebook.

Although, two files are missing: pitches.pkl and durations.pkl that you'll have to compute from the notebook (in part 4). Don't worry, the content of these missing files are fast to compute and they were not included on Git because of their sizes (700 Mo for pitches.pkl).

Have fun improving our neural network and creating your own melodies :)