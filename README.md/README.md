# Safe Road - Accident Detection ML

YOLOv8 accident-detection model training run and an interactive results dashboard, built for the [Safe Road](https://github.com/sohams5002/safe-road-app) emergency response project.

## What's here

- `args.yaml` - YOLOv8 training configuration for the run
- `results.csv` - per-epoch training and validation metrics (loss, precision, recall, mAP)
- `labels.jpg`, `train_batch*.jpg` - label distribution and sample training batches
- `plot.py` - Plotly Dash dashboard that loads `results.csv` and visualises the training curves

## Run the dashboard

```
pip install -r requirements.txt
python plot.py
```

Then open the local Dash URL in a browser.

## Stack

Python, YOLOv8 (Ultralytics), Plotly Dash, Pandas
