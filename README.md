# Predicting Financial Markets with Machine Learning

### Individual Project Preparation/Realisation (*305AAE*/*306AAE*)

#### Computer Hardware and Software Engineering Final Project

#### at Coventry University

## 📄 Documentation

- [`Final_Project_Dissertation.pdf`](/Final_Project_Dissertation.pdf) - **My Dissertation detailing the entirety of the project.**
- [`Final_Project_Presentation.pdf`](/Final_Project_Presentation.pdf) - **Presentation that presents a short overview of the project.**
- [`Literature_Table.xlsx`](/Additional%20Documentation/Literature_Table.xlsx) - **A *Microsoft Excel* Table containing the sources used for Literature Review.**
- [`Project_Notebook.url`](/Additional%20Documentation/Project_Notebook.url) - **A Link to a *Microsoft OneNote* Notebook containing the project Logbook & other notes.**
- [`Individual_Project_Tests.xlsx`](/Additional%20Documentation/Individual_Project_Tests.xlsx) - **A *Microsoft Excel* Spreadsheet containing a log of the projects Tests with Parameters and Outcomes.**

## 📌 Noteworthy Files

- [`downloadSequencedTrainingData.m`](/Project%20Scripts/downloadSequencedTrainingData.m) - A MATLAB Function Script. Creates a `Dataset` directory with sub-directories for each class. Each class directory will be filled with `.csv` Data Points. The *Comma-Separated Values* files contain stock information for requested shares in a given time window. (*Uses Lenskiy's function for downloading the data from Yahoo Finance*).
- [`createLSTM.m`](/Project%20Scripts/createLSTM.m) - A MATLAB Function Script. Trains a *Long Short-Term Memory* Neural Network model from information stored in the `Dataset` directory.
- [`calculateEarnings.m`](/Project%20Scripts/calculateEarnings.m) - A MATLAB Function Script. Runs a simple simulation with the MATLAB NN model. Currently set up to trade for 3 months.
- [`batchProcess.m`](/Project%20Scripts/batchProcess.m) - A MATLAB Script. Runs the above 3 functions with varying parameters, enabling mass testing with a "hands-off" approach.


## ⭐️ Acknowledgements

- [Artem Lensky](https://github.com/Lenskiy) for Creating [MATLAB Functions](https://github.com/Lenskiy/Yahoo-Quandl-Market-Data-Donwloader) that Enable Access to *Yahoo Finance* Information.

