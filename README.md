# DCVC-DC Profiling

This repository contains the implementation and profiling experiments of the DCVC-DC neural video compression model.

## Project Contents

- Training scripts for DCVC-DC
- Video testing scripts
- Dataset configuration files
- Profiling notebook from Kaggle

## Repository Structure

src/                    : model implementation  
checkpoints/            : pretrained model utilities  
dcvc-dc-profiling/      : Kaggle profiling notebook  
train_dcvc_DC.py        : training script  
test_video.py           : evaluation script  

## Dataset

Experiments are performed on HEVC Class B sequences:

- BQTerrace
- BasketballDrive
- Cactus
- Kimono
- ParkScene

## Experiments

Profiling was performed on Kaggle to analyze CPU and GPU usage of the DCVC-DC pipeline.

## Author

LOGMONS
