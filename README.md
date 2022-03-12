### :rocket Udacity Challenge

This repository is meant to be used as a challenge for Udacity.

I should cover
-	Simple Frontend ✔
- RestAPI Backend ✔
- Database ✔
- Deploy the application to AWS ✔
- Make sure to apply the CI/CD principles ✔


## The challenge

In this project, you will create a simple Bookstore web application using this dataset Goodreads-books

The architecture
- Django Web application frame work
- PostgreSQL for database
- PGadmin
- REST/HTTTP
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

The CI/CD
- GitHub
- GitHub Actions
- AWS 
- Docker
- Docker Compose
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)


## Application Endpoint
You can visit the app using this link [Book Store](http://ec2-44-202-33-153.compute-1.amazonaws.com/).

You can send HTTP request for the API using the below collection
[Book Store Collection](http://ec2-44-202-33-153.compute-1.amazonaws.com/).

EndPoints:
GET /
GET /api/books/
POST /api/books/
DELETE /api/books/
GET /api/books/$ID/
PUT /api/books/$ID/
DELETE /api/books/$ID/

### Requirements
- Docker

#### Run locally

```bash
docker compose up -d
```
And you can visit the application on localhost:80
