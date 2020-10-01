# {{ cookiecutter.project_name }}

{{ cookiecutter.project_description }}. This project was created and is maintained by {{ cookiecutter.project_author }}.

## Project structure

```
└───{{ cookiecutter.project_name }}
    ├───bin/             ---> third-party executables and scripts
    ├───data/            ---> all project data goes here (eg: csv, fastq, fasta, vcf). Large file extensions must be added to .gitignore
    │   ├───processed/   ---> processed data (eg: assembled genome, annotated genome, transformed tabular files)
    │   └───raw/         ---> raw data (eg: database dumps, raw CSVs, unestructured data)
    ├───docs/            ---> project documentation (eg: sphinx files)
    ├───notebooks/       ---> exploratory data analysis (EDA) files (eg: jupyter notebooks, r markdown, r notebooks)
    ├───scripts/         ---> utilitary scripts
    ├───tests/           ---> unitary tests
    ├───.env             ---> declaration of environment variables
    ├───.gitignore       ---> files and directories to be ignored by git
    ├───environment.yml  ---> conda environment file
    ├───LICENSE          ---> license for code distribution
    ├───Makefile         ---> Makefile to centralize the main analysis steps in "rules"
    ├───README.md        ---> Project README
    └───requirements.txt ---> python requirements
```

## Setup

```
$ make setup
```
