# openslava-vub-fraud-workshop
Fraud detection and geoanalytics use cases on customer payment transactions

## Presentation
 * [presentation](https://isp-vub.github.io/openslava-vub-fraud-workshop/presentation.html)

## Visualizations:
 * [choropleth](https://isp-vub.github.io/openslava-vub-fraud-workshop/geovis-choropleth.html)
 * [timeslider choropleth](https://isp-vub.github.io/openslava-vub-fraud-workshop/geovis-timechoropleth.html)

## Prerequisites:

Download the latest version [MiniForge](https://github.com/conda-forge/miniforge) (add python to classpath checkbox).

We recommend using a virtual environment (conda) to avoid conflicts with other software on your device.

```bash
conda create --name openslava-fraud python=3.7
conda activate openslava-fraud
conda install -c conda-forge tensorflow
conda install -c conda-forge jupyterlab pandas pyarrow scikit-learn pyod geopandas folium descartes python-graphviz openpyxl pydot
pip install sdv

jupyter notebook
```

## Contact:
  * Anton Kovaľ - akoval@vub.sk
  * Jakub Červeň - jcerven1@vub.sk
