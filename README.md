# DeSo Flask Integration

This project demonstrates how to integrate a Flask application with the DeSo (Decentralized Social) blockchain protocol. It includes functionalities for user authentication via DeSo Identity and posting content to the DeSo blockchain. Additionally, it utilizes IPFS for decentralized media storage, enhancing the application's capability to handle decentralized data.

## Features

- User authentication with DeSo Identity
- Posting content to the DeSo blockchain
- Uploading media to IPFS and referencing in DeSo posts
- Easy deployment with Heroku's one-click deploy feature

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Pip for Python package installation
- Heroku CLI (for deployment)

### Local Development Setup

1. Clone the repository:

  
   git clone https://github.com/<your-github-username>/<your-repo-name>.git
   cd <your-repo-name>

Create a virtual environment and activate it:

     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`>

2.Install the dependencies:

     pip install -r requirements.txt


3.Run the Flask application locally:

    flask run

Your app should now be running on http://localhost:5000.

###Deployment

Deploy this application to Heroku with a single click:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/yourusername/your-repo-name)


##  Manual Deployment to Heroku
If you prefer, you can also manually deploy the app using the Heroku CLI:

1.Log in to Heroku and create a new app:

         heroku login
         heroku create <your-heroku-app-name>
2.Push your code to Heroku:

        git push heroku main
        
3.Open your application:

        heroku open

## Contributing

We welcome contributions to this project! Please see CONTRIBUTING.md for more details on how to contribute.

## License

This project is open source under the terms of the MIT License.

## Acknowledgments

DeSo Protocol for providing a decentralized social network framework.
IPFS for decentralized storage solutions.
