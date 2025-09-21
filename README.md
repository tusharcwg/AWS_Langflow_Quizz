# AWS Cloud Practitioner Exam Demo (Langflow)
This repository contains a demo application built using Langflow.
It provides a 10-question quiz designed to help users practice for the AWS Cloud Practitioner Exam.

#**📋 Features**

> Interactive quiz with 10 multiple-choice questions

> Focused on AWS Cloud Practitioner (CLF-C02) exam concepts

> Built using Langflow for LLM orchestration

# **🧠 About the Project**
This project demonstrates how to build an AI-driven quiz generator using the Langflow framework.
The workflow is designed to show how external knowledge retrieval, reasoning, and LLM inference can be combined to create meaningful outputs.

Specifically, the app:

> Ingests domain-specific documents related to AWS.

> Stores them in a vector database (Astra DB) for contextual search.

> Uses an LLM provider (Groq) to generate multiple-choice questions dynamically.

> Presents a 10-question AWS Cloud Practitioner quiz as a proof of concept.

The goal is to illustrate how AI workflows can seamlessly combine document ingestion, context retrieval, and large language model reasoning to create practical applications for exam prep and learning.
