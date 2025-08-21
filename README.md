![Github Forks](https://img.shields.io/github/forks/Yixin0313/personal-homepage-template?style=flat)
![Github Stars](https://img.shields.io/github/stars/Yixin0313/personal-homepage-template?style=flat)
![License](https://img.shields.io/github/license/Yixin0313/personal-homepage-template)

#  A general-purpose template: suitable for both academic and professional use.

## Introduction

This is a **general-purpose personal website template**, modified from [Sen Li's academic template](https://github.com/senli1073/senli1073.github.io).  

I have added a **work experience section**, making it more practical for programmers and job seekers.

## Getting Start
### 1. Fork this repository

The repository name should be `<username>.github.io`, which will also be your website's URL.


### 2. Edit page content
(1) Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) Modify the content of each section, which corresponds to `contents/*.md`.

(3) Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) Push it: 
```
git commit -am 'init'
git push
```


### 3. Enjoy

Fire up a browser and go to `https://<username>.github.io`



## License

Copyright Yixin Huang, 2025. Licensed under an MIT license. You can copy and mess with this template.
