# JAMUNET: PREDICTING THE MORPHOLOGICAL CHANGES OF BRAIDED SAND-BED RIVERS WITH DEEP LEARNING

$${\color{red}{}}$$

🔴 Attention! 🔴
\
*The public repository is under development. The data, code and necessary documents will be available soon. For any information you can contact me at **antonio.magherini@gmail.com**.* 

This repository stores the data, files, code and other documents necessary for the completion of the Master thesis of [Antonio Magherini](https://nl.linkedin.com/in/antonio-magherini-4349b2229), student of the MSc Civil Engineering program - Hydraulic Engineering track, with a specialization in River Engineering 
at the [Faculty of Civil Engineering and Geosciences](https://www.tudelft.nl/citg) of Delft University of Technology (TU Delft).
\
The thesis was developed in collaboration with [Deltares](https://www.deltares.nl/en). The report can be found on [TU Delft repository](https://repository.tudelft.nl/record/uuid:38ea0798-dd3d-4be2-b937-b80621957348).

The thesis committee of this project is composed of Dr. Riccardo Taormina (Committee chairman, TU Delft), Dr. ir. Erik Mosselman (Main supervisor, Deltares & TU Delft), and Dr. Víctor Chavarrías (Supervisor, Deltares).

For any information, feel free to contact the author at the following email addresses:
<ol>
  <li>antonio.magherini@gmail.com (private account, recommended).</li>
  <li>Antonio.Magherini@deltares.nl (institute account, will stop to exist after the graduation)</li>
  <li>A.Magherini@student.tudelft.nl (student account, will stop to exist after the graduation);</li>
</ol>

The structure of this repository is the following:
- <code>benchmarks</code>, contains modules and notebooks of the benhcmark models used for comparison;
- <code>data</code>, contains raw data (hydraulic data, data from [Jagers (2003)](https://research.utwente.nl/en/publications/modelling-planform-changes-of-braided-rivers), satellite images);
- <code>images</code>, contains the images shown in the thesis report and other documents;
- <code>model</code>, contains the modules and noteboooks with the deep-learning model;
- <code>other</code>, contains documents, images, and other files used during the project;
- <code>postprocessing</code>, contains the modules used for the postprocessing of the data;
- <code>preliminary</code>, contains the notebooks with the preliminary data analysis, satellite images preprocessing and visualization, satellite image preprocessing and other examples;
- <code>preprocessing</code>, contains the modules used for the preprocessing of the data.

The file <code>braided.yml</code> is the environment file with all dependencies, needed to run all the notebooks.

<p align="center" style="margin-top: 1px;">
    <!-- <img src="images\jamuna_narrow_.png" alt>  -->
    <img src=".\images\1994-01-25.png" width="500"> 
</p>

<p align="center">
    <!-- <em>Jamuna River. Image taken from <a href="https://earth.google.com/web/@24.90919263,90.84277199,340.42882201a,979110.75147048d,35y,-0h,0t,0r/data=OgMKATA">Google Earth</a></em> -->
    <em>Brahmaputra-Jamuna River at the border between India and Bangladesh. The image was retrieved<br>from <a href="https://earthengine.google.com/">Google Earth Engine</a> <a href="https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LT05_C02_T1_L2">USGS Landsat 5 collection</a>. The image was taken on January 25, 1994.</em>
</p>
