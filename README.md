# Obituary Generator
## Overview
This is a [website](https://obituary-generator.netlify.app) that generates obituaries using the power of ChatGPT prompting. All you have to do is input a name, a picture, and its date to get a formatted graphical obituary on the topic! The text obituary is generated from the OpenAI model `text-curie-001`. This project was part of a final assignment in course ENSF 381 Winter 2023 in collaboration with [Shayyan Asim](https://github.com/ShayyanAsim).

## Technologies Used
### Frontend
Used React components
### Backend
Connected AWS services such as Lambda functions (Python), DynamoDB, S3, Amazon Polly for automated voices, and Step Function to linearize processes. Cloudinary holds the images and voices sound bytes, and the OpenAI API is used to get the text obituaries.
