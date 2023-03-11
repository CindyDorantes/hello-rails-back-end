<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Hello-rails-back-end <a name="about-project"></a>

**Hello-rails-back-end** is the backend part of a full-stack application built with rails as an api &react for the front end

Follow this [Link](https://github.com/CindyDorantes/hello-react-front-end) for the frontend repo

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

![](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white) 
<br/>
![](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
<br/>
![](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### Key Features <a name="key-features"></a>

- FullStack Application
- Using React with Rails in different repos
- API-only rails application

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Basic knowledge of the command line.
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/) installed on your device.
- [Ruby on Rails](https://guides.rubyonrails.org/v5.0/getting_started.html) installed on your device.
- Postgresql Database, you can follow this [link](https://www.postgresql.org/download/), choose your system & follow the provided instructions.
- Node.js installed to use ```npm```

### Setup

- Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone https://github.com/CindyDorantes/hello-rails-back-end.git
```

- Clone the frontend repository **IN THE SAME** directory:

```sh
  cd my-folder
  git https://github.com/CindyDorantes/hello-react-front-end.git
```

### Install

- Run
```sh
  cd hello-react-front-end
  bundle install
```
<hr>

### Usage

To run the project, follow these steps:

- Modify the "database.yml" file to adjust the username & password if needed

- Create database, run migration & populate the database
```sh
  rails db:create
  rails db:migrate
  rails db:seed
```
- To run the project in your browser, run:
```sh
  rails s
```
- Finally, follow the instructions in the README of the front-end repo.

<hr>

## 👥 Authors <a name="authors"></a>

👤 **Cindy Dorantes**

- GitHub: [@CindyDorantes](https://github.com/CindyDorantes)
- Twitter: [@CindyDorantes10](https://twitter.com/CindyDorantes10)
- LinkedIn: [Cindy Melisa Dorantes Sánchez](https://www.linkedin.com/in/cindydorantessanchez/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give a ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Microverse for overseeing the project.
- Thanks to my learning partners for their help and support

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>