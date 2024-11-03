# Social Media Post Composition and Trending Hashtags Analysis Application

## Project Description
In the era of social media dominance, users crave platforms that offer seamless posting experiences while providing insights into trending topics. To address this need, we aim to develop a Streamlit application that allows users to compose and publish posts, similar to popular social media platforms. This application integrates with AWS Lambda and DynamoDB to facilitate post processing and hashtag analysis.

## Features
- **Post Composition**: Users can write posts containing text and hashtags using the provided interface.
- **Post Submission**: Upon clicking the "Post" button, the application triggers a backend process that sends the post content to AWS Lambda.
- **AWS Lambda Integration**: AWS Lambda receives the post content, parses it, extracts hashtags and post text, and stores this data in DynamoDB.
- **Trending Hashtags**: Users can view trending hashtags by clicking the "Show Trending Hashtags" button, which analyzes the DynamoDB table to aggregate and identify popular hashtags.
- **Dynamic Updates**: The trending hashtags section updates dynamically as new posts are made and analyzed, providing real-time insights into trending topics.
- **User Interface**: The application features an intuitive and user-friendly interface, making it easy for users to compose posts and explore trending hashtags.

## Problem Scope
- Develop a Streamlit application that enables users to compose and publish posts containing text and hashtags.
- Integrate the application with AWS Lambda to process posts and store data in DynamoDB.
- Implement functionality to analyze the DynamoDB table and identify trending hashtags.
- Ensure real-time updates of trending hashtags as new posts are submitted.

## Installation

### Prerequisites
- Python 3.6 or later
- AWS Account with permissions for Lambda and DynamoDB
- Streamlit library
- Boto3 library for AWS integration

