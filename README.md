# System design task

## Context
You work in an e-commerce platform facilitating trades between buyers and sellers. (like Amazon but the company is not selling goods directly)

Your company has picked a new provider called “finmid” to finance customer purchases. Customers can select a seller and goods they want to buy, and if they are eligible, they can pay 30 days later for it.

To enable this use case, you will use finmid API ([documentation](https://docs.finmid.com/docs/b2b-payments-core-concepts))

> Note: you only need B2B Payments API from the documentation, you can ignore Capital API section.

## Technical details
- Your application is designed as a monolith with web UI
- All the data is stored in a single SQL database
- The application is deployed in a cloud environment
- The application has ~1000 active daily users
- We need to support 24/7 availability of the system

## Task
Since the company is growing, the team decided that you need to start splitting the application into services, and this feature should be developed as the first separate service.

You want to design and present a technical solution to the team to deliver this feature as an MVP.

Your task is to write an **RFC** on the integration option with finmid.

> Note: We expect only RFC describing your solution. We don't expect any coding or example implementation.
