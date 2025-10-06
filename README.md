# open-polymer
Open resources for the Polymer Challenge

## Install dependencies
Clone this repo and run:
```bash
uv sync
```

## Data

### Kaggle CLI
To use the `kaggle` cli tool, follow [Authentication instructions](https://www.kaggle.com/docs/api).

Download the `kaggle.json` file and run the following:
```bash
cp ~/Downloads/kaggle.json ~/.kaggle/kaggle.json
chmod 600 ~/.kaggle/kaggle.json
```

```bash
kaggle competitions download -c neurips-open-polymer-prediction-2025
```
