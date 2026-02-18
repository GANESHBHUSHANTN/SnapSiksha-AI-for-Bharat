# SnapSiksha AI

AI-powered visual learning platform that transforms complex concepts into animated explanations. Built for AI for Bharat Hackathon.

## Overview

SnapSiksha converts text, code, and documents into on-demand animated explainer videos using AI. It breaks down complex topics into simple visual steps with synchronized narration.

## Key Features

- **AI Concept Understanding** - Uses Amazon Bedrock (Claude/Titan) to analyze queries
- **Visual Decomposition** - Custom VCDE engine breaks concepts into teachable steps
- **Automated Animation** - Generates Manim animations for each step
- **Voice Narration** - Amazon Polly provides synchronized audio
- **Scalable Architecture** - AWS serverless infrastructure

## Tech Stack

**Frontend:** React, Tailwind CSS, AWS Amplify  
**Backend:** AWS Lambda, Amazon API Gateway, Amazon Cognito  
**AI/ML:** Amazon Bedrock, VCDE, Manim, Amazon Polly  
**Storage:** Amazon S3, CloudFront  
**Monitoring:** Amazon CloudWatch

## Architecture

User → React Frontend → API Gateway → Lambda Orchestrator → Bedrock (AI) / VCDE (Decomposition) / Manim (Animation) / Polly (Voice) → S3 Storage

## API Endpoints

- `POST /api/concepts` - Submit concept for explanation
- `GET /api/concepts/{id}` - Get status and video URL
- `GET /api/concepts` - List user history

## Team

**Team:** SRIBISCO  
**Team Members:** Ganesh T N Bhushan , D Varsha 
**Track:** AI for Learning & Developer Productivity (Student)

