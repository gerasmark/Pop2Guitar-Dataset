# Pop2Guitar Dataset

A synchronized dataset of pop songs and their corresponding guitar covers for automatic guitar cover generation research.

## Overview

The Pop2Guitar dataset contains 40 pop songs paired with their corresponding guitar covers, totaling 2.52 hours of music. This dataset was created to explore guitar cover generation through domain adaptation techniques, extending automatic cover generation beyond piano-centric approaches.

## Dataset Statistics

- **Total pairs**: 40 song-guitar cover pairs
- **Duration**: 2.52 hours
- **Genre**: Primarily Western pop music
- **Split**: 90-10 (36 training pairs, 4 validation/test pairs)

## Metadata Format

Each track includes a YAML metadata file with:
- `uploader`: Channel/artist name
- `title`: Track title
- `youtube_id`: YouTube video identifier
- `duration`: Track length in seconds

## Usage

This dataset is designed for:
- Guitar cover generation research
- Cross-instrument domain adaptation studies
- Music information retrieval tasks
- Evaluation of automatic music arrangement systems