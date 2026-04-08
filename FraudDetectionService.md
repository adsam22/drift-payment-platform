# Fraud Detection Service

## Overview
The Fraud Detection Service evaluates login and transaction activity to identify suspicious behavior.

## Responsibilities
- Risk scoring for user activity
- Detect suspicious login attempts
- Monitor transaction anomalies

## Dependencies
- Authentication Service (login activity data)
- Payment Processing Service (transaction data)

## Downstream Consumers
- Payment Processing Service (may block transactions)
- Internal risk monitoring systems

## Risks
- Changes in authentication flow may impact fraud signals
- Incomplete data may reduce detection accuracy
- False positives may block legitimate users

## Ownership
Fraud and Risk Team
