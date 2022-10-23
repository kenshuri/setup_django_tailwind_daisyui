# Minimal template to set-up a Django project with TailwindCSS and daisyUI

As described, this code will set-up a Django Project with tailwindCSS and daisyUI. The auto-reload feature is also included.

The code for this was vastly inspired from a stackoverflow answer on [How to use TailwindCSS with Django?](https://stackoverflow.com/questions/63392426/how-to-use-tailwindcss-with-django#63392427). You can have a look ay my [blog post](https://blog.kenshuri.com/posts/001_setup_django_tailwind_daisyui.md) for some details.

## Set-up the project

To set-up the project from scratch, run the following commands in your terminal.

```shell
git clone https://github.com/kenshuri/setup_django_tailwind_daisyui.git
cd setup_django_tailwind_daisyui
python -m virtualenv venv
pip install -r requirements.txt
cd jstoolchains
npm install
```

You're good to go my friend!

## Start your project 

To see your project in action, open 2 terminals.

In the first terminal run:
```shell
cd setup_django_tailwind_daisyui
cd jstoolchains
npm run tailwind-watch
```

In the second terminal run:
```
cd setup_django_tailwind_daisyui
python manage.py runserver
```

As prompted, open the page http://127.0.0.1:8000/ and enjoy 🚀

Note that changes in your html template `blogApp\templates\blogApp\index.html` automatically updates what you see in your browser.


