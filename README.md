# MLOps – Course

This repository contains the slides, labs, and project scaffold for a  MLOps training:

## Structure
```
mlops_2day_course/
├── slides/
│   └── MLOps_SupdeVinci.pptx
├── labs/
│   ├── Lab1/
│   └── Lab2_SA_HuggingFace/
├── project/
│   └── ml_microservice/
├── docs/
│   └── syllabus.md

```

## Quickstart
```bash
# create & activate env
python3 -m venv .venv && source .venv/bin/activate
pip install -r project/ml_microservice/requirements.txt

# run microservice locally
make -C project/ml_microservice run

# run tests
make -C project/ml_microservice test



https://huggingface.co/B2lmb/sentiment_distilbert/commit/ead453e28d5795d863ffe132b2b24e0ba9b66b3b
```
