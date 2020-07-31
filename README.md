# web-scraping-immobilienscout24

A jupyter notebook to extract latest real estate rents from "Immobilienscout24" and display the information on a city map by district, here Stuttgart ("Stuttgart_Mieten.html"). 
The poloygon layers of the districts originate from the homepage of Stuttgart ("KLGL_Stadtplanbasis.gdb"). The data can be processed with the library "geopandas". 
Unfortunately it's a pain to install the library, more precisely its dependencies. The following guide should resolve the issues.

## installing geopandas using anaconda
1. `conda install -c conda-forge geopandas`
2. `conda install pip`
3. `pip uninstall pyproj`
4. `pip install --force-reinstall pyproj`
