# Zerofy (SurplusPack) — AI-Powered Food Surplus Management System

## Overview
Zerofy (also referred to as SurplusPack) is an AI-powered surplus food management and rescue platform designed to reduce food waste at retail stores.  
The system dynamically discounts near-expiry food items and automatically reallocates unsold inventory to NGOs using autonomous background agents.

The platform demonstrates how intelligent automation can optimize food distribution without relying on manual intervention.

---

## Problem Statement
Retail food waste occurs due to:
- Static pricing of perishable items
- Delayed redistribution to NGOs
- Manual coordination between stores and consumers
- Lack of real-time inventory intelligence

Zerofy addresses these challenges through automated decision-making and time-aware inventory management.

---

## Key Features
- Dynamic price adjustment based on expiry time
- Autonomous NGO assignment for near-expiry items
- Multi-item claim system with a single verification code
- Location-based store discovery
- Persistent inventory and claim tracking
- Real-time system operation using background agents

---

## System Architecture

---

## AI Agent Design
The system includes multiple autonomous agents that run continuously:

1. **Auto-Discount Agent**
   - Adjusts prices dynamically based on remaining shelf life

2. **NGO Allocation Agent**
   - Automatically assigns expiring food to NGOs

3. **System Optimization Agents**
   - Clean old records
   - Maintain database health

These agents simulate intelligent decision-making without requiring machine learning models.

---

## Technologies Used
- Python
- Gradio (UI)
- SQLite (Database)
- Pandas
- Threading
- DateTime & Timezone Handling

---

## Use Cases
- Retail stores managing perishable inventory
- NGOs sourcing food donations efficiently
- Urban food waste reduction initiatives
- Proof-of-concept for smart supply chain systems

---

## Scalability & Future Improvements
- Replace SQLite with PostgreSQL or cloud databases
- Introduce ML-based demand prediction
- Add mobile app integration
- Implement real-time notifications

---

## Author
Developed as an AI-inspired automation project focusing on sustainability, intelligent systems, and real-world impact.
