🤖💬 AI Customer Support Chatbot – IBM Cloud Based

Abstract:
A smart chatbot that helps customers with order tracking, product recommendations, returns, offers, and feedback.
It is built using IBM Watsonx Assistant, Cloudant database, and a simple backend API.
This project is for learning cloud application development and shows how AI + Cloud can automate customer support.


⭐ Features

Built on IBM Cloud using Watsonx Assistant

Understands customer messages using intents & entities

Gives product suggestions based on category

Helps track orders using Cloudant database

Handles returns, refunds, offers, and feedback

User-friendly and works on web chat


🖥️ How It Works (Simple Explanation)

1. User types a message (like “Track my order”).


2. Watsonx Assistant understands the message.


3. Assistant connects to Cloudant DB (orders, products, feedback).


4. Backend sends correct data back to the chatbot.


5. User gets the answer instantly.



🔧 IBM Services Used

Watsonx Assistant – Understands user questions

Cloudant Database – Stores orders, products, feedback

Backend API – Connects Watson to Cloudant

IBM Cloud – Hosting and service management



---

🧠 Intents Used (Examples)

#greet – Hello, Hi

#track_order – Track my order

#recommend_product – Suggest something

#return_policy – How to return

#offers – Any discount?

#feedback – User ratings/comments

#goodbye – Bye, Thank you



---

🧩 Entities Used

@product_category – electronics, fashion, shoes, etc.

@product – laptop, phone, smartwatch

@order_status – shipped, delivered

@issue_type – return, refund, damaged

@payment_method – UPI, COD

@rating – 1 to 5 stars

@greeting_type – morning, night



---

🗂️ Databases Used (Cloudant)

1. Order Database

order_id

customer_name

product

order_status


2. Product Database

product_id

product_name

category

price

image_url


3. Feedback Database

name

rating

comments



---

🔗 Backend Integration

Connects Watsonx Assistant to Cloudant

API fetches order status

API returns product list

API saves feedback

Secure & fast communication



---

🎯 Project Outcome

Helps customers instantly

Reduces manual support work

Shows how cloud and AI work together

Great learning project for IBM Cloud Application Developer



---

👥 Team Members

(Replace with your details)

Name	Roll Number

adhishree bhawsar 24100BTCSDSI17456
harshita Sharma 24100BTCSDSI17473
RISHIKA upadhyay 24100BTCSDSI17484


Course: Cloud Application Developer – IBM
College: (Your College Name)


---

⚠️ Disclaimer

This chatbot is made for educational purposes only and simulates real processes like order tracking and product suggestions.
