# Movie Ticket Booking Management

## National Internship Program (NIP) 2026

A Movie Ticket Booking Management application developed using the Pega Platform as part of the Pega National Internship Program (NIP).

## Project Overview

The Movie Ticket Booking Management application is designed to simplify and automate the movie ticket booking process for CineWave Entertainment.

The application allows customers to submit movie ticket booking requests, checks show and seat availability, calculates booking costs, captures customer confirmation, processes the booking, and provides booking confirmation.

## Problem Statement

CineWave Entertainment currently manages movie ticket bookings through manual processes such as emails and offline systems. This can result in delays, limited visibility, and difficulties in tracking bookings and communicating with customers.

This project provides a Pega-based solution to automate and manage the complete movie ticket booking workflow.

## Objectives

- Allow customers to request movie tickets.
- Check movie show and seat availability.
- Calculate the total booking cost.
- Capture customer confirmation before final booking.
- Process and track booking requests.
- Maintain movie and show information.
- Generate booking details and confirmation.
- Notify customers about booking confirmation.
- Route booking-related work appropriately.

## Technology Used

- Pega Platform
- Pega App Studio
- Pega Dev Studio
- Pega Data Objects
- Business Rules
- Case Management
- Workflow Automation
- Correspondence / Notifications

## Application Details

**Application Name:** Movie Ticket Booking Management

**Case Type:** Ticket Booking

**Developer:** PARUVATHANACHIAR P

**Institution:** V. S. B. Engineering College

**Program:** Pega National Internship Program (NIP) 2026

## Case Lifecycle

The Ticket Booking case follows a structured workflow:

1. Booking Intake
2. Availability Check
3. Payment Processing
4. Booking Confirmation
5. Resolution

The application also includes alternative flows for rejection, correction/rework, and issue handling.

## Key Features

### 1. Booking Intake

Captures customer and booking information such as:

- Customer details
- Movie selection
- Show selection
- Seat selection
- Booking preferences

### 2. Availability Check

The application verifies show status and seat availability before proceeding with the booking.

### 3. Payment Processing

The booking cost is calculated based on the ticket price and number of tickets. Payment-related processing and confirmation are handled as part of the workflow.

### 4. Booking Confirmation

The customer booking request is confirmed and booking details are generated.

### 5. Notification

Customers can be notified about booking confirmation or rejection.

### 6. Resolution

The case can be closed after successful booking or escalated when an issue requires further handling.

## Data Management

The application uses reusable data structures to manage movie and show information.

Important information includes:

- Movie Name
- Genre
- Show Date
- Show Time
- Seat Capacity
- Ticket Price
- Number of Tickets
- Total Cost

## Personas

The application uses personas to represent different users involved in the booking process.

- Customer
- Booking Staff
- Cinema Manager
- Support Agent
- Marketing Executive
- Application Control Agent

## Work Queue

Work queues are used to route work to the appropriate processing group.

- `PremiumShowQueue` — used for IMAX, premium, or special screenings.
- `StandardShowQueue` — used for other show types.
- `BookingAgentQueue` — used for booking-related approval and work assignment.

## Project Deliverables

This repository contains the project submission documentation prepared for the Pega National Internship Program.

### Submission Document

`MovieTicket_PARUVATHANACHIAR_P.docx`

The document contains:

- Project details
- User story implementations
- Application screenshots
- Configuration details
- Application understanding
- Personas
- Work queues
- Rule details
- Case flow
- Design decisions
- Challenges and solutions

## Project Repository

This GitHub repository contains the project submission document and related project information.

## Pega Platform

The application was developed and configured using the Pega Platform during the National Internship Program.

## Author

**PARUVATHANACHIAR P**
B.E. Computer Science and Engineering  
V. S. B. Engineering College

---

**Pega National Internship Program (NIP) 2026**
