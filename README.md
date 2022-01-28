# blocksearch-iccprt

This script can be used to search a particular block/parameter of a block from all the compounds of a Schneider Foxboro DCS. Here, ICCPRT is used as the source of our database. Each ICCPRT file of a Control Processor (CP) is exported as a worksheet in one single excel file. For example, if there are 10 CP's in the network, each CP will have its ICCPRT worksheet. 

In [convertData.ipynb](https://github.com/faseelmo/blocksearch-iccprt/blob/main/convertData.ipynb), each block information is extracted from the excel database and arranged in a pandas DataFrame.  

The above DataFrame needs to be saved as a csv file to run [search.ipynb](https://github.com/faseelmo/blocksearch-iccprt/blob/main/search.ipynb). 
