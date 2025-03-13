# ProtoMedia GUI

This project is a graphical user interface (GUI) application built using Open3D for visualizing 3D models and point clouds. 

## Clone the Repository

To clone this repository, run:

```sh
git clone https://github.com/Aditya-Naresh/open3dgui.git
cd open3dgui
```

## Requirements

To install the required dependencies, run:

```sh
pip install -r requirements.txt
```

## Usage

To run the application, execute the following command:

```sh
python vis_gui.py
```


## Features

- **Lighting Profiles**: Choose from various predefined lighting profiles or customize your own.
- **Material Settings**: Apply different material presets to your models.
- **View Controls**: Switch between different mouse control modes such as Arcball, Fly, Model, Sun, and Environment.
- **Advanced Lighting**: Enable or disable HDR maps and sun lighting, and adjust their intensities and directions.
- **Export**: Export the current view as an image.

## File Structure

- `vis_gui.py`: Main application file containing the GUI implementation.
- `requirements.txt`: List of Python dependencies required for the project.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: This file.

## Acknowledgements

- [Open3D](http://www.open3d.org/) for providing the visualization and rendering framework.
