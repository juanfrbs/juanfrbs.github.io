+++
title = 'Artisan commands'
+++

## List of Artisan commands

### **Laravel Artisan Command Cheatsheet**

![Artisan Cheatsheet](/images/cheatsheets/artisanCheatsheet.png) 

### **🛠 General Artisan Commands**

| Command                      | Description                         |
| ---------------------------- | ----------------------------------- |
| `php artisan list`           | Show all available Artisan commands |
| `php artisan help <command>` | Get help for a specific command     |
| `php artisan tinker`         | Open Laravel's interactive console  |

### **🎭 Application Management**

| Command             | Description                                   |
| ------------------- | --------------------------------------------- |
| `php artisan serve` | Start a local development server              |
| `php artisan down`  | Put the application into maintenance mode     |
| `php artisan up`    | Bring the application out of maintenance mode |

### **🚀 Database & Migrations**

| Command                            | Description                         |
| ---------------------------------- | ----------------------------------- |
| `php artisan migrate`              | Run pending migrations              |
| `php artisan migrate:rollback`     | Undo the last migration batch       |
| `php artisan migrate:reset`        | Roll back all migrations            |
| `php artisan db:seed`              | Seed database with test data        |
| `php artisan migrate:fresh --seed` | Refresh database and re-run seeders |

### **⚙️ Model & Controller Management**

| Command                                        | Description                                             |
| ---------------------------------------------- | ------------------------------------------------------- |
| `php artisan make:model <ModelName>`           | Create a new model                                      |
| `php artisan make:controller <ControllerName>` | Create a new controller                                 |
| `php artisan make:model <ModelName> -mcr`      | Create a model with migration, controller, and resource |

### **🔐 Authentication & Authorization**

| Command                                        | Description               |
| ---------------------------------------------- | ------------------------- |
| `php artisan make:middleware <MiddlewareName>` | Generate a new middleware |
| `php artisan make:policy <PolicyName>`         | Generate a new policy     |

### **📜 Route & Cache Management**

| Command                    | Description                             |
| -------------------------- | --------------------------------------- |
| `php artisan route:list`   | Show all registered routes              |
| `php artisan cache:clear`  | Clear application cache                 |
| `php artisan config:clear` | Clear configuration cache               |
| `php artisan route:cache`  | Cache the routes for better performance |

### **🛠 Custom Commands**

| Command                                  | Description                     |
| ---------------------------------------- | ------------------------------- |
| `php artisan make:command <CommandName>` | Create a custom Artisan command |

### External resources

[Artisan Console](https://laravel.com/docs/12.x/artisan)

[artisan.page](https://artisan.page/)

