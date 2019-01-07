# Passport JS Exercise

## STEP 1

<ul>
<li>Create a new Postgres database with "users" table.</li>
<li>The table should have at least the following columns:</li>
<ul>
<li>id</li>
<li>email</li>
<li>password</li>
</ul>
</ul>

## STEP 2

Write an express server that serves a simple website at the path '/'.

<ul>The website should have: 
<li>a login form</li>
<li>a logout button</li>
<li>h1 tag that will either say "Logged in" or "Not Logged in"</li>
</ul>

## STEP 3

Incorporate PassportJS into your application (use the demo app in the resources folder as a reference). Implement a LocalStrategy that will let users create accounts and log in with their email address and a password. The "login" and "logout" buttons on your website should trigger the "auth/login" and "auth/logout" routes respectively. Use EJS to render either "Logged in" or "Not Logged in" to the webpage.
