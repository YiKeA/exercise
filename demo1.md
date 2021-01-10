# easyocr相关报错

Using legacy 'Using legacy 'setup.py install' for torch, since package 'wheel' is not installed.
Installing collected packages: PyYAML, python-dateutil, pyparsing, Pillow, numpy, kiwisolver, decorator, cycler, torch, tifffile, scipy, PyWavelets, networkx, matplotlib, imageio, torchvision, scikit-image, opencv-python, easyocr
    Running setup.py install for torch ... error install' for torch, since package 'wheel' is not installed.
Installing collected packages: PyYAML, python-dateutil, pyparsing, Pillow, numpy, kiwisolver, decorator, cycler, torch, tifffile, scipy, PyWavelets, networkx, matplotlib, imageio, torchvision, scikit-image, opencv-python, easyocr
    Running setup.py install for torch ... error
    

> ERROR: Command errored out with exit status 1:
>      command: 'c:\users\abc\appdata\local\programs\python\python38-32\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\Abc\\AppData\\Local\\Temp\\pip-install-8o5wqxa9\\torch_9c8ebf7614474cedb4ef53d7d3496980\\setup.py'"'"'; __file__='"'"'C:\\Users\\Abc\\AppData\\Local\\Temp\\pip-install-8o5wqxa9\\torch_9c8ebf7614474cedb4ef53d7d3496980\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\Abc\AppData\Local\Temp\pip-record-yw7syoqo\install-record.txt' --single-version-externally-managed --compile --install-headers 'c:\users\abc\appdata\local\programs\python\python38-32\Include\torch'
>          cwd: C:\Users\Abc\AppData\Local\Temp\pip-install-8o5wqxa9\torch_9c8ebf7614474cedb4ef53d7d3496980\
>     Complete output (23 lines):
>     running install
>     running build_deps
>     Traceback (most recent call last):
>       File "<string>", line 1, in <module>
>       File "C:\Users\Abc\AppData\Local\Temp\pip-install-8o5wqxa9\torch_9c8ebf7614474cedb4ef53d7d3496980\setup.py", line 225, in <module>
>         setup(name="torch", version="0.1.2.post2",
>       File "c:\users\abc\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\__init__.py", line 145, in setup
>         return distutils.core.setup(**attrs)
>       File "c:\users\abc\appdata\local\programs\python\python38-32\lib\distutils\core.py", line 148, in setup
>         dist.run_commands()
>       File "c:\users\abc\appdata\local\programs\python\python38-32\lib\distutils\dist.py", line 966, in run_commands
>         self.run_command(cmd)
>       File "c:\users\abc\appdata\local\programs\python\python38-32\lib\distutils\dist.py", line 985, in run_command
>         cmd_obj.run()
>       File "C:\Users\Abc\AppData\Local\Temp\pip-install-8o5wqxa9\torch_9c8ebf7614474cedb4ef53d7d3496980\setup.py", line 99, in run
>         self.run_command('build_deps')
>       File "c:\users\abc\appdata\local\programs\python\python38-32\lib\distutils\cmd.py", line 313, in run_command
>         self.distribution.run_command(command)
>       File "c:\users\abc\appdata\local\programs\python\python38-32\lib\distutils\dist.py", line 985, in run_command
>         cmd_obj.run()
>       File "C:\Users\Abc\AppData\Local\Temp\pip-install-8o5wqxa9\torch_9c8ebf7614474cedb4ef53d7d3496980\setup.py", line 51, in run
>         from tools.nnwrap import generate_wrappers as generate_nn_wrappers
>
> ​    ModuleNotFoundError: No module named 'tools.nnwrap'
>
> ERROR: Command errored out with exit status 1: 'c:\users\abc\appdata\local\programs\python\python38-32\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\Abc\\AppData\\Local\\Temp\\pip-install-8o5wqxa9\\torch_9c8ebf7614474cedb4ef53d7d3496980\\setup.py'"'"'; __file__='"'"'C:\\Users\\Abc\\AppData\\Local\\Temp\\pip-install-8o5wqxa9\\torch_9c8ebf7614474cedb4ef53d7d3496980\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\Abc\AppData\Local\Temp\pip-record-yw7syoqo\install-record.txt' --single-version-externally-managed --compile --install-headers 'c:\users\abc\appdata\local\programs\python\python38-32\Include\torch' Check the logs for full command output.