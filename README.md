# TrainTogether – Technical Case Study

## Overview
TrainTogether is a live cross-platform fitness and social mobile application built and maintained independently. This repository provides a technical overview of the system architecture, security design, and operational considerations without exposing the private production codebase.

## Why I Built This
I built TrainTogether to solve a real problem and to gain hands-on experience owning a production system end-to-end, including authentication, data security, reliability, and ongoing maintenance.

## Tech Stack
- Flutter (Dart)
- Firebase Authentication
- Firestore (NoSQL)
- Firebase Cloud Storage
- GitHub for version control

## Architecture Overview
- Mobile client built with Flutter
- Backend services provided via Firebase
- User authentication handled via Firebase Auth
- Role-based access control enforced through security rules and application logic
- Media stored securely in Cloud Storage
- Real-time features supported through Firestore listeners

## Security & IAM Considerations
- User authentication handled via managed identity provider
- Role-based access control to restrict data access
- Least-privilege principles applied in Firestore rules
- Separation of user data to prevent cross-access
- Secure handling of uploaded media and metadata

## Reliability & Operations
- Production issue diagnosis using logs and error outputs
- Iterative bug fixes and controlled updates
- Release builds tested before deployment
- Focus on stability alongside feature development

## What I Learned
- Owning a production system requires balancing security, reliability, and usability
- Small permission mistakes can have large security implications
- Logs and observability are critical for debugging real-world issues
- Building is only half the job — maintaining is the real work

## Note on Code Availability
The full production codebase is kept private. Code samples and further details are available on request.
