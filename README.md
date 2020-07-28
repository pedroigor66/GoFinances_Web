# Table of contents
- [About](#about)
- [Main libs and techs used](#-main-libs-and-techs-used)
- [Downloading and setting up the project](#-downloading-and-setting-up-the-project)
- [Usage](#usage)
- [License & copyright](#license--copyright)

## About

This project was done during Rocketseat's GoStack bootcamp challenge. It is a web application that displays transactions with incomes, outcomes and the resulting balance. Similar to how a bank account balance is displayed. The transactions can be imported in `.csv` files that have their data separated by commas.

This is an example of how your dashboard webpage should look like once everything is correctly set up:

![Dashboard_Screenshot](/src/assets/dashboard_img.jpg)

<!-- UPDATE THE NODEJS README -->

---

## 👨‍💻 Main libs and techs used

This project was developed using the following techs:

- [React](https://pt-br.reactjs.org/)
- [CSS with Styled Components](https://styled-components.com/)
- [uuidv4](https://www.npmjs.com/package/uuidv4)
- [Insomnia](https://insomnia.rest/)
- [Axios](https://github.com/axios/axios)
- [nodeJS server from previous challenge](https://github.com/pedroigor66/node_typeorm)

---

## 🔧 Downloading and setting up the project

Simply clone this template or download it to your device and run the command **yarn** on your terminal to install all required dependencies.
To make sure erything is running properly, run **yarn test**.
To run the webpage, run the command **yarn start**.
To run the API server, download the [nodeJS server](https://github.com/pedroigor66/node_typeorm) then install its dependencies and run the command **yarn dev:server**.
See more instructions on how to set up the server in the [nodeJS server GitHub repository](https://github.com/pedroigor66/node_typeorm).

---

## Usage

- `List the transactions in the API`: The Dashboard page should be able to display a list in a table with the fields `title`, `value`, `type` and `category`. The table should display all the transaction that are stored in the API (nodeJS server).

- `Displaying the resulting balance from the API`: The api should return the total balance after decreasing the incomes from the outcomes. Outcome transactions that could turn the balance negative are not going to be accepted.

- `Importing .csv files`: In the **import** page, `.csv` files should be allowed to be submitted. The transactions in the files must be stored in the API and should reflect on the Dashboard.

This is how the import page should look like:

![Import_webpage](/src/assets/import_page.jpg)


## License & copyright

Developed by Pedro Igor C. de Oliveira.

Licensed under the [MIT License](LICENSE).
