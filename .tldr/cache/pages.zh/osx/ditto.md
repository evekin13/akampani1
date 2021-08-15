# ditto

> 复制文件和目录。

- 用源目录的内容覆盖目标目录的内容：

`ditto {{源文件路径}} {{目标文件路径}}`

- 为复制的每个文件打印一行到终端窗口：

`ditto -V {{源文件路径}} {{目标文件路径}}`

- 复制给定的文件或目录，同时保留原始文件权限：

`ditto -rsrc {{源文件路径}} {{目标文件路径}}`