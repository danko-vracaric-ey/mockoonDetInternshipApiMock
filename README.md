# mockoonDetInternshipApiMock

# Introduction

- We use mock API when we don't have a server ready and want our front end team to start working or to share our API with someone who don't have access to it. Mockoon let's us set up our mock API fast and locally which guarantees safety of our data as it is run in our local network.

# How to run it

- Clone mockoonDetInternshipApiMock GIT repository `https://github.com/danko-vracaric-ey/mockoonDetInternshipApiMock.git` which cointains the environment file that we need to open in Mockoon to get our mock API server up and running

# Through Desktop Application

1. Download and install Mockoon desktop application `https://mockoon.com/download/`

2. Go to File -> Open Environment and select the `mockoonDetInternshipApiMock.json` environment from the cloned git repository

3. Press Run button

# Or through @Mockoon/cli NPM package

1. Install Mockoon package `$ npm install -g @mockoon/cli`

2. Run your mock file `$ mockoon-cli start --data ~/path/to/your-environment-file.json`

- for more information visit official Mockoon documentation page `https://mockoon.com/docs/latest/about/`

- As the final step replace `http://det.api.rs.ey.com` with `http://127.0.0.1:3001` inside your project and see all the routes once you load the environment by pressing Routes next to the Play button

# Note

- Supported countries: New York and South Carolina
