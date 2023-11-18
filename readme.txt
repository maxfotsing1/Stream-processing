Batch Processing (Task1_readFile): download, clean and uniformize data, create a function to evaluate the 
correlation coefficient between to devices and find the 5 ost correlated pairs of devices. 

Consumer (Stream processing - Producer):The producer is responsible for sending real-time data 
(information from various sensors) to a server for a given time period

Receiver (Stream Processing - receiver):The receiver receives the data transmitted by the producer. 
It analyzes this data and performs various transformations and calculations. This includes the calculation of 
the Pearson correlation coefficient between the different sensors.

Sliding windows : Architecturally, the code uses the PySpark library to analyse a real-time stream of bicycle
count data in Brussels. The code implements a sliding window to process the data, which is a common way of 
analysing stream data in real-time processing