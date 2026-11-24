# Travel Budget Management Chatbot

A domain-specific chatbot designed to assist travellers in planning, monitoring and managing their travel expenses using a Large Language Model (LLM).

## 1. Project Overview

The Travel Budget Management Chatbot aims to help travellers manage their travel finances before and during a trip. It provides assistance in planning travel budgets, tracking daily expenses, monitoring remaining budgets and converting foreign currencies into Malaysian Ringgit (MYR).

## 2. Problem Statement

Travellers may face difficulties managing their travel expenses, especially when planning a trip or travelling to destinations that use different currencies. Common problems include:

- Determining how much money to prepare for a trip.
- Keeping track of daily expenses and knowing how much money has been spent.
- Monitoring the remaining travel budget.
- Understanding foreign currency values in Malaysian Ringgit (MYR).

## 3. Objectives

The objective of this project is to develop a domain-specific chatbot that assists travellers in planning, monitoring and managing their travel expenses.

## 4. Main Functions

**4.1 Travel Budget Planning**

Suggests a suitable travel budget based on the destination and the user's total budget. It also recommends budget allocations for different categories, such as food, accommodation and transportation.

**4.2 Expense Tracking**

Allows users to record their daily travel expenses and keep track of their spending.

**4.3 Budget Monitoring**

Monitors recorded expenses and calculates the total amount spent and the remaining travel budget.

**4.4 Currency Conversion**

Converts foreign currencies into Malaysian Ringgit (MYR) to help users understand their travel expenses.

## 5. Team Members

| Name | GitHub Username | Role |
|---|---|---|
| Member 1 | @username | Project Leader |
| Member 2 | @username | Frontend Developer |
| Member 3 | @username | Backend Developer / Model Integrator |
| Member 4 | @username | Domain Specialist |

## 6. Domain and Dataset

**Selected Domain:** Travel Budget Management

The chatbot uses a custom dataset containing at least 30 question-and-answer pairs related to travel budgeting and expense management. The dataset is stored in CSV format and is used to provide relevant information when answering users' questions.

**Dataset Source:** [Describe the sources used to prepare the dataset.]

## 7. Architecture

The chatbot follows this general workflow:

1. The user enters a question or expense through the chatbot interface.
2. The backend receives and processes the user's input.
3. Relevant information is retrieved from the custom dataset when needed.
4. The information is provided as context to the LLM.
5. The system processes the user's request.
6. The chatbot displays the response to the user.

## 8. Model

**Model/API:** [To be decided]

**Reason for Selection:** [To be updated]

**Integration Method:** [To be updated]

## 9. Project Structure

```text
project/
├── data/
├── src/
├── app/
├── tests/
├── docs/
├── README.md
├── problem-statement.md
├── requirements.txt
├── .gitignore
└── .env.example
```

## 10. How to Run

1. Clone this repository.
2. Install the required dependencies.
3. Configure the necessary environment variables.
4. Run the chatbot application.
5. Open the chatbot interface.

Detailed instructions will be added after development.

## 11. Demo

[Add the chatbot demonstration video link here.]

## 12. Limitations

- The chatbot focuses on travel budget planning and expense management.
- Budget recommendations depend on the information provided by users.
- Currency conversion accuracy depends on the availability and accuracy of exchange rates.
- The chatbot may occasionally provide inaccurate or irrelevant responses.

## 13. GenAI Use

Generative AI tools may be used to assist with project development, including code suggestions, prompt development and documentation. All generated content is reviewed and tested by the group members.
