# SyncToolbox

This repository contains a Python package called Sync Toolbox, which provides open-source reference implementations for full-fledged music synchronization pipelines and yields state-of-the-art alignment results for a wide range of Western music. 

Using suitable feature representations and cost measures, the toolbox's core technology is based on dynamic time warping (DTW), which brings the feature sequences into temporal correspondence. To account for efficiency, robustness and, accuracy, our toolbox integrates and combines techniques such as multiscale DTW (MsDTW), memory-restricted MsDTW (MrMsDTW), and high-resolution music synchronization.

## Usage

Fully worked examples for using the sync toolbox are provided in the accompanying Jupyter notebook. In ``sync_audio_audio_simple.ipynb``, we show how to use the toolbox to synchronize two recordings of the same piece of music using standard chroma features. We also compare runtimes for standard DTW and MrMsDTW. In ``sync_audio_audio_full.ipynb``, we expand this example and demonstrate how to build a full synchronization pipeline that yields state-of-the-art results. Finally, ``sync_audio_score_full.ipynb`` shows a similar pipeline for synchronizing a music recording with the corresponding score.

There is also an API documentation for the Sync Toolbox:

https://meinardmueller.github.io/synctoolbox

## Installing

You can install the Sync Toolbox using the Python package manager pip:

```
pip install synctoolbox
```

## Contributing

We are happy for suggestions and contributions. However, to facilitate the synchronization, we would be grateful for either directly contacting us via email (meinard.mueller@audiolabs-erlangen.de) or for creating an issue in our Github repository. Please do not submit a pull request without prior consultation with us.

## Acknowledgements

The synctoolbox package builds on results, material, and insights that have been obtained in close collaboration with different people. We would like to express our gratitude to former and current students, collaborators, and colleagues who have influenced and supported us in creating this package, including Vlora Arifi-Müller, Michael Clausen, Sebastian Ewert, Christian Fremerey, and Frank Kurth. The main authors of Sync Toolbox are associated with the International Audio Laboratories Erlangen, which are a joint institution of the Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU) and Fraunhofer Institute for Integrated Circuits IIS. We also thank the German Research Foundation (DFG) for various research grants that allowed us for conducting fundamental research in music processing (in particular, MU 2686/7-2, DFG-MU 2686/14-1).