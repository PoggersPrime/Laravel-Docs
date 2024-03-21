# Laravel Artisan Commands

# General Commands

• `php artisan`: Show a list of all available commands.
• `php artisan help <command>`: Display help for a specific command.

# Development Server

• `php artisan serve`: Start the Laravel development server.

# Application Configuration

• `php artisan config:cache`: Cache the application configuration for faster loading.
• `php artisan config:clear`: Clear the configuration cache.
• `php artisan env`: Display the current application environment.

# Database

• `php artisan migrate`: Run all pending migrations.
• `php artisan migrate:install`: Create the migration repository.
• `php artisan migrate:refresh`: Rollback all migrations and re-run them.
• `php artisan migrate:reset`: Rollback all migrations.
• `php artisan migrate:rollback`: Rollback the last database migration.
• `php artisan migrate:status`: Show the status of each migration.
• `php artisan make:migration <name>`: Create a new migration file.
• `php artisan make:seed <name>`: Create a new seeder class.
• `php artisan db:seed`: Seed the database with records.
• `php artisan db:wipe`: Drop all tables, views, and types.

# Models, Views, and Controllers

• `php artisan make:model <name>`: Create a new Eloquent model class.
• `php artisan make:controller <name>`: Create a new controller class.
• `php artisan make:middleware <name>`: Create a new middleware class.
• `php artisan make:policy <name>`: Create a new policy class.
• `php artisan make:provider <name>`: Create a new service provider class.
• `php artisan make:resource <name>`: Create a new resource class.
• `php artisan make:command <name>`: Create a new Artisan command.

# Authentication and Authorization

• `php artisan make:auth`: Scaffold basic login and registration views and routes.
• `php artisan auth:clear-resets`: Flush expired password reset tokens.
• `php artisan passport:install`: Install Laravel Passport for API authentication.
• `php artisan make:auth`: Scaffold basic login and registration views and routes.
• `php artisan make:policy <name>`: Create a new policy class.
• `php artisan make:request <name>`: Create a new form request class.
• `php artisan passport:client`: Create a client for issuing access tokens.

# Cache

• `php artisan cache:clear`: Flush the application cache.
• `php artisan cache:table <table>`: Create a migration for the cache database table.

# Queue

• `php artisan queue:work`: Start processing jobs on the queue.
• `php artisan queue:listen`: Listen to a given queue.
• `php artisan queue:restart`: Restart queue worker daemons after their current job.
• `php artisan queue:retry <id>`: Retry a failed queue job.
• `php artisan queue:failed`: List all of the failed queue jobs.

# Testing

• `php artisan test`: Run the application tests.
• `php artisan dusk`: Run the Laravel Dusk browser tests.

# Route

• `php artisan route:list`: List all registered routes.
• `php artisan route:cache`: Create a route cache file for faster route registration.
• `php artisan route:clear`: Remove the route cache file.

# Event

• `php artisan event:list`: List all events and their listeners.
• `php artisan event:generate`: Generate the missing events and listeners based on registration.

# Other Useful Commands

• `php artisan storage:link`: Create a symbolic link from "public/storage" to "storage/app/public".
• `php artisan optimize`: Optimize the framework for better performance.
• `php artisan down`: Put the application into maintenance mode.
• `php artisan up`: Bring the application out of maintenance mode.
• `php artisan make:job <name>`: Create a new job class.
• `php artisan make:event <name>`: Create a new event class.
• `php artisan make:listener <name>`: Create a new event listener class.

