![MASS-UBMATF](https://img.shields.io/badge/MASS--UBMATF-Computational_Astrobiology_2026-blue)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20680424.svg)](https://doi.org/10.5281/zenodo.20680424)


# Deep Learning Detection of Exoplanet Transits in PSLS-Simulated PLATO Light Curves

## Project Summary 
The aim of this project is to hunt for exoplanets (planets outside our solar system). Space telescopes look for these planets by staring at stars and waiting for a dip in brightness, a transit, that happens when a planet goes in front of the star. However, stars are not perfectly stable: they have sunspots, solar flares, and natural pulses that create a big amount of noise that can hide a small planet.

In this project 1000 realistic stars were simulated, with varying levels of noise and planetary transits to mimic the upcoming European Space Agency (ESA) PLATO mission, and then a Deep Learning Artificial Intelligence (a 1D Convolutional Neural Network) was built and trained to see if it could find the planets hidden in the static. The AI eventually learned to ignore the chaotic stellar flares and detected the hidden planets with high accuracy, outperforming the traditional mathematical methods (Box Least Squares).

## Instructions to Run
1. Ensure your Python environment has the necessary dependencies installed by running:
   `pip install -r requirements.txt`
2. Open the main Jupyter Notebook (`.ipynb` file).
3. In the top menu bar, select **Kernel** > **Restart & Run All** to execute the entire pipeline from data generation to the final evaluation plots.
