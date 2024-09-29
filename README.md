# Advanced-Django-Ecommerce-Web-Application



70% of the project has been finished.

Features (available, more coming-up with the left 30%):
1. Advanced custom user model with email JWT verification.
2. Dynamic web pages
3. Product store with product variations
4. Cart functionalities
5. Order management and confirmation emails
6. Payment gateway integration (PayPal) etc.

## Run Project (on Windows)

> Note: You need to have Python installed on your system.

**Open CMD in the project directory and follow the commands below-**

1. **Setup Virtual Environment:**
    ```sh
    python -m venv env
    ```
    
2. **Head to `env/Scripts` directory:**
    ```sh
    cd env/Scripts
    ```

3. **Activate the environment:**
    ```sh
    activate
    ```

4. **Get back to Base Directory:**
    ```sh
    cd../..
    ```

5. **Run Server:**
    ```sh
    python manage.py runserver
    ```

## Database Migration
1. **Make migrations:**
    ```sh
    python manage.py makemigrations
    ```

2. **Migrate:**
    ```sh
    python manage.py migrate
    ```

## Admin User Creation
1. **Create SuperUser:**
    ```sh
    python manage.py createsuperuser
    ```
