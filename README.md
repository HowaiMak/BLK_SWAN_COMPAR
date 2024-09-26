# BLK_SWAN_COMPAR
Black Swan Indicators Comparison
## Outline
This notebook compares some of the existing Black Swan detectors in market crashes. The shown grpahs here are during the Financial Crisis of 2008.
Comparing different detected Black Swan periods might help decision making in the qunatitative world, especially during unexpected market trends.

### Current Existing Models (in this repository):
1. Z-score based on daily returns (from stats library)
3. Percentile-based threshold (similar idea to z-score)
3. Price deviation over moving average standard deviation

It is welcomed to download and play around with the settings and threshold to explore for insights.
Please feel free to suggest any Black Swan model that is not included. I will try and update it asap.

## Testing and Implementing
All referencing models are coded in ipython. Idealy this should be run or either python, or even better C++. The choice of Jupyter Notebook is simply for demonstrating purposes and readability.

For those who wish to run the code in python instead of ipython, please copy the code into a .py files first. After that import the library "os" in order to read and extract your current working directory (or the Excel files directory) to read the .csv files. Alternative way can be done manually by inputting the directory address into the code at the beginning. Commencing the program shall be done via the terminal (cmd) by calling "python script_name.py". If potential error appears please run in administrative mode, or check the executable of the .py file
