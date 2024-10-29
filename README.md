# HiKA-AI Virtual Concierge - Proof of Concept

## Project Overview

The **HiKA-AI Virtual Concierge** is a Tier 0 support chatbot designed to enhance the student service experience at Queensland University of Technology (QUT). It provides instant answers to common queries, reducing wait times for students in line to see a Tier 1 human concierge. The proof of concept aims to test HiKA-AI’s ability to address frequently asked questions and offer a convenient self-service option.

**Deployment Locations:**
- **Gardens Point Campus** - Service Points
- **Kelvin Grove Campus** - Service Points

## Features

- **Azure AI Studio Integration**: The chatbot is built in Azure AI Studio and deployed as an Azure web app. It handles general student queries across categories, including:
  - Admissions & future students
  - Blue card
  - Campuses and transport
  - Enrolment
  - Events
  - Fees and payments
  - Class Registration
  - Id cards
  - IT and printing
  - Learning and assessment
  - Library
  - Lost property
  - Official documents and qualifications
  - QUT websites
  - Student life
  - Student welfare

- **Microsoft Forms Integration for Feedback**: The page includes a feedback button linking to a Microsoft Form. Users are encouraged to provide feedback on their experience. The form is configured to:
  - Send an email notification to `se.service.improvement@qut.edu.au` for each submitted response.
  - Collect insights on chatbot utility and areas for improvement.

## Usage Instructions

### For Students
1. **Engage with HiKA-AI**: Click on the **"Chat with HiKA-AI"** button to begin. HiKA-AI is designed to answer a wide range of general questions, providing immediate responses to help you navigate campus services.
2. **Leave Feedback**: After using HiKA-AI, click on the **"Leave Feedback"** button to submit your thoughts. This feedback will help QUT enhance the digital concierge service.

### For Support Staff and Testers
The web page can be accessed through GitHub Pages, which hosts the HTML code for this chatbot interface. Please ensure all updates to the code are committed and pushed to maintain synchronisation with the live page.

## Deployment on GitHub Pages

This page is hosted as a GitHub Pages site to allow remote testing and easy updates. To deploy updates:
1. Commit any changes to the `main` branch.
2. Access the GitHub Pages link under **Settings > Pages** to view the live site.

## Technical Information

- **Azure Integration**: This proof of concept leverages Azure AI Studio for chatbot functionality. It integrates seamlessly with the HTML front-end, and the chatbot resets for each new session.
- **Feedback Form**: Hosted on Microsoft Forms, configured to send response emails to the Service Improvement team. Each new user clicking the feedback link opens a fresh form instance.

## Future Enhancements

Depending on the success of this proof of concept, the following improvements may be considered:
- **Enhanced Data Analytics**: To gather insights on common queries and peak usage times.
- **Further Integration with Campus Systems**: To access real-time data related to service availability, events, and updates.
- **User Authentication for Personalised Assistance**: For more secure and personalised responses.

For any questions or technical issues, please contact the Service Improvement team at `se.service.improvement@qut.edu.au`.
