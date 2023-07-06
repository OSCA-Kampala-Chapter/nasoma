# NASOMA
**Description**: _**Nasoma**_ is an open source web application designed to streamline the hiring process for tech enthusiasts and recruiters. It serves as a centralized hub where talented individuals can effortlessly display their skill sets in various programming languages, making it easier for recruiters to assess their capabilities without extensive manual inquiries. The project's name, **"Nasoma"** represents the concept of digitally presenting one's educational background, similar to showcasing a school diploma.

- **Technologies**: _**Nasoma**_ is built using the following technologies:
  - Frontend: HTML, CSS (SCSS), JavaScript, Bootstrap v5.2.3
  - Backend: PHP >= 7.4.3, MySQL > 8.0
- **Status**: _**Nasoma**_ is currently under development. The project is an open source initiative, and contributions are welcome.
- **Production URL**: _**Nasoma**_ is currently not deployed to a production environment. However, you can clone the repository and run it locally on your machine.
## Dependencies
- [PHP](https://www.php.net/downloads.php) - PHP >= 7.4.3 is required
- [MySQL](https://www.mysql.com/downloads/) - MySQL > 8.0 is required
- [Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/download/) - Bootstrap v5.2.3 is required
- [SCSS](https://sass-lang.com/install) - SCSS is required to compile the SCSS files to CSS
## Installation
1. Clone the repository
```bash
git clone
```
2. Create a database named `nasoma` in MySQL
3. Import the `nasoma.sql` file into the `nasoma` database
4. Navigate to the `nasoma` directory
```bash
cd nasoma
```
5. Install the dependencies
```bash
composer install
```
6. Run the application
```bash
php -S localhost:8000
```
7. Open your browser and navigate to `localhost:8000`
## Usage
- Applicants can create an account and add their educational background, work experience, and skills.
- Recruiters can create an account and search for applicants based on their skills.
## Contributing
Contributions are welcome. Feel free to open a pull request or branch from this repository.
### Prerequisites
Kindly take time to understand the project's structure and the technologies used before contributing.
- The project's structure is based on the _**view-api**_ pattern referenced [here](https://github.com/cim-engineering/view-api-pattern)
- The database structure utilizes a DB wrapper class referenced [here](https://github.com/ThingEngineer/PHP-MySQLi-Database-Class)
- The project utilizes the router referenced [here](https://github.com/steampixel/simplePHPRouter)
- The project utilizes Rakit validation referenced [here](https://github.com/rakit/validation)
### Steps
1. Fork the repository
2. Create your feature branch
```bash
git checkout -b feature/your-feature
```
3. Commit your changes
```bash
git commit -m "Add your commit message here"
```
4. Push to the branch
```bash
git push origin feature/your-feature
```
5. Open a pull request
6. Wait for your pull request to be reviewed and merged
7. Celebrate your contribution!
## License
This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/license/mit/) for details.
## Credit and Acknowledgment

## Contributors
- [Marshud](https://github.com/Marshud) - _Initial work_
- [jshgwng](https://github.com/jshgwng) - _Project manager_
- [Alshatri](https://github.com/Alshatri) - 