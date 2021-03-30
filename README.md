# OSU UWRT 2021 ML Workshop

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#setup">Setup</a></li>
        <li><a href="#api-key">Api Key</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This workshop introduces concepts of Machine Learning by solving a real world problem using machine learning concepts. A simple approach to solving the problem will be implemented first, then the complexity of the solution will be expaneded. Finally, the data the solution has access to is manually selected to further improve the solution and demonstrate overtraining. Basic concept of neural networks will also be discussed.

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

Before the workshop, make sure you have [Python](https://www.python.org/downloads/) and [Visual Studio Code](https://code.visualstudio.com/download) installed on your computer before starting. When installing Python on Windows, make sure to check the "Add to PATH" checkbox on the first window.

### Setup

You do not need to complete these steps before the workshop, but you can if you want.

1. Download a zip of the repo [from this link](https://github.com/osu-uwrt/2021_ML_Workshop/zipball/master) and unzip it.
2. Open this folder in Visual Studio Code. Click "Install", "Allow" or "Trust" for every message that pops up in the bottom right corner.
3. Install dependencies by opening a terminal in Visual Studio Code and running
   ```sh
   python -m pip install -r requirements.txt
   ```
   - If the installation fails, try it on a version of Python below 3.7. A windows installer for Python 3.6.8 can be found [here](https://www.python.org/ftp/python/3.6.8/python-3.6.8-amd64.exe). You may need to add it to your PATH environment variable and remove any other Python versions in there such that running `python -v` displays 3.6.8.
4. Open the file `ml-workshop.ipynb` and you should be good to go! If this step works, you are all set up for the workshop!

### API Key

If the weather data download is not working, the API key may have expired. To generate a new one visit [https://worldweatheronline.com](https://www.worldweatheronline.com/developer/signup.aspx) and place it in `ml-workshop.ipynb`

<!-- USAGE EXAMPLES -->

## Usage

Open up `ml-workshop.ipynb` and follow along with each of the sections.

<!-- CONTACT -->

## Contact

Email: [osu.uwrt@gmail.com](mailto://osu.uwrt@gmail.com)

Website: [https://uwrt.club](https://uwrt.club)
