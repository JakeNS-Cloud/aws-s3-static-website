# S3 Static Website Hosting

Overview
This project demonstrates how to host a simple static website using Amazon S3. The site was built with basic HTML and made publicly accessible using S3 static website hosting and IAM-controlled bucket policies, with a focus on simplicity and cost efficiency.

AWS Services Used

- Amazon S3 
- IAM
- S3 Bucket Policy
- HTML

Implementation Summary

- Created a basic `index.html` file for the website
- Uploaded the HTML file to an S3 bucket
- Enabled S3 static website hosting
- Disabled block public access at the bucket level
- Applied a bucket policy allowing public `GetObject` access
- Followed least-privilege security principles

Cost Considerations

  - No servers or compute resources required
  - S3 static hosting provides a low-cost solution for simple websites

Possible Future Enhancements
  - Enable HTTPS using CloudFront
  - Automate deployment using Terraform or CloudFormation
  - A custom domain could be configured using Route 53, but this was intentionally omitted to keep the project budget-friendly.

Key Takeaways: 

  - Hosted a static website without servers
  - Configured secure public access using IAM and bucket policies
  - Applied least-privilege security principles
  - Designed a simple, cost-effective cloud solution
  - Developed basic HTML skills to design the site

More of my work on my portfolio page! https://github.com/JakeNS-Cloud/JakeNS-Portfolio 
