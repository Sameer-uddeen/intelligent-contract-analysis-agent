# Project Description — Intelligent Contract Analysis Agent

## Project Summary
Intelligent Contract Analysis Agent is a business-ready legal analysis solution built in Microsoft Copilot Studio for the Enterprise Agents track. The agent reviews contract documents, extracts important clauses, identifies risky language, checks alignment with contract standards, and proposes negotiation improvements.

## Problem Solved
Manual legal review of large contract volumes is time intensive and can delay negotiations. It also increases the chance that key clauses are overlooked or inconsistently assessed. This project addresses that problem by giving legal teams a guided AI assistant for first-pass contract analysis.

## Features and Functionality
- Contract summarization in plain language
- Clause extraction for key legal terms
- Risk detection for common red flags such as unlimited liability and missing termination details
- Compliance validation using a grounded knowledge base
- Negotiation guidance for clauses that need improvement
- Comparison of high-risk and low-risk contracts for demonstration purposes

## Technologies Used
- Microsoft Copilot Studio
- Microsoft 365 Copilot (Enterprise Agent)
- Foundry IQ knowledge grounding via a contract standards library
- GitHub for public repository submission assets

## Microsoft IQ Layer
This project uses **Foundry IQ** by grounding analysis in a clause library / contract standards knowledge file so that the agent references structured standards instead of responding only from a prompt.

## Demo Flow
1. Load the knowledge base containing contract rules.
2. Upload a contract PDF.
3. Ask the agent to analyze the uploaded contract.
4. Review the structured output.
5. Repeat with a second contract to show different risk levels.

## Submission Notes
Include the following in the contest project entry:
- This project description
- Public GitHub repository link
- Demo video link
- Architecture diagram
