# Depression-Detection-In-Multilingual-Code-Switching


  ## Goal
  To develop a classification system to detect depression using NLP and machine learning. 
  
  ## Getting Started
  These instructions describe the prerequisites and steps to get the project up and running.

  ### Setup
 
 To setup a Virtual Environment with all the prerequisite packages used in the project, do the following:
  1. Install [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) using the `conda_install.sh` file in the 'scripts' directory using the command: `$ bash scripts/conda_install.sh`
  2. Create a conda environment from the included `environment.yml` file using the following command:
     
     `$ conda env create -f environment.yml`
  3. Activate the environment
     
     `$ conda activate NLP`

  ### Usage
  To run the code, the user can navigate to the folder containing the file 'team-mangalyaan.py', and run it using the command: `$ python team-mangalyaan.py --options`. The user can get a description of the options by using the command: `$ python team-mangalyaan.py -help`.
  
   
  ### Output
  Upon running the command in the ‘Usage’ section, barplots will be created that illustrate the effects of the three postprocessing techniques used here to deal with machine bias on the three different datasets based on gender and race.


## License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for more details.
