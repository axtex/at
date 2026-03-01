# at
> Cloud-Native Portfolio Platform

A serverless developer portfolio with globally distributed delivery, dynamic project rendering, and a contact API — built to be fast anywhere in the world.

## What is this?

at is the personal portfolio platform behind my work. It's built on Next.js and served through AWS CloudFront's global CDN, meaning it loads fast regardless of where visitors are. Projects are rendered dynamically by pulling live data directly from the GitHub API, so the portfolio always reflects current work without manual updates.

The contact form is powered by a serverless AWS Lambda function — no backend server to maintain. CI/CD pipelines handle deployment automatically on every push, with performance monitoring and analytics to track how the site is being used.

## Core Features

- [ ] Globally distributed delivery via AWS S3 + CloudFront CDN
- [ ] Dynamic project rendering from GitHub API
- [ ] Serverless contact form via AWS Lambda
- [ ] CI/CD pipeline with automated deployment
- [ ] Performance optimization and analytics tracking
- [ ] Production-grade monitoring

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 14, TypeScript, Tailwind CSS |
| Serverless | AWS Lambda |
| CDN | AWS CloudFront |
| Storage | AWS S3 |
| External API | GitHub API |
| Infra | GitHub Actions CI/CD |
