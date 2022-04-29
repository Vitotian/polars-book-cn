# IO

`Polars` 支持多种文件类型，其各自的分析器是目前最快的。

例如,在用`Pandas`处理CSV之前，*通过*`Polars`读取，比直接用`Pandas`读取更快。

只需运行`pl.read_csv("<FILE>", rechunk=False).to_pandas()`去说服你自己！
