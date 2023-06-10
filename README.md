# Python-shutdown-Windows
Windows关机Python程序
import os：这行代码导入了Python的os模块，用于与操作系统进行交互。

shutdown_command = "shutdown /s /t 0"：这行代码定义了一个名为shutdown_command的变量，它包含了一个表示关机命令的字符串。/s参数表示执行关机操作，/t 0参数表示在0秒后关机。

os.system(shutdown_command)：这行代码使用os.system()函数执行了关机命令。os.system()函数允许您在操作系统的命令行中执行命令。在这里，我们将shutdown_command作为参数传递给os.system()函数，从而执行关机命令。
