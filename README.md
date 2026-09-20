### Repository Structure

```
zambia-commodity-price-forcasting-model
├── api
│   ├── main.py              # FastAPI app + lifespan
│   ├── schemas.py           # Pydantic request/response models
│   └── routers/
│   ├── predict.py
│   └── health.py
├── artifacts               # figures and digrams for the report
├── data
│   ├── processed            # original CSVs — never modify
│   └── raw                  # train and test dataset
├── helpers                  # shared code between notebooks and scripts
├── LICENSE
├── models                   # Trained models
├── notebooks
├── pyproject.toml
├── README.md
└── scripts
```

- original CSVs — never modify ->
