# comsol_parametric_sweep_data_analysis
Data analysis of the parametric sweep results from comsol

Here are some code I used to produce the figures in this paper:
https://www.mdpi.com/1424-8220/19/21/4772

The main tasks include:
1. split the parametric sweep data to a set of data array. Each array is a frequency response for one parameter point
2. Do a customized curve fitting for each frequency response to get the peak frequency, amplitude and quality factor of each frequency scan curve
3. Plot the extracted data
