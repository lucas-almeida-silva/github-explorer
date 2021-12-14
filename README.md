<p align="center">
   <img src=".github/logo.jpg" alt="Github Explorer" />
</p>

# :page_with_curl: Table of Contents

* [About](#information_source-about)
* [Technologies](#computer-technologies)
* [Requirements](#page_with_curl-requirements)
* [Features](#rocket-features)
* [Images](#camera-images)
* [How to run](#seedling-how-to-run)
* [License](#pencil-license)

# :information_source: About

GitHub Explorer is a web application to search GitHub repositories based on author and repository name. The repository data is taken from the API provided by GitHub.

From the repository details, you can see the number of stars, forks and open issues, in addition to the list of issues. By clicking on an issue, the user is redirected 
to the issue's page on GitHub.

These searched repositories are stored in the browser's local storage. 

# :computer: Technologies

- [ReactJS](https://pt-br.reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)

# :page_with_curl: Requirements

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) (optional)
- [Git](https://git-scm.com/) (to clone the repository)

# :rocket: Features

- Search repositories
- View repository details (stars, forks and issues)

# :camera: Images

 <img src=".github/explore-repos-page.jpg" alt="Explore repositories" />
 <img src=".github/repo-details.jpg" alt="Repository details" height="550" style="margin-top: 10px" />
 
# :seedling: How to run

```bash
# Clone the repository
$ git clone https://github.com/lucas-almeida-silva/github-explorer.git

# Go to the project folder
$ cd github-explorer

# Install Dependencies
$ yarn
# or npm install

# Run the application
$ yarn start
# or npm start
```
Access the application at http://localhost:3000

# :pencil: License

This project is under the [MIT license](LICENSE).
