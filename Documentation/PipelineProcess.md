# Pipeline process

- Using github as a source code management tool, developers work and push their changes to specific repository.

- Creating a circleCi pipeline attached to the github repository, the pipeline will be triggered with every change in the repository.

- The pipeline has different steps like ( install project dependencies , build , test and deploy). 

- All those steps are defined in .circleci/config.yaml file
