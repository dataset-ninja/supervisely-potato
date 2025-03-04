Dataset **Supervisely Potatoes** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzMwNzVfU3VwZXJ2aXNlbHkgUG90YXRvZXMvc3VwZXJ2aXNlbHktcG90YXRvZXMtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiOS9yemR2ZlVpN25DM3NVaUtVcDdRamI2UVlIcHJhV1NNOGxZUlhER2lHQT0ifQ==)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Supervisely Potatoes', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://supervisely.com/blog/trained-smarttool-plants/).