# git-them

> This project features an Angular app that consumes the GitHub API to retrieve user and repository information.

## Description

git-them app provides a way to search and display a GitHub user's information that includes their username, profile photo and repository listings.

## Getting Started

To get you started you can simply clone the `git-them` repository and install the dependencies.

### Prerequisites

You need git to clone the `git-them` repository. You can get git from [here](https://git-scm.com/).

You must also have Node.js and its package manager (npm) installed. You can get them from [here](https://nodejs.org/).

### Clone `git-them`

Clone the `git-them` repository using git:

```
git clone https://github.com/trucktar/git-them.git
cd git-them
```

### Install Dependencies

There are two kinds of dependencies in this project: tools and Angular framework code.

To install these dependencies and setup the project environment, simply run:

```
npm install
```

### Run the Application

The project is preconfigured with a simple development web server. The simplest way to start this server is:

```
ng serve
```

Now browse to the app at [`localhost:4200/`](local-app-url).

## Usage

On startup, the app displays [TruckTAR's](https://github.com/trucktar/) user information and public repositories. To view a different user's information, navigate to the user-search page by clicking the `Search User` link in the navbar.

In the form displayed, enter a username and click submit. If the user exists, you'll be redirected to the user-repos page where the user's information and repositories are listed.

## Contact

Nyota Mwangi - [@trucktar](https://twitter.com/trucktar/) - nyota.benjamin@gmail.com  
Project Link: [https://trucktar.github.io/git-them/](https://trucktar.github.io/git-them/)

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
