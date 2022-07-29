# Spotify-Trend-Emailer
A humble version of Spotify Wrapped, that utilises the Spotify API and the email package

## Installation
```bash
pip install spotipy
```

## Accessing Spotify for Developers
To access the spotify for developers dashboard, ensure you have a valid spotify account and then log in and create a new project with any name you want

### Client Details
![spotify1](https://user-images.githubusercontent.com/108723117/181784499-e4e4e25e-5060-4084-962b-ea6dad0942a9.png)

### Adding Redirect URL
Simply click on edit settings and then add the redirect url - http://localhost:9000

![image](https://user-images.githubusercontent.com/108723117/181784857-a329e35a-7b83-473c-9d38-7f65d5610d73.png)



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

## Successful
Well done!! You now have access to your most recent trends and statistics from your spotify account

![example](https://user-images.githubusercontent.com/108723117/181786012-31b5a25b-5b1d-4397-a44a-b5ff2fc423d4.png)





