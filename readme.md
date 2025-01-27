# Personal Portfolio Website

![Design Preview](images/design.png "Design Preview")

## Project Overview
This project involved creating a personal portfolio website to showcase my skills, experience, and projects. The website is hosted on AWS and utilizes a variety of cloud services to ensure scalability, reliability, and performance. Additionally, I implemented a CI/CD pipeline using GitHub Actions to automate deployments, ensuring seamless updates to the website.

## Objectives
- Create a professional and responsive portfolio website.
- Gain hands-on experience with AWS services and CI/CD practices.
- Implement a serverless architecture for backend functionality.
- Ensure global accessibility and fast load times.
- Automate deployment processes for efficiency.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript (using HTML5Up template).
- **Backend**: AWS Lambda, API Gateway, DynamoDB.
- **Hosting & Deployment**: AWS S3, CloudFront.
- **Domain & Routing**: GoDaddy (domain purchase), Route 53 (DNS routing).
- **SSL/TLS Certificate**: AWS Certificate Manager (ACM).
- **Source Code Management**: GitHub.
- **CI/CD Pipeline**: GitHub Actions for automated deployments to S3.

## Key Features
- **Static Website Hosting**: Used AWS S3 to store and serve static files (HTML, CSS, JS).
- **Global Content Delivery**: Configured CloudFront to distribute the website to edge locations.
- **Contact Form Backend**: Created a serverless backend using AWS Lambda and API Gateway.
- **Custom Domain**: Purchased a domain via GoDaddy and configured DNS routing using Route 53.
- **SSL/TLS Certificate**: Secured the website with HTTPS using AWS Certificate Manager (ACM).
- **Responsive Design**: Used a pre-designed template from HTML5Up for a modern and mobile-friendly design. (Also modified and created some new templates with the help of AI.)
- **Source Code Management**: Used GitHub for version control.
- **Continuous Deployment**: Set up GitHub Actions to automate deployments to S3.

## Challenges & Solutions
| **Challenge**                                      | **Solution**                                                                 |
|----------------------------------------------------|------------------------------------------------------------------------------|
| Ensuring low latency for global users.             | Used CloudFront to cache content at edge locations.                          |
| Implementing a serverless backend for the contact form. | Leveraged Lambda and API Gateway for a scalable solution.                   |
| Automating deployments to S3.                      | Configured GitHub Actions for CI/CD.                                         |
| Securing the website with HTTPS.                   | Used AWS Certificate Manager (ACM) to provision and manage SSL/TLS certificates. |

## Outcome
- Successfully deployed a fully functional portfolio website.
- Gained practical experience with AWS services, serverless architecture, and CI/CD pipelines.
- Achieved fast load times and global accessibility.
- Secured the website with HTTPS using AWS Certificate Manager (ACM).
- Streamlined the development process with automated deployments using GitHub Actions.

## Future Improvements
- Add authentication and user management using AWS Cognito.
- Integrate a blog section using AWS Amplify.
- Implement analytics using AWS CloudWatch or Google Analytics.
- Enhance the CI/CD pipeline to include testing and staging environments.

---

**Note**: If you'd like a full-length video on this project, feel free to `send me a message` through `Get in Touch` section on my website. I'd love to hear your feedback and suggestions!
