# passport

passport js exercise

## STEP 1

<ul>
<li>Create a new Postgres database with "users" table.</li>
<li>The table should have at least the following columns:
</li>

id
email
password

## STEP 2

Write an express server that serves a simple website at the path '/'. The website should have a login form, a logout button, as well as an h1 tag that will either say "Logged in" or "Not Logged in".

## STEP 3

Incorporate PassportJS into your application (use the demo app in the resources folder as a reference). Implement a LocalStrategy that will let users create accounts and log in with their email address and a password. The "login" and "logout" buttons on your website should trigger the "auth/login" and "auth/logout" routes respectively. Use EJS to render either "Logged in" or "Not Logged in" to the webpage.
