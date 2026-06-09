# Spacez AI Review Intelligence Agent

## Overview

This project was developed as part of the Spacez AI Product Associate Take-Home Assignment.

The goal is to design an AI-powered review intelligence system that collects guest reviews from multiple booking platforms and transforms them into actionable insights for different stakeholders within the hospitality business.

The solution focuses on helping:

- Operations Team
- Business Team
- Caretakers

make faster and more informed decisions based on customer feedback.

---

## Problem Statement

Guest reviews are distributed across multiple platforms such as Airbnb, Booking.com, and Google Reviews.

This creates several challenges:

- Recurring issues remain unnoticed.
- Property performance is difficult to evaluate.
- Caretaker effectiveness is unclear.
- Business teams lack portfolio-level visibility.
- Operational improvements are reactive rather than proactive.

The objective is to build an AI agent that automatically analyzes reviews and delivers stakeholder-specific insights.

---

## Solution

The AI Review Intelligence Agent performs:

### Review Aggregation
Collects reviews from multiple platforms and normalizes ratings.

### Sentiment Analysis
Identifies positive, negative, and neutral feedback.

### Theme Detection
Extracts recurring topics such as:

- Cleanliness
- Check-in Experience
- Maintenance
- WiFi Issues
- Pool Conditions
- Hospitality
- Location Accessibility

### Stakeholder-Specific Reporting

#### Operations Team
Receives recurring issue reports and maintenance alerts.

#### Business Team
Receives portfolio performance metrics, reputation trends, and property-level insights.

#### Caretakers
Receive actionable feedback focused only on areas within their control.

---

## Prototype Focus

For the prototype, the primary stakeholder selected was:

**Caretakers**

### Why Caretakers?

Caretakers directly influence guest experience through:

- Check-in and checkout management
- Guest communication
- Issue resolution
- Coordination with housekeeping and vendors

Providing focused feedback helps them take immediate action and improve guest satisfaction.

---

## Key Insight

One of the major findings during analysis was that:

> Not all negative reviews should be attributed to caretakers.

Issues such as:

- Poor WiFi
- Road accessibility
- Property infrastructure
- Misleading listing photos

are often outside a caretaker's control.

The system therefore separates:

### Caretaker-Controlled Issues
- Check-in delays
- Communication quality
- Responsiveness
- Hospitality

### Non-Caretaker Issues
- Infrastructure problems
- Property maintenance
- Listing inaccuracies
- External environmental factors

This prevents unfair performance evaluations.

---

## Features

- Multi-platform review analysis
- Rating normalization across platforms
- Sentiment classification
- Theme extraction
- Stakeholder-specific dashboards
- Actionable recommendations
- Recurring issue detection

---

## Tech Stack

- React.js
- JavaScript
- AI-powered review analysis
- Data visualization components

---

## Project Structure
