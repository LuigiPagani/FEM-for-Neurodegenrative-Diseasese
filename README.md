### Instruction to build and run the code


The brain mesh can be downloaded from this link and placed inside the folder "FK_solver/mesh":
https://drive.google.com/file/d/1PJTaHAU-kgxId5_C6Zd4nj27HRcyHZS2/view

### Compiling
To build the executable:
```bash
$  cd FK_solver/src/
$ module load gcc-glibc dealii
$ mkdir build
$ cd build
$ cmake ..
$ make
```
The executable will be created into `build`, and can be executed through
```bash
$ mpirun -np <number of cores> ./FK_solver
```

## Authors

- Simon Hugot      ([@nncm-xbc](https://github.com/nncm-xbc))
- Luigi Pagani     ([@LuigiPagani](https://github.com/LuigiPagani))
- Samuele Vignolo  ([@samuvignolo](https://github.com/samuvignolo))
