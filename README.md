# Laravel 6 - Development Container
This repository is for the CIS2167 - Server & Client Side Scripting module at Edge Hill University.

**Tested and verified to work with:**
- Windows: 11 and 10.

## Setup
Depending on your system, this should take around 5-10 mins.

### If you are using Visual Studio Code (VSC) - recommended
1. Create an empty project folder for which you want to use this development container for _(e.g. blogadmin)_. 
2. Download the repository as a zip folder _(not clone as this will be used for your own repository)_.
3. Extract the folder into your empty project folder.
4. Open the project project in VSC.
5. Go to `View` > `Command Palette...` and type in `Open Folder in Container...`.
6. Create your Laravel project.

## Extras
### Renaming containers
When opening a folder in a container with VSC, it will give it a random name as you may notice in your `Docker Desktop` application. It is fine if you have one container but as you progress with your modules, it will start getting messy as you create more containers.

**If you want to be more organised and quickly know which container is for which project, follow the following steps to rename it:**
1. Open `Docker Desktop`.
2. Identify which container is for which project _(you can do this by running it and seeing what it is)_.
3. In a terminal, run `docker container rename <current_container_name> <new_name>`

For example: `docker container rename hopeful_eular CIS2167_BLOGADMIN`.

## Contributing
Using `git` is all about version control, contribution, and teamwork. **If you want to practice forking and submitting pull requests**, feel free to add more sections to this README.md file that will help your current and future class mates.

For example, different operating systems and code editors may require additional or less actions so put the time in add those in here for others! Plus, you can say you contributed and it will increase your experience.
