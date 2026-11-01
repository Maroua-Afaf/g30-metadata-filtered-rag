# G30: Metadata-Filtered RAG for Image Captioning

Mini project, image processing. Group G30.

## What this project does
We build a system that writes captions for photos. Before writing, it searches a
library of 10,000 COCO photos and uses the captions of the most similar ones as
hints (RAG). Our technique filters the library by the objects found in the photo.

## Team
(each member adds one line, see the team folder)

## Folder structure
- notebooks/: Colab notebooks
- data/splits/: frozen ID files and cleaning report
- outputs/figures/: charts
- big files (photos, embeddings, FAISS index) are stored on our shared Drive

## Settings
Random seed: 42

## Status
Phase 1 (data exploration and preprocessing): in progress
