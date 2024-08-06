
This is the single one-file budled CrackMapExec executable for Windows.
# CrackMapExecWin
<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/5151193/17577511/d312ceb4-5f3b-11e6-8de5-8822246289fd.jpg" alt="cme"/>
</p>

:triangular_flag_on_post: Features
--------
* Added the necessary hiddenimports based on the original crackmapexec.spec files in the project of **[byt3bl33d3r's CrackMapExec](https://github.com/Porchetta-Industries/CrackMapExec)**,then use **[pyinstaller](https://pypi.org/project/pyinstaller/)** to package a single one-file budled executable.

Build exe
--------
```
pyinstaller crackmapexec.spec
```
Build cme
--------
```
python build_collector.py
```