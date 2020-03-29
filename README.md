## Project Name:  cpp_soln_checker
This is useful to various online judge problem submission, for checking program output with the given output.
steps:
1.create `in` & `out` file in any directory.

2.add the directory name (`Dir` variable) in script.

3.`source` the script.
(use it on the current terminal)

4.copy inputs & outputs of the current program in `in` & `out` files respectively. It will check automatically and either give success or throw error
using guide
```bash
$ compile <filename>.cpp
```
if you want to compile with sanitizers use
using guide
```bash
$ compile <filename>.cpp 1
```


To use it permanently across all terminals add these lines in your `~/.bashrc` at the end.
```bash
if [[ -f /<location>/compile ]];then
   source /<location>/compile
fi
```
-Bisakh
