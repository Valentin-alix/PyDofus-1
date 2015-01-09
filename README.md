PyDofus Tools
=============

Python 3 scripts to pack/unpack Dofus files

- **d2i**: done
- **d2p**: done
- **dlm**: done
- **dx**: done
- **swl**: done


- **d2o**: todo
- **ele**: todo

Usage
-----

###d2i

```Shell
$ python d2i_unpack.py file.d2i
# file output: file.json
```

```Shell
$ python d2i_pack.py file.json
# file output: file.d2i
```

###d2p

```Shell
$ python d2p_pack.py
# (all files in input folder)
# folder output: ./output/{all files}.d2p
```

```Shell
$ python d2p_pack.py file.d2p
# require original file in input folder and unpacked file in output folder
# file output: ./output/~generated/file.d2p
```

###dlm

```Shell
$ python dlm_unpack.py file.dlm
# file output: file.json
```

```Shell
$ python dlm_pack.py file.json
# file output: file.dlm
```

###dx

```Shell
$ python dx_unpack.py file.dx
# file output: file.swf
```

```Shell
$ python dx_pack.py file.swf
# file output: file.dx
```

###swl

```Shell
$ python swl_unpack.py file.swl
# file output: file.swf and file.json
```

```Shell
$ python swl_pack.py file.swf
# require file.json
# file output: file.swl
```

Authors
-------

**Marvin Roger** ([marvinroger](https://github.com/marvinroger)) : based on his work
**Yann Guineau** ([LuaxY](https://github.com/LuaxY)) : automated scripts for pack/unpack dofus files
