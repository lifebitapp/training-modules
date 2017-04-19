# Module 8a: Laravel PHP Framework

***

## Getting Started

Prior to completing the module below it is highly recommended that you look at the following learning material:  **Even if you consider yourself a Laravel expert, there is material in the resources below that even seasoned users are not unaware of.**

- [Laravel 5 Fundamentals](https://laracasts.com/series/laravel-5-fundamentals)

_You're only building a sample application for the purpose of demonstrating knowledge of the various tools in Laravel. The application concept doesn't need to be something you'd want to show to the world._

***

## The Test

1. Create a new repository in your GitHub namespace called `Laravel-Test`, and commit all the work from this module there.
2. Build a Laravel application with the features, functions, entities etc of your choosing as long as the application meets the criteria below. Be creative and resourceful but at the same time don't take 10 years to build your app.

**Application Criteria**

When building your application and meeting a specific criteria below, you should use a relevant commit message to indicate that your commit is satisfying a particular criteria.  This isn't an application you'll ship, focus on fulfilling the criteria to demonstrate your understanding of the framework components.

1. Build your features using Test First Development. Don't write any feature code until the failing test is created first. 1) Write the test; 2) Write code to make it pass; 3) Refactor; 4) Rinse & Repeat. Keep in mind, however, that you CAN over-test your application. See [Test like the TSA by DHH](http://37signals.com/svn/posts/3159-testing-like-the-tsa).
2. Integrate user authentication.
3. Integrate sending email (with HTML and Plain Text versions of the email).
4. All models should have validation. Between all models, make sure to use ALL of these validation rules at least once:
    - Required
	  - Numeric
	  - Required If
	  - Regex
    - Email
    - Url
    - Use a custom error message
    - Custom validation rule
5. All models should account for mass-assignment vulnerabilities by using the `fillable` or `guarded` properties.
6. Make sure your application is protected from the following security vulnerabilities. _The framework may or may not handle some of this for you, so verify to be sure._
    - XSS
    - SQL-Injection
    - CSRF
    - Session-Fixation
7. Include a minimum of four (4) different Entities (excluding lookups).
8. Include the following relationships:
    - At least 1 relationship for each model
    - 1+ belongs to relationship
    - 1+ has many relationship
    - 1+ has one relationship
    - 1+ has and belongs to many relationship
    - 1+ polymorphic relationship
9. CRUD interface for at least 1 model.
10. Handle uploading an image that is a property of an entity. (Something like `$user->avatar`). Have 1+ alternative image representations created from the uploaded image (eg. thumbnail, etc.). You may consider using one or more packages to help do this.
11. Include at least two (2) 'resourceful' routes and controllers.
12. Subscribe to at least one (1) event. This can be a built-in event or a custom event you fire.
13. Create at least one (1) Facade.
14. Use pagination at least once.
15. Use 2+ Queues: one for sending email (in #5); and one custom queue.
16. Use at least one query scope in your application.
17. Implement at least one (1) model policy

***

## Wrapping Up

When you are done, push your code to GitHub. Please create a tag called `v1.8a` with a message of `"ready for review"`.  Be sure your tags are pushed to the remote repository and are visible in GitHub.

Create an issue titled **Review Module 8a - Laravel PHP Framework** and `@mention` your mentor and team leader.
