# Static Website with CI/CD Pipeline

This repository contains the source code for a simple static website, which is deployed using a **CI/CD pipeline** implemented with **AWS EC2**, **S3**, and **GitHub Pages**. The pipeline automates the deployment process and has decreased the deployment time by 50%.

## Live Links

- **GitHub Pages**: [here](https://riteshzode.github.io/staticwebsite.github.io/)
- **AWS S3**: [here](http://staticwebsitelive.s3-website-us-east-1.amazonaws.com/)

## Features

- **Simple Static Website**: The website is built using HTML, CSS, and JavaScript.
- **CI/CD Pipeline**: Automates the deployment of the website to AWS EC2, S3, and GitHub Pages.
- **Fast Deployment**: With the automated pipeline, deployment time has been reduced by 50%.
- **GitHub Actions**: The pipeline leverages GitHub Actions for continuous integration and delivery.

## Technologies

- **HTML**: For the structure of the website.
- **CSS**: For styling and layout.
- **JavaScript**: For interactivity.
- **AWS EC2**: For hosting the static website using Nginx.
- **AWS S3**: For storing and serving static assets (like images, CSS, JS).
- **GitHub Pages**: For hosting the static site via GitHub's free hosting service.
- **GitHub Actions**: For CI/CD pipeline automation.

## File Structure
```
    ├── .github/
    │   └── workflows/
    │       └── workflows.yml            # GitHub Actions multiple CI/CD pipeline configuration
    ├── index.html                       # Main HTML page
    ├── main.js                          # JavaScript for interactivity
    ├── policy.txt                       # AWS policy for  public read access
    ├── styles.css                       # CSS for the website styling
    ├── target-file.csv                  # Example data file for website or backend use
    └── README.md                        # This file 
```


