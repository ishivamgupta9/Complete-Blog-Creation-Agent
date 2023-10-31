# Complete Blog Creation Agent APP

This is a Streamlit web application for generating blog topics and content using the OpenAI GPT-3 model. You can use this app to generate blog topics and write blog content on those topics. Below is an overview of the features and functionality of the app:

## Getting Started

### Prerequisites

Before you can use this app, you need to set up a few things:

1. **Environment Variables**: Create a `.env` file in the root directory of the app and add your OpenAI API key as follows:
    
Replace `your_openai_api_key_here` with your actual OpenAI API key. This key is necessary to interact with the GPT-3 model.

2. **Dependencies**: Install the necessary Python packages by running:

```bash
pip install -r requirements.txt
```
This will install the required libraries and dependencies for the application.

## Running the App

You can run the app by executing the following command:

```bash
streamlit run blog_generation_app.py
```
This will start the Streamlit app in your web browser.

## Features

1. **Category Input**

   You can enter a category for your blog. This category will be used to generate related blog topics.

2. **Topic Generation**

   The app uses OpenAI's GPT-3 model to generate blog topics based on the provided category.

3. **Topic Approval**

   You can review the generated topics and choose to approve or disapprove them. If you disapprove, you can request a new topic.

4. **Blog Content Generation**

   Once you approve a topic, the app will use GPT-3 to generate blog content for that topic.

5. **Blog Approval**

   You can review the generated blog content and choose to approve or disapprove it.

6. **Saving Approved Blogs**

   Approved blogs are saved and can be printed or saved for later use.

## How to Use

1. Input a category for your blog.
2. Review and approve topics generated based on the category.
3. Review and approve the blog content generated for approved topics.
4. Save or print the approved blogs.

The app is designed to assist in the creative process of generating blog topics and content, making it a valuable tool for bloggers and content creators. It leverages the power of AI to streamline the content creation process.

Please note that the quality and relevance of the generated content may vary, and manual review and editing are recommended for a polished final product.





