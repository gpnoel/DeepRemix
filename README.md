# DeepRemix
## Remixing Music with Deep Learning

An interface in which you can give it a song, and a style for the song to be remixed in, and a LSTM neural network will remix it and output a remixed song.

For more information see [DeepRemix.com.](https://deepremix.com)

## Dependencies
* Python 2.7
* Keras
* Scipy
* Numpy
* PyDub (for input parsing)
* PyTest (for testing)

## Usage

Clone the repository, copy the song you'd like to remix into `./data/Music` and run

 `python scriptforparsingmusicgoeshere.py`

 Once the song has been put in an appopriate representational state, you can now run it through the neural network by running:

 `python scriptthatrunsnetworkgoeshere.py`

 This will save the output song into `./data/Output`

# Travis CI
## To test a build, do the following:

* Commit and push something to the repository...
