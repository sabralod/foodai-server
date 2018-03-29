```bash
conda env create -f environment.yml
```
```bash
source activate foodai-server
source deactivate foodai-server
```

**Notes:**

https://github.com/conda/conda/issues/4339
```bash
conda env export | cut -f 1 -d '='
```