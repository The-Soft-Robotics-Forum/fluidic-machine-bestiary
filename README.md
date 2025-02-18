# The Bestiary of Fluidic Machines
The Fluidic Machine Bestiary is an online repository of reconfigurable fluidic building blocks, which can be used to readily build and deploy entirely new types of fluidic machines, including bio-inspired, monolithically-printed soft robots.

The goal of the project is to take the pace of development in soft robotics to another level. Instead of starting from scratch, designers have access to a centralised repository of component models in a standardised file format. This format encourages knowledge-sharing, and allows to be creative within the process, instead of recreating the same results, and trying to solve the same problems.

As the bestiary evolves, it will include entire printable monolothic robots, as well as individual constituent modules, including control logic blocks, sensors, and actuators.

We encourage others to submit their components to the platform and help turn it into a thriving marketplace of ideas, and a model for the future of democratised research.

# How to use
The repository has been subdivided into folders for each component type (actuators, control components, etc.). Each folder includes .step files for the modules, which you can load into your CAD software of choice, and use to build entirely new machines. You can also import .step directly into your slicing software of choice (instead of .stl).

The current fluidic connection standard is 2mm x 2mm square channels, due to its relative ease of manufacturing on FDM machines. Do not worry if your models do not meet this standard; it is likely to evolve in the future to cater to the community's needs.

# Associated work
The Flex Printer is an open-source 3D printing platform which makes printing ultra-flexible elastomers easy, reliable, and fast. It's one of the best ways to quickly get up and running, printing and experimenting with your own soft machines. You can find out more on the [Flex Printer repository](https://github.com/The-Soft-Robotics-Forum/flex-printer).

# How to contribute
Complete beginner guide for forking github repo and contributing. If you have prior experience, skip to [Step 6](#Step-6:-Pull-Request)

### Step 1: Fork the Repo 
1. Click the "Fork" button in the top-right corner of the page - [1](https://www.freecodecamp.org/news/how-to-fork-a-github-repository/)
2. Chose where to fork the repository 
### Step 2: Clone your forked repo
1. Go to your forked repo and copy the URL that appears when the green code button is clicked. 
2.  open a terminal on your computer and run `git clone [URL]` [2](https://www.gitkraken.com/learn/git/problems/github-how-to-fork)
### Step 3: Create a branch 
1. navigate to your recently cloned repo on your pc via terminal
2. `git checkout -b [NEW_BRANCH_NAME]` where new_branch_name is the name you wish to give your branch
### Step 4: Make changes 
1. make your desired changes to the part files keep note of the voron naming scheme and be consistent 
2.  run `git add .` 
3. run `git commit -m "a detailed message of the changes you have made"`
### Step 5: Push Changes and Create a pull request. 
1. `git push origin [NEW_BRANCH_NAME]`
2. go to your fork on the github website and select compare and pull request
3. fill in the pull request details 
### Step 6: Pull Request
- Provide a clear and concise title for the pull request
- include a detailed description of the part changes you have made and why
    - if you have introduced new parts make sure the naming is consistent with the in place naming scheme
    - if you have introduced new hardware please provide a BOM for this
