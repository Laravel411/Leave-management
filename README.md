# Create README file with instructions

# echo "Employee Leave Management System"

Setup Instructions

1. Clone the repository.
2. Run `composer install` to install dependencies.
3. Set up your `.env` file with database credentials.
4. Run `php artisan migrate` to set up the database.
5. Run `php artisan db:seed` to populate initial data.
6. Run the server using `php artisan serve`.

## Architectural Choices
This application uses Laravel's built-in functionalities for authentication, migrations, and seeding.

## Assumptions
- MySQL is used as the database.
- Basic role functionality (employee and admin).

" > README.md

# Commit README.md
git add README.md
git commit -m "Create README file with setup instructions"

# Push to GitHub 
git remote add origin https://github.com/Laravel411/Leave-management.git
git branch -M main
git push -u origin main

echo "Project setup complete and pushed to GitHub."
