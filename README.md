# Personal-Project-Repository

###### Updated: 29/04/2021

The Repository for my Individual Project!

## Project Scripts

- __downloadSequencedTrainingData.m__ - A MATLAB Function Script. Creates a `Dataset` directory with sub-directories for each class. Each class directory will be filled with `.csv` Data Points. The *Comma-Separated Values* files contain stock information for requested shares in a given time window. (*Uses Lenskiy's function for downloading the data from Yahoo Finance*).
- **createLSTM.m** - A MATLAB Function Script. Trains a *Long Short-Term Memory* Neural Network model from information stored in the `Dataset` directory.
- **calculateEarnings.m** - A MATLAB Function Script. Runs a simple simulation with the MATLAB NN model. Currently set up to trade for 3 months.
- **batchProcess.m** - A MATLAB Script. Runs the above 3 functions with varying parameters, enabling mass testing with a "hands-off" approach.

###### Deprecated Scripts

* __downloadTrainingData.m__ - Creates a _.csv_ file containing stock information for given shares in a given time period. (Uses Lenskiy's function that downloads the data from Yahoo)
* __createNeuralNetwork.m__ - Trains a basic Neural Network based on data provided from a _.csv_ file. (Based on the Matlab Example)

## Additional Documentation

- **Presentation.pptx** - Details the Project and Findings.


## Acknowledgements:

- [Artem Lensky](https://github.com/Lenskiy) for Creating [MATLAB Functions](https://github.com/Lenskiy/Yahoo-Quandl-Market-Data-Donwloader) that Enable Access to Yahoo Finance Information.