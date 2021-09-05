# FSL Util Code

[![hackmd-github-sync-badge](https://hackmd.io/nQElH4AyS3SF9ZijfrdSSA/badge)](https://hackmd.io/nQElH4AyS3SF9ZijfrdSSA)


## `util_convert_format.py`

Convert `checkpoint` to `h5` or `tflite`

```bash
python3 util_convert_format.py <path/to/param.py>
```

## `util_export_embedding.py`

Export data to embeddings.

```bash
python3 util_export_embedding.py <path/to/param.py>
```

edit line 34, 35 `dataset` path and `output_dir_name`.

## `util_export_reference.py`

Average embeddings each class as supported set.

```bash
python3 util_export_reference.py <path/to/output_dir_name/>
```