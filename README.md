# Star Classification with Machine Learning

## Overview

This project focuses on the classification of astronomical objects using data from the Sloan Digital Sky Survey (SDSS).

The goal is to build predictive models capable of classifying celestial objects into three categories:

- Galaxy
- Star
- Quasar

The classification is based on spectral and photometric features observed by SDSS.

## Goal

The main objective is to compare different classification methods and identify the model that best generalizes to unseen astronomical observations.

The analysis focuses on:

- understanding the structure of the SDSS dataset
- identifying relevant astronomical features
- preprocessing the data
- comparing machine learning classifiers
- evaluating model performance
- interpreting which variables contribute most to classification

## Dataset

The dataset contains astronomical observations collected by the Sloan Digital Sky Survey.

The main groups of variables include:

### Identification variables

Examples include:

- `obj_ID`
- `spec_obj_ID`
- `run_ID`
- `cam_col`
- `field_ID`
- `plate`
- `MJD`
- `fiber_ID`

These variables identify the astronomical object, the observation, or the instrument configuration.

### Spatial coordinates

- `alpha`: right ascension
- `delta`: declination

These variables describe the position of the object on the celestial sphere.

### Photometric filters

- `u`: near-ultraviolet band
- `g`: green band
- `r`: red band
- `i`: near-infrared band
- `z`: infrared band

These variables measure the brightness of the object in different wavelength bands.

### Redshift

- `redshift`: measures the shift in wavelength of light emitted by the object

Redshift is particularly useful for distinguishing distant astronomical objects such as galaxies and quasars.

### Target variable

- `class`: object category

The target variable contains three possible classes:

- Galaxy
- Star
- Quasar

## Methods

The project considers several classification approaches:

- Linear Discriminant Analysis
- Quadratic Discriminant Analysis
- K-Nearest Neighbors
- Decision Trees
- Model comparison using train/test/validation splits

## Authors
- Anna Ciapparelli
- Clelia Meloni
- Tommaso Roncaglio
