# Challenge

Create a simple consumer loan app. The app is a headless web service that exposes the following endpoints:

- apply for a loan and provide `loan amount`, `term`, `name`, `surname`, and `personal id`
- list all approved loans
- list all approved loans by a borrower (you can skip AuthN and AuthZ)
  
Do not grant a loan if:
- the application comes from a person with a blacklisted personal id (a list of blacklisted personal ids lives in a config file or DB)
- too many applications come from a given country in the last `N` days

Resolve a country code using some external service and store it in a database, together with a loan application.

### Technical requirements

Use Java programming language; use any JVM language for tests. You have total control over frameworks, tools, and libraries.

### What gets evaluated
- Conformance to business requirements
- Code quality (we value good OO design guided by tests)
- Checkout-and-run convenience

### Happy coding! 👨‍💻
