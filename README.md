# python-web-microblog

This web app was developed following the following course: https://www.udemy.com/share/103Ryi3@jE-zrfKPXPBJQCTzapwxZwi3WjkcANHKNywhm8ytu3wSaLlArR5AGYiBPDRNhiIIbg==/
I left it practically unchanged but I will add my own modifications later on. To list some possible changes:
  - Minor fixes like populating the entries' section from recent to old, and making sure the footer appears in the bottom of the page.
  - Dark mode.
  - Title input field.
  - The possibility to append images to entries (probably by providing an external link rather than storing it in the DB)


The web app built using Flask, a light web framework of python.
There are extra files ".env.example", "procfile" and "runtime.txt" that allows Heroku deploy this app, this is also true for app.py, where the create_app()
function that wraps the whole app is required for deployment, a library called gunicorn is also needed, so if you want to mess around with this code all the named elements are not required 
to run the app, even so, you might encounter issues if you run the app using gunicorn to call it.

On another note it's recommended to run the app in a virtual enviroment.
