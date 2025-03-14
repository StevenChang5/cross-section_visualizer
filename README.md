# FLUVIAL-12 Visualizer

The purpose of this repository is to visualize the output of the FLUVIAL-12 model. This program enables users to easily view hydrograph cross sections at a user-specified time. 

<p align="center">
    <img src="figures/gui.png" alt="Application GUI" width="540"/>
</p>

## Run Locally

Clone the project

```bash
  git clone https://github.com/StevenChang5/cross-section_visualizer.git
```

Go to the project directory

```bash
  cd cross_section_visualizer
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Place the b4m.txt file into a "files" folder before running the program

Go to the src directory and run the program

```bash
  cd src
  python3 main.py
```