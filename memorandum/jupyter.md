

```bash
jupyter notebook --generate-config
```

Check the file in `~/.jupyter/jupyter_notebook_config.py`

指定notebook的初始目录

```python
c.NotebookApp.notebook_dir = u'/notebook'
```

资源文件目录`~/anaconda3/lib/python3.6/site-packages/notebook/static`