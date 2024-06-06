# CCS Project

## Group members

Magnus L. Christensen, Andrea Bragante, Jarl-Sebastian Sørensen

## Description

This repo contains the Jupyter noteboooks used for the Computational Cognitive Sciences project, 2024, IT and Cognition.
We could not upload any parts of the dataset, so the analyses are supposed to be read-only if you do not have it.

The structure is as follows:

- `report.pdf` is the submitted research

- `videoselect.ipynb` is used to select videos in the dataset where speakers speak about the same amount of time+

- `prosody` contains the notebook used for run prosodic features analysis. The one uploaded runs the analysis with a window size of 3 minutes. To change it to 5 or 7 minutes, it is sufficient to set `WINDOW_SIZE = 5 * 60` or `WINDOW_SIZE = 7 * 60`. We assume a folder `videos` inside of this folder.

- `head-cue` contains four notebooks for running the analysis of head cues. The main part is approximately the first half of each document, whereafter a lot of exploration and other tests has been conducted, which wasn't used in the final iteration/analysis. `head_global.ipynb` is for `analysis 2`, while the rest is for the corresponding minute windows, and can be run without change (We assume a folder `videos` inside of this folder, and the necessary libraries installed).

- `lexical-entrainment.ipynb` contains the code used to run the lexical entrainment analysis. It consists of the 2 measures as described in the paper Kullback-Leibler and high-frequency words and using these measures the entrainment for the cas eof the first and second analysis.
