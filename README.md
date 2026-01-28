ShelfSwap
ShelfSwap is a web application designed to facilitate peer-to-peer book management and exchange. The platform provides a community-driven alternative to traditional marketplaces by allowing users to manage personal libraries and connect with local readers for book swaps.

Core Features
Library Management: A dashboard for users to catalog, organize, and filter their personal book collections.

Exchange System: A matching mechanism that enables users to request and coordinate book swaps with others.

Community Engagement: Integrated tools for book clubs and local meetup organization.

Analytics: Visual tracking of reading habits and exchange frequency.

Trust & Safety: A peer-review system for users to rate exchange experiences.

Technical Stack
Frontend: React.js

Backend: Node.js with Express.js

Database: MySQL (Hosted via GCP Cloud SQL)

API Architecture: RESTful endpoints for CRUD operations on users, books, and exchange logs.

Database Design
The underlying database is optimized for relational integrity and follows 3NF standards. Key tables include:

Users: Stores account profiles and preferences.

Books: A master catalog of book metadata and ISBNs.

UserCopies: Maps specific book instances to owners.

ExchangeRequests: Tracks the status of ongoing and historical swaps.

Getting Started
Prerequisites
Node.js (v16+)

npm

A running MySQL instance (GCP Cloud SQL recommended)
