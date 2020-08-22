
Newspaper web application (Django for beginners book)

- Created new project newspaper_project
- Created new app - users
- Created model CustomUser(AbstractUser) with additional field - age
- Updated UserCreationForm and UserChangeForm in form.py
- Created class CustomUserAdmin(UserAdmin)
- Created feature to register on the website (login/logout) 
- Creted 4 html templates (base, login, home, signup)
- Created view class SignUp
- Added additional field when user signup (email address)
- Created new app Pages
- Created HomePageView class to display home page 'home.html'
- Runned tests to check the status code, correct urls and correct templates
- Added Bootstrap, created new navbar on the base template
- Installed django-crispy-forms
- Updated Sign Up form to crispy
- Added features to change user password
- Added feature to reset password with console 
- Added new app - articles (CRUD)
- Added feature to edit/see detail of articles/ delete
- Added feature to add new article
- Updated ArticleCreateView, added feature to automatically set author of the article to user which login 
- Imported Mixin to check login status and redirect user to login page when user try to create/see the list of articles/see detail page/update/delete articles
- Added feature to leave a comments in django-admin panel
