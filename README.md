# Flipkart-Review-Scrapper
## Table of Content
- Introduction
- Demo 
- File Structure
- Installation
- Deployement on AWS

## INTRODUCTION

**Flipkart Website of Particual Product** ![Screenshot (64)](https://user-images.githubusercontent.com/62636740/127958047-95472f1f-d55e-4a19-b8bd-d47746c8bd3b.png)

In thses project we extarct the flipkart website. In that we select a particular product such  as apple iphone 7. Now from that we can extract the reviews and rating of that phone  availiable from the single page. You can give any mobile name and you get reviews of that mobile which are availiable on the 1st page. In the given project we extact the below given information such as,

1. Name Of That Person
2. Whether It Is Certified Buyer or Not
3. Location
4. Month of Review
5. Ratings
6. Comment Head
7. Comment

## DEMO
In The Demo Section We Are Showing You The Deployment on Both The Enviornment Local as Well as Server.

**1. Local Server**

![Screenshot (63)](https://user-images.githubusercontent.com/62636740/127959105-ede751df-1f5c-4cd2-a2b6-393b6924ae81.png)

**2. Heroku**

![Screenshot (65)](https://user-images.githubusercontent.com/62636740/128126420-ad695180-dc00-492d-a79c-55bf3e219bd1.png)

## FILE STRUCTURE

```
Project
|
|
Static--|
|       |
|       |--CSS--|
|               |---main.css
|               |---style.css
|
templates--|
|          |---base.html
|          |---index.html
|          |---result.html
|
|Procfile
|
|Raw File.ipnyb
|
|app.py
|
|gitignore
|
|requirements.txt
|
|runtime.txt
```

## INSTALLTION
The Code is written in Python 3.7.11. If you don't have Python installed you can find it [your link here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) the repository.
```bash
pip install -r requirements.txt
```

## DEPLOYMENT ON AWS [ELASTIC BEANSTALK] & HEROKU

Sign Into AWS Management Console & Heroku With The Given Link

[AWS Management Console Link](https://aws.amazon.com/console/)

[Heroku Login Link ](https://signup.heroku.com/login)

## TECHNOLOGY USED
![flask-logo](https://user-images.githubusercontent.com/62636740/90309868-ebae7480-df09-11ea-8750-6ca4445dfd8f.png)

![ AWS Elastic Beanstalk](https://user-images.githubusercontent.com/62636740/127960907-a6a13a42-3bdb-41f7-843d-493c7e168bd4.png)

![heroku-logo](https://user-images.githubusercontent.com/62636740/128127046-dbcc862b-1312-4099-ae3c-bd27b8371a5a.png)

