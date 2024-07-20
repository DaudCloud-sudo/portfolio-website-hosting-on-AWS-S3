# Portfolio Website Hosting on AWS S3

Welcome to my personal project repository where I’m hosting my portfolio website using Amazon S3. This project is part of my ongoing effort to polish my skills in cloud computing and website hosting. Below, you'll find details about the setup, deployment, and usage of this repository.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Setup and Deployment](#setup-and-deployment)
  - [Step 1: AWS Management Console](#step-1-aws-management-console)
  - [Step 2: Sign In or Create an AWS Account](#step-2-sign-in-or-create-an-aws-account)
  - [Step 3: Secure Your AWS Account](#step-3-secure-your-aws-account)
  - [Step 4: Access S3](#step-4-access-s3)
  - [Step 5: Create an S3 Bucket](#step-5-create-an-s3-bucket)
  - [Step 6: Upload Website Content](#step-6-upload-website-content)
  - [Step 7: Configure S3 Bucket for Static Website Hosting](#step-7-configure-s3-bucket-for-static-website-hosting)
  - [Step 8: Make Objects Public](#step-8-make-objects-public)
- [Viewing Your Website](#viewing-your-website)

## Project Overview

This repository contains the static content for my portfolio website. I’ve used AWS S3 to host this static site, and it’s been a great way to deepen my understanding of cloud-based hosting solutions. The site showcases my work, skills, and projects, and serves as a hands-on application of my cloud and web development knowledge.

## Project Structure

Here’s a brief overview of the project's structure:

- **`index.html`**: The main HTML file for the homepage. This is the entry point of my portfolio website.
- **`css/`**: Directory containing CSS files for styling the website. I've organized the stylesheets here to keep everything neat.
- **`js/`**: Directory for JavaScript files that add interactivity to my site. Scripts for animations and user interactions are included here.
- **`images/`**: Folder containing image assets used throughout the website. This includes photos, icons, and other visual elements.
- **`certificates-degrees-achievements/`**: This folder contains all the certs and achievements of mine.
- **`resume.pdf/`**: This is my resume to get accessed from the website.


## Setup and Deployment

To get this site up and running on AWS S3, follow these steps:

### Step 1: AWS Management Console

Go to the AWS Management Console: [Manage AWS Resources - AWS Management Console](https://aws.amazon.com/console/).

![image](https://github.com/user-attachments/assets/bd31eaa7-9474-4952-b9a9-d3549d4cc90d)

### Step 2: Sign In or Create an AWS Account

- If you already have an AWS account, sign in.
- If you don't have an AWS account, create one. AWS provides detailed instructions for creating an account.

![image](https://github.com/user-attachments/assets/c20c22b2-4c9e-4b69-a60a-818613fc7050)


### Step 3: Secure Your AWS Account

For additional security:
- Use an admin account with limited access instead of the root account.
- Enable two-factor authentication (2FA).

### Step 4: Access S3

1. Navigate to the AWS Management Console.
2. Use the search bar to search for "S3".
3. Click on "S3" to access the S3 Dashboard.

![image](https://github.com/user-attachments/assets/bd2e1a96-0fd8-44f8-b4c7-f6476b1764f0)


### Step 5: Create an S3 Bucket

1. Click on "Create bucket".
2. Configure your bucket:
   - **Bucket Name**: Choose a unique name for your bucket.
   - **Enable ACLs**: Access Control Lists (ACLs) help manage permissions. Enable ACLs to control access to your bucket and its objects.
   - **Ownership**: Set to root/admin account.
   - **Public Access**: Untick the block all public access to make the bucket public.
   - **Bucket Versioning**: Enable versioning to keep multiple versions of an object in one bucket.

3. Click on "Create bucket".
4. After creation, navigate to the Bucket section and you will see your newly created bucket.

![image](https://github.com/user-attachments/assets/b004d414-27ab-4c56-9f3b-a720100a94d8)


### Step 6: Upload Website Content

1. Open your newly created bucket.
2. Click on "Upload".
3. Upload all your website files (HTML, CSS, JS, images, etc.).

![image](https://github.com/user-attachments/assets/d5a37e5a-788d-4870-a118-417852742e92)

### Step 7: Configure S3 Bucket for Static Website Hosting

1. Go to the "Properties" tab of your bucket.
2. Scroll down to the "Static website hosting" section.
3. Click on "Edit".
4. Configure the following settings:
   - **Static web hosting**: Enable
   - **Hosting type**: Host a static website
   - **Index document**: Enter `index.html`

![image](https://github.com/user-attachments/assets/d9a79912-84a5-41d3-a460-031a761fec6d)

5. Save the settings.

### Step 8: Make Objects Public

By default, objects (HTML, CSS, JS files) are private. To make them public:

1. Go to the "Objects" tab in your bucket.
2. Select the checkboxes next to your `index.html` file and other website assets.
3. Click on "Actions" and select "Make public using ACL".
4. Confirm the action.

![image](https://github.com/user-attachments/assets/1eb94cbf-7ba9-46c6-bcb0-d3640207ac72)

## Viewing Your Website

1. Go to the "Properties" tab of your bucket.
2. Scroll down to the "Static website hosting" section.
3. Note the endpoint URL provided. This is your live website URL.
4. Open the URL in a browser to view your hosted website.
5. Wohoo, my website is live.

![image](https://github.com/user-attachments/assets/ea6abe92-a6df-426a-b1d1-5f12e470b1cb)


By following these steps, you have successfully hosted a static website on AWS S3. This method is cost-effective and scalable for hosting static websites.

# Connect with Me

- [GitHub](https://github.com/DaudCloud-sudo)
- [LinkedIn](https://www.linkedin.com/in/shahzaib-daud-computer-engineer/)
- [Medium](https://medium.com/@s.daud)
- [Facebook](https://www.facebook.com/shahzaibdaud42/)
