
# ECG Signal Analysis using Python



This is a Python code that analyzes electrocardiogram (ECG) signals obtained from a dataset in CSV format. The code utilizes various libraries such as pandas, numpy, scipy, and matplotlib, among others. Additionally, it installs and imports the "heartpy" packages for easier data handling and processing.




After successfully installing the required packages, you can run the code and follow the prompts to analyze the ECG signal. The code reads the dataset using pandas and applies a low-pass filter to filter the ECG signal. It then applies various algorithms for processing the filtered signal to extract the peaks and calculate the RR intervals. These algorithms include filtering, smoothing, and peak detection. The code also computes various statistics on the RR intervals such as mean RR, standard deviation RR, mean HR, and maximum HR, among others.

Finally, the code divides the RR intervals into separate sections, each corresponding to a single activity, and computes the statistics separately for each section. The results are displayed in tabular form for easier analysis.



## Appendix
You can find a part of the report of this project in the repository, which includes a detailed analysis of the ECG signal processing algorithms used in the code and their performance evaluation.
