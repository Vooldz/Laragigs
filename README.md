# Laravel Jobs

## Description
This Laravel project is a platform for connecting developers with job opportunities. Businesses can post job vacancies, and developers can browse through these opportunities to find freelance work or full-time employment. Our goal is to simplify the job search process for developers and streamline recruitment for businesses.

## Installation
To install this project, follow the steps below:

1. Clone the repository:
```bash
git clone https://github.com/Vooldz/Laragigs.git
```
2. Navigate to the project directory:
```bash
cd Laragigs
```
3. Install dependencies:
```bash
composer install
```
4. Copy .env.example` to `.env`:
```bash
cp .env.example .env
```
5. Generate app key:
```bash
php artisan key:generate
```
6. Run migrations:
```bash
php artisan migrate --seed
```
7. Start the server:
```bash
php artisan serve
```
8. Link the storage folder to public so uploaded files are accessible:
```bash
php artisan storage:link
```


## Usage
Once the server is running, you can access the platform by navigating to ```http://localhost:8000``` in your web browser. From there, you can create an account, post a job, or search for jobs.

## Contributing
We welcome contributions from the community.

