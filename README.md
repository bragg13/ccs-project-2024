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
