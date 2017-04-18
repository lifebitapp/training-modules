
# Lifebit Development Standards

## Code

 * Must follow all [Android/Java standards](https://blog.mindorks.com/android-code-style-and-guidelines-d5f80453d5c7)
 * Must follow [SOLID principles](https://android.jlelse.eu/android-development-the-solid-principles-3b5779b105d2).
 * Must not be pulled into mainline branches until it has gone through code review
 * Should indicate _what_ is happening, comments should indicate _why_

### Code Review

Reviewers must verify the standards in this document are being followed in addition to other [code review best practices](http://kevinlondon.com/2015/05/05/code-review-best-practices.html).

 * Must be reviewed by the author first
 * Must be reviewed by at least one other member of the team (crucial for knowledge sharing)

## Testing

A developer should be able to check out the project, make a change, and if the tests pass be confident their change could be deployed to production.

 * Tests should be automated, running in a CI environment on every pull request
 * Requirements for a feature should be scoped out by the team prior to beginning work on that feature
 * Unit test coverage should be 100% for domain logic, leaving integration points with the framework (such as controllers, service providers, etc.) to be covered by other types of tests described below
 * Functional, integration and acceptance testing coverage should be whatever it needs to be to ensure the application is working correctly
