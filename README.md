# Anaconda Environment Set-up 

1. Install Python 3.7 from the official [site](https://www.python.org/downloads/)
2. Install [Anaconda](https://www.anaconda.com/distribution/) for the version of Python you installed
3. To create the environment, run `conda env create -f environment.yml -n helmet-env`
    * To verify that it was created properly, run `conda info --envs` to list all conda environments
    * You may need to install pip before this step
4. To activate the environment, run `source activate helmet-env` 
5. To deactivate the environment, run `source deactivate` 
6. Further documentation can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)

As the project progresses, add all dependencies to the YAML file and update the environment accordingly.