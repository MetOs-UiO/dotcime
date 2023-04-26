# dotcime
Configuration files for porting CTSM to the machines Saga and Fram under a .cime folder.

This repository makes it possible to pull the latest changes in [cime](https://github.com/ESMCI/cime) without affecting your machine configuration. 

## Usage
Clone, name, and place this repository under the folder `$HOME/.cime` to run CTSM out of the box (hopefully). This setup is not recommended. Also, saga config is outdated and can not be fixed yet.

### NB 
By storing the machine configurations under  the folder `$HOME/.cime` you must create a case with the following command

```
$CTSM_ROOT/cime/scripts/create_newcase --case <your-case-name> --res <your-res> --compset <your-compset> --machine <your-machine> --run-unsupported --project <your-project> `
```
 