# Email_Service_Demo
# Resilient Email Sending Service

## Overview

This project implements a resilient email sending service in TypeScript. The service uses two mock email providers and implements various fault-tolerant mechanisms, such as retry logic with exponential backoff, fallback between providers, idempotency, rate limiting, and status tracking.

## Features

- **Retry Mechanism**: Exponential backoff on failures.
- **Fallback**: Switch to a second provider on failure.
- **Idempotency**: Prevent duplicate emails.
- **Rate Limiting**: Basic rate limiting to prevent overuse.
- **Status Tracking**: Track email sending attempts.
- **Bonus**: Circuit breaker pattern, simple logging, basic queue system.

## Requirements

- Node.js
- TypeScript

## Setup

1. Clone the repository
