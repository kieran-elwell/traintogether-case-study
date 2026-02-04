# TrainTogether — Production Mobile App Case Study

## Overview
TrainTogether is a live cross-platform fitness and social mobile application built and maintained independently.
This repository provides a technical case study of the system architecture, security design, and operational
considerations, without exposing the private production codebase.

## Why I Built This
I built TrainTogether to solve a real problem and to gain hands-on experience owning a production system end-to-end.
This includes authentication, access control, data security, reliability, and ongoing maintenance in a real-world
environment.

## Tech Stack
- Flutter (Dart)
- Firebase Authentication
- Firestore (NoSQL)
- Firebase Cloud Storage
- GitHub for version control

## Architecture Overview
- Cross-platform mobile client built with Flutter
- Backend services provided via managed cloud services (Firebase)
- User authentication handled via Firebase Authentication
- Role-based access control enforced through security rules and application logic
- Media stored securely in Cloud Storage with controlled access
- Real-time features supported through Firestore listeners

## Security & Access Control
- Authentication handled via a managed identity provider
- Role-based access control to restrict access to user data
- Least-privilege principles applied in database security rules
- Logical separation of user data to prevent cross-access
- Secure handling of uploaded media and associated metadata

## Reliability & Operations
- Production issue diagnosis using logs and error outputs
- Iterative bug fixes and controlled updates after release
- Release builds tested prior to deployment
- Focus on maintaining stability alongside feature development

## What I Learned
- Owning a production system requires balancing security, reliability, and usability
- Small access control mistakes can have significant security impact
- Logs and observability are essential for diagnosing real-world issues
- Building software is only part of the work — maintaining it is equally important

## Scope of This Repository
- System architecture and design overview
- Security and access control approach
- IAM and permission design decisions
- Reliability and operational considerations
- Lessons learned from running a production system

The full production codebase is intentionally kept private.
Additional details or code examples can be shared on request.


