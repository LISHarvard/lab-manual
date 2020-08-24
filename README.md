# LISH Lab Manual

All code for projects should live in this GitHub organization. We want to be able to have a central location to find ongoing and past lab projects, with easily accessible code and data. 

## Projects
Make sure to follow these guidelines when creating a new project repository.
1. When creating a new repo, default to making the repository private. You may be working with sensitive data or code that is not yet ready for public consumption. You may make the repo public later on. Note that when you create a private repo, members of the LISH organization can still clone, pull, and commit to your repo.
2. Each project repository is required to have a README. A README needs to have basic information including the purpose of the projects, how to run the code, and where to find the data.
3. Each project repository also needs a `requirement.txt` file. This file will list all of the libraries that are required to run the code in your repo. For more details on writing and installing from a `requirements.txt` file, [see this page](https://note.nkmk.me/en/python-pip-install-requirements/).

### Code
Your code should be well organized and documented.
1. When you have more than few scripts, use folders to organize your code.
2. Avoid magic numbers. (`dogs * number_of_dog_owners` rather than `dogs * 12`)
3. Use descriptive file, class, method, and variable names. (Not `Unititled.ipynb` or `def x()`)

### Data
GitHub does not allow tracking of files over 100MB. In most cases, all data should be stored externally and the project README should include a detailed description of how to find and access the data for the project.
