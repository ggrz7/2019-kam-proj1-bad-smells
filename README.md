# 2019-kam-proj1-bad-smells
First project for Knowledge Analysis &amp; Management (2019)
### Documentation
 
For the general documentation run:

    python3 bad_smells.py

For details about each command and instruction on "how to run", run:

    python3 bad_smells.py <command> -h/--help
    
### Generated files
All the files generated by the software can be found in folder `res` (in project root).

### Arguments
By default the three available function use files `tree.py` and project to analyze (e.g `android-chess`) 
in the `lib` folder, although this folder is not uploaded to github. Therefore to use the function without 
arguments you should create the `lib` folder (in the project root) and move there the two files.

### Examples usage:
The following are some example of commands:
1. **Ontology creation**
    - ```$ python3 bad_smells.py onto_creator -p <path>/tree.py```
2. **Ontology population**
    - ```$ python3 bad_smells.py individ_creator -s <path>/android-chess/app/src/main/java/jwtc/chess```
3. **Detect bad smells**
    - ```$ python3 bad_smells.py find_bad_smells```
