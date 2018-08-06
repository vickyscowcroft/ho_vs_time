## H0 vs time jupyter notebook

Jupyter notebook to make plots of H0 vs publication date for Cepheids and CMB modelling.

Pink and blue regions indicate the **unweighted** means and their uncertainties for each method. See [Beaton et al. 2016](https://ui.adsabs.harvard.edu/#abs/2016ApJ...832..210B/abstract) Figure 1 and text for an explanation. 

* Data are read in from the h0_table.csv file. 
* Format is Shortname, Method, Specific_Technique, Value, +err, -err, Author year ref, month 
  - Shortname = whatever you want
  - Technique = Cepheid, CMB, etc
  - Specific_Technique = For when there are multiple H0 values in a given paper, and you want to remember which one you've picked.
  - Value = H0 value
  - +err = Upper error bar
  - -err = Lower error bar
  - Author year ref = ApJ Style reference, e.g. Beaton et al. (2016)
  - Month = Month **number** of publication, i.e. Jan = 1, Feb = 2, so it can put the value in the right place in the figure.
 
 
