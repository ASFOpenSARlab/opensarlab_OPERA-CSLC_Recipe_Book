<div style="display: flex; align-items: center;">
    <img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/logos/ASF_logo.svg" alt="ASF logo" style="width: 15%; margin-right: 10px;"/>
    <img src="https://asf.alaska.edu/wp-content/uploads/2023/10/OPERA-logo.png" alt="ASF logo" style="width: 15%;"/>
</div>


# Start Here

## opensarlab_OPERA-CSLC_Recipe_Book

**The OPERA project at the Jet Propulsion Laboratory produces analysis-ready datasets from space-borne synthetic aperture radar (SAR) and optical sensors.**

This Jupyter Book provides data recipes demonstrating data access, analyses, and data transformations using the OPERA CSLC-S1 product.

>"The Coregistered Single-look Complex (CSLC) product consists of SLC images that are precisely aligned or “coregistered” to a pre-defined UTM/Polar stereographic map projection systems. The CSLC images contain both amplitude and phase information of the complex radar return. The amplitude is primarily determined by ground surface properties (e.g., terrain slope, surface roughness, and physical properties), and phase primarily represents the distance between the radar and ground targets corrected for the geometrical distance between the two based on the knowledge from Digital Elevation Model and platform’s position, i.e., the CSLC phase represents residual geometrical distance between the sensor and target, the atmospheric propagation delay and the target movements. The Level-2 CSLC product is derived from the Sentinel-1 radar observations and is provided in the Hierarchical Data Format version 5 (HDF5) file format. The CSLC product will be posted at 5x10 m spacing in east and north direction, respectively. The CSLC product also serves as the basis for the OPERA Displacement (DISP) product. The product will be accessible through the Alaska Satellite Facility Distributed Active Archive Center (ASF DAAC)."
>
>[https://www.jpl.nasa.gov/go/opera/products/cslc-product-suite](cslc-product-suite)

<br>
<div class="alert alert-success">
<font face="Calibri" size="5"><b><font color='rgba(200,0,0,0.2)'> <u>Jupyter Book Navigation</u></font></b></font>

<font face="Calibri" size="3">For an improved Jupyter Book Experience in JupyterLab, try installing the [jupyterlab-jupyterbook-navigation](https://pypi.org/project/jupyterlab-jupyterbook-navigation/) JupyterLab extension.
</font>
</div>

<img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/notebook_images/jlab_toc.gif" alt="jupyterlab-jupyterbook-navigation demo gif]" width="75%"/>

## How To Use This Jupyter Book

>1. ### Install the software environment needed to run the notebooks
>
>    - Run the **Install Required Software with Conda** notebook ([OPERA_CSLC_jupyter_book_env.ipynb](software_environments/OPERA_CSLC_jupyter_book_env.ipynb))
>    - Rerun this step periodically. Updates to environment config files will not take effect unless you update or recreate your environment.
>
>1. ### Explore data access notebooks
>    - [Direct S3 Access](data_access/OPERA_S3_Access.ipynb)
>    - [Download Data](data_access/search_download_OPERA-CSLC-S1.ipynb)
>
>1. ### Create interferograms
>    - [Calculate and multilook interferograms from OPERA S1-CSLCs](insar_generation/ASF_OPERA_CSLC_2_IFG.ipynb)

## Contact Us

<div class="alert alert-info" style="display: flex; align-items: center; font-family: 'Times New Roman', Times, serif; background-color: #d1ecf1;">
  <div style="display: flex; align-items: center; width: 10%;">
    <a href="https://github.com/ASFOpenSARlab/opensarlab_OPERA-CSLC_Recipe_Book/issues">
      <img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/logos/github_issues.png" alt="GitHub logo over the word Issues" style="width: 100%;">
    </a>
  </div>
  <div style="width: 95%;">
    <b>Did you find a bug? Do you have a feature request?</b>
    <br/>
    Explore GitHub Issues on this Jupyter Book's GitHub repository. Find solutions, add to the discussion, or start a new bug report or feature request: <a href="https://github.com/ASFOpenSARlab/opensarlab_OPERA-CSLC_Recipe_Book/issues">opensarlab_OPERA-CSLC_Recipe_Book Issues</a>
  </div>
</div>

<div class="alert alert-info" style="display: flex; align-items: center; justify-content: space-between; font-family: 'Times New Roman', Times, serif; background-color: #d1ecf1;">
  <div style="display: flex; align-items: center; width: 10%; margin-right: 10px;">
    <a href="mailto:uso@asf.alaska.edu">
      <img src="https://opensarlab-docs.asf.alaska.edu/opensarlab-notebook-assets/logos/ASF_support_logo.png" alt="ASF logo" style="width: 100%">
    </a>
  </div>
  <div style="width: 95%;">
    <b>Have a question related to SAR, OPERA CSLCs, or ASF data access?</b>
    <br/>
    Contact ASF User Support: <a href="mailto:uso@asf.alaska.edu">uso@asf.alaska.edu</a>
  </div>
</div>


