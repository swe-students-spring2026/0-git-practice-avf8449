# Git Practice

## Article

**[Why Modern Software Still Collapses Under Its Own Complexity](https://dick-dowdell.medium.com/software-architecture-still-fails-at-scale-9b607a444fda)** *By Dick Dowdell (Jan 2026)*

## Why I find it interesting

This article is interesting because it talks about the original vision Alan Kay (the father of Object Oriented Programming) had.  It is surprising that the actual inspiration was biology, based on cells that despites being autonomous and protecting their state, they communicate with others through messages. 

The author of the article later explains *Assertion-driven development* where buisness rules are captured as formal machine readable declarations. Instead of translating requirements into code, the executable software should be generated directly from these assertions. This limits the system, making it unable to enter an incorrect state.

## Comment - Robin Chen

What I took away from this article is that a lot of “software doesn’t scale” problems are really about complexity, we build systems where everything ends up coupled through shared state and hidden assumptions. The assertion driven development idea is also interesting since it tries to directly include business rules and prevent invalid states, but I’m curious how realistic it is to have (and further maintain) a big set of assertions without making it the complexity of itself.

### Other changes made

- Added top level heading.
- Removed all colons in titles.
- Surround all titles in blank lines.
