# mcg_5_23_16_chandra_script
This is the script used to generate the plots for the manuscript "Detection of Asymmetry in the Narrow Fe Kα Emission Line in MCG-5-23-16 with Chandra". In this manuscript, the authors analyze the Fe Ka line in the X-ray bright AGN MCG-5-23-16.  

The script in this upload is in the form of a Jupyter Notebook and was used to generate the plots and model fit parameters referenced in the manuscript. The script assumes that you have already downloaded PyXspec, matplotlib, numpy, scipy, pandas, astropy, and statistics as Python packages in your environment. It also assumes that you have downloaded the 12 spectra of the AGN MCG-5-23-16 analyzed in this manuscript from https://doi.org/10.25574/cdc.186 and reduced the 12 spectra as described in the manuscript.  

Lastly, to get the script running, one needs to download the file xillver-a-Ec5.fits from https://sites.srl.caltech.edu/~javier/xillver/ and mytl_V000010nEp000H500_v00.fits from https://www.mytorus.com/ (select the "Zeroth-order continuum (etable version): mytorus_Ezero_v00.fits.gz" option on the Downloads page).
