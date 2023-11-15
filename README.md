# dotcime
Configuration files for porting CESM to the machines Betzy and Fram under a .cime folder.

This repository makes it possible to pull the latest changes in [cime](https://github.com/ESMCI/cime) without affecting your machine configuration. 

***THIS IS NOT A VERY GOOD WAY TO RUN THINGS INSTEAD CHECKOUT CTSM FROM NorESMhub OR CHANGE THE EXTARNALS.CFG TO CHECKOUT CIME at NorESMhub***

**FOR CESM 2.1.3**

## Usage
Clone, name, and place this repository under the folder `$HOME/.cime` to run CTSM out of the box (hopefully). This setup is not recommended. Also, saga config is outdated and can not be fixed yet.

### NB 
By storing the machine configurations under  the folder `$HOME/.cime` you must create a case with the following command

```
$CTSM_ROOT/cime/scripts/create_newcase --case <your-case-name> --res <your-res> --compset <your-compset> --machine <your-machine> --run-unsupported --project <your-project> `
```
 **FOR CESM 2.1.3**

 Please clone this repo and check out `cesm2.1_fram` branch
