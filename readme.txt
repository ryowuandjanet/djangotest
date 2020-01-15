create a new repository on the command line
echo "# djangotest" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ryowuandjanet/djangotest.git
git push -u origin master


push an existing repository from the command line
git remote add origin https://github.com/ryowuandjanet/djangotest.git
git push -u origin master

在django_project/email_info.py的密碼要填入gmail的密碼
EMAIL_HOST_PASSWORD = "5*******L****"