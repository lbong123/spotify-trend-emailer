<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About the Project

<p align="center">
  <img src="https://user-images.githubusercontent.com/108723117/181786012-31b5a25b-5b1d-4397-a44a-b5ff2fc423d4.png" width="700" height="500"/>
</p>

The goal of this project was to an analytics tool capable of displaying aggregated listening statistics throughout the year of a specific user.

*Key Features*
- automated email containing listening statistics throughout the year
- multi-modal feedback in the form of graphs, charts and tables
- customised Spotify feel in received feedback


### Built With

* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
* ![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)
* ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
* ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
* ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

<p align="right">(<a href="#about-the-project">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

To run this project in your own codespace you will need to have Python installed.

### Installation

#### Libraries
1. Install spotipy
   ```sh
   pip install spotipy
   ```
2. Install plotly
   ```sh
   pip install plotly
   ```
3. Install pandas
   ```sh
   pip install pandas
   ```
#### Accessing Spotify for Developers
To access the spotify for developers dashboard, ensure you have a valid spotify account and then log in and create a new project with any name you want

##### Client Details
<p align="center">
  <img src="https://user-images.githubusercontent.com/108723117/181784499-e4e4e25e-5060-4084-962b-ea6dad0942a9.png" width="700" height="450"/>
</p>

##### Adding Redirect URL
Simply click on edit settings and then add the redirect url - http://localhost:9000

<p align="center">
  <img src="https://user-images.githubusercontent.com/108723117/181784857-a329e35a-7b83-473c-9d38-7f65d5610d73.png" width="700" height="450"/>
</p>

<p align="right">(<a href="#about-the-project">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage
To use the program, simply run the main file after entering your personal details for your email and spotify developer account


``` Python
client_ID="YOUR_CLIENT_ID"
client_SECRET='YOUR_CLIENT_SECERET'   
redirect_url='http://localhost:9000'

EMAIL_ADDRESS = 'YOUR_EMAIL_ADDRESS'
EMAIL_PASSWORD = 'YOUR_EMAIL_PASS'
TARGET_ADDRESS = "TARGET_EMAIL"
```






