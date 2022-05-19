# Luftborn Database Service
A Database Service manager

# Installation
* Run ``composer require luftborn/database-service``.
* Go to `composer.json` search for `autoload` 
  <br>Add to `psr-4` this line <br> `"Luftborn\\DatabaseService\\": "vendor/luftborn/database-service/src"`.
* Go to `config/app.php`  add to `providers` this line `\Luftborn\DatabaseService\DatabaseServiceProvider::class`

# Usage

* import the required File
`use Luftborn\DatabaseService\Models\Users`. 
