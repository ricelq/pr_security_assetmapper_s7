
<span id="readme-top"></span>

<div align="center">

<h3 align="center">Symfony 7 Authentication Project</h3>

  <p align="center">
    This is a clean Symfony project implementing user authentication
    and the AssetMapper component combined with Tailwind.
   Manage assets without Node, Npm or any other bundler. 
    <br />    <br />
    </p>
</div>




<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* PHP 8.2
* MySQL
* Composer
* Symfony-cli

### Installation

Clone this repository to your local machine:

1. Clone the repo
   ```sh
   git clone https://github.com/ricelq/pr_security_assetmapper_s7.git
   ```

2. Install dependencies via composer
   <br>(Download [composer](https://getcomposer.org) if not yet installed)
   ```sh
   composer install
   ```

3. Edit the .env file with your USERNAME, PASSWORD AND DATABASENAME
   ```sh
   DATABASE_URL="mysql://USERNAME:PASSWORD@127.0.0.1:3306/DATABASENAME?charset=utf8mb4"
   ```
   
4. Create database
   ```sh
   php bin/console doctrine:database:create
   ```

5. Migrate data to database
   ```sh
   php bin/console doctrine:migrations:migrate
   ```
   
6. Run application
   ```sh
   composer run build 
   symfony server:start
   then visit page at https://127.0.0.1:8000
   ```   


## Enabled Bundles
Concern        | Bundles
------------------------  | ---
security  | [`symfony/security-bundle`](https://github.com/symfony/security-bundle)
reset-password  | [`symfonycasts/reset-password-bundle`](https://github.com/SymfonyCasts/reset-password-bundle)
verify-email  | [`symfonycasts/verify-email-bundle`](https://github.com/SymfonyCasts/verify-email-bundle)
mailer  | [`symfony/mailer`](https://github.com/symfony/mailer)
http-client  | [`symfony/http-client`](https://github.com/symfony/http-client)
maker-bundle  | [`symfony/maker-bundle`](https://github.com/symfony/maker-bundle)
asset mapper  | [`symfony/asset-mapper`](https://github.com/symfony/asset-mapper)
twig engine  | [`symfony/twig-pack`](https://github.com/symfony/twig-pack)

## Screenshots
### Login page
![img_login.png](img_login.png)
<br/><br/>
### Register page
![img_register.png](img_register.png)

<!-- CONTACT -->
## Contact

Ricel Quispe - [@linkedin](https://www.linkedin.com/in/ricelquispe) - ricel@prodeimat.ch

Project Link: [https://github.com/ricelq/pr_security_assetmapper_s7](https://github.com/ricelq/pr_security_assetmapper_s7)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
