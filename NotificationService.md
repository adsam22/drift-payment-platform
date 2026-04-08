# Notification Service

## Overview
The Notification Service is responsible for sending system generated alerts via email and SMS.

## Responsibilities
- Send login alerts
- Send payment confirmations
- Deliver security notifications

## Dependencies
- Authentication Service (login events)
- Payment Processing Service (transaction events)

## Downstream Consumers
- End users receive notifications

## Risks
- Failed triggers may result in missed alerts
- Delays in event processing could impact user trust

## Ownership
Notifications Platform Team
