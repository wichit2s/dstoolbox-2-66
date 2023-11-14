# wichit2s/dstoolbox-2-66
private project for ds toolbox class.

## 07/11/2566

* ติดตั้ง scoop.sh

* ติดตั้ง github-cli 

        scoop install git
        #scoop bucket add main
        scoop install gh
    
* สร้างสภาพแวดล้อมใหม่

        python -m venv venv
        venv\Scripts\activate

* ติดตั้ง package 

        pip install django


## 14/11/2566

* สร้าง github repository ของตัวเอง 

        Username/dstoolbox-2-66-66xxxxxxxx

* เพิ่ม wichit2s เป็น collaborator 

* การเข้าใช้งาน github

        gh auth login
        gh repo clone Username/dstoolbox-2-66-66xxxxxxxx

* เริ่มเขียน markdown 

* [การเขียนเอกสารบน Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

* github.com/cookiecutter/cookiecutter-django 

    venv\Scripts\activate
    pip install django pre-commit
    pip install cookiecutter
    cookiecutter gh:cookiecutter/cookiecutter-django

```
Do you want to re-use the existing version? [y/n] (y):
  [1/27] project_name (My Awesome Project): dssiprj
  [2/27] project_slug (dssiprj):
  [3/27] description (Behold My Awesome Project!): DSSI Senior Project
  [4/27] author_name (Daniel Roy Greenfeld): Wichit Sombat
  [5/27] domain_name (example.com): ubu.ac.th
  [6/27] email (wichit-sombat@ubu.ac.th): wichit.s@ubu.ac.th
  [7/27] version (0.1.0):
  [8/27] Select open_source_license
    1 - MIT
    2 - BSD
    3 - GPLv3
    4 - Apache Software License 2.0
    5 - Not open source
    Choose from [1/2/3/4/5] (1): 1
  [9/27] Select username_type
    1 - username
    2 - email
    Choose from [1/2] (1): 2
  [10/27] timezone (UTC): Asia/Bangkok
  [11/27] windows (n):
  [12/27] Select editor
    1 - None
    2 - PyCharm
    3 - VS Code
    Choose from [1/2/3] (1): 3
  [13/27] use_docker (n): y
  [14/27] Select postgresql_version
    1 - 15
    2 - 14
    3 - 13
    4 - 12
    5 - 11
    6 - 10
    Choose from [1/2/3/4/5/6] (1): 1
  [15/27] Select cloud_provider
    1 - AWS
    2 - GCP
    3 - Azure
    4 - None
    Choose from [1/2/3/4] (1): 4
  [16/27] Select mail_service
    1 - Mailgun
    2 - Amazon SES
    3 - Mailjet
    4 - Mandrill
    5 - Postmark
    6 - Sendgrid
    7 - SendinBlue
    8 - SparkPost
    9 - Other SMTP
    Choose from [1/2/3/4/5/6/7/8/9] (1): 9
  [17/27] use_async (n):
  [18/27] use_drf (n): y
  [19/27] Select frontend_pipeline
    1 - None
    2 - Django Compressor
    3 - Gulp
    4 - Webpack
    Choose from [1/2/3/4] (1):
  [20/27] use_celery (n):
  [21/27] use_mailpit (n):
  [22/27] use_sentry (n):
  [23/27] use_whitenoise (n): y
  [24/27] use_heroku (n):
  [25/27] Select ci_tool
    1 - None
    2 - Travis
    3 - Gitlab
    4 - Github
    5 - Drone
    Choose from [1/2/3/4/5] (1):
  [26/27] keep_local_envs_in_vcs (y):
  [27/27] debug (n): y
 [SUCCESS]: Project initialized, keep up the good work!
```
