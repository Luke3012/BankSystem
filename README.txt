BANKSYSTEM is a full-stack web banking system developed as part of a university project in Java, leveraging Apache Tomcat 10.1.5 and SQLite as the backend database. Designed for handling bank account operations, the application introduces two user roles: Admin and Holder, each with a tailored set of features.

Admins can register or remove account holders, while holders can perform transactions such as deposits, withdrawals, purchases, and refund requests. Depending on the account type—Basic, Premium, or Enterprise—users have different limits on deposits, expenditures, and allowable overdraft balances.

Security is enforced via encrypted password handling, managed with a custom cryptographic key-value system and validated against internal tables.

The architecture strictly adheres to SOLID principles and incorporates a wide range of software design patterns:
• 	DAO (Data Access Object) for database interaction
• 	Observer for event-driven updates (e.g. transaction notifications)
• 	MVC (Model-View-Controller) to separate concerns between interface, logic, and data
• 	Factory to abstract object creation
• 	Iterator for structured data traversal (including reverse iteration of transactions)

The project is structured using Java Servlets as Controllers, JSP files for Views, and Model/Operation classes for business logic. Exception handling is integrated throughout, with custom exceptions managing business rules like deposit and withdrawal limits, and insufficient funds.

Whether you're an admin managing accounts or a user navigating your bank activity, BANKSYSTEM delivers secure, scalable functionality built on solid programming foundations.
