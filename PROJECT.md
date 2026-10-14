# AI Debugging Tutor

## 1. Project Vision

Build an AI programming tutor that helps beginners understand why their code fails instead of simply giving them the correct solution.

**Core principle:** Don't just fix my code. Teach me why it failed.

## 2. Developer Goal

This is a learning-first, product-oriented project.

The developer wants to:
- Learn real software development skills by building a real product.
- Launch a usable MVP.
- Find real users in international markets.
- Explore sustainable recurring revenue.
- Build a public portfolio project and learn product development.

AI should accelerate learning, not replace it.

## 3. Target Users

Initial target users:
- High school students learning programming.
- University students who are new to programming.
- Self-taught beginners learning C++.

The initial product and documentation should use English and target an international audience.

## 4. Main Problem

Beginners often encounter errors without understanding their causes.

General AI tools can explain or fix code, but users may receive complete solutions without learning how to solve the problem themselves.

## 5. Core Solution

Provide a structured debugging and learning workflow:
1. The student describes a programming exercise.
2. The student submits their own code.
3. The tutor analyzes the code and available error information.
4. The tutor explains the problem in beginner-friendly language.
5. The tutor provides a hint rather than immediately revealing the solution.
6. The student revises the code and tries again.
7. The tutor explains the outcome and reinforces the underlying concept.

The product should prioritize learning and independent problem-solving.

## 6. AI Assistance Levels

The default behavior is to guide, not solve.

- Level 1: Ask a guiding question.
- Level 2: Give a conceptual hint.
- Level 3: Point to the relevant part of the code and explain the likely cause.
- Level 4: Show a small example or more detailed guidance.
- Level 5: Provide a full solution when explicitly requested, followed by an explanation.

The student should be able to request more help.

## 7. MVP Scope

The first version should support:
- Entering a programming exercise.
- Entering C++ code.
- Providing an error message or observed behavior.
- Receiving an explanation of the likely problem.
- Receiving progressive hints.
- Requesting additional help.
- Revising and resubmitting code.

The first version should focus on a clear, useful learning loop rather than a large feature set.

## 8. Non-MVP

Do not build these before validating the core experience:
- A full online IDE or code execution sandbox.
- A VS Code extension.
- Complex user profiles and analytics.
- Social networking or leaderboards.
- Support for many programming languages.
- A complicated subscription and payment system.

## 9. Product Differentiation

Do not compete with general AI tools on raw model intelligence.

Explore differentiation through:
- A structured hint-based workflow.
- Context about the exercise and previous attempts.
- Learning history and recurring error patterns.
- A consistent tutoring style.
- Reduced friction between writing code, understanding errors, and trying again.

Every proposed feature should answer:

**Why would a user need this product instead of asking a general AI assistant the same question?**

## 10. Technology and Learning

- First programming language: C++.
- First product format: Web application.
- Product interface: English.
- Developer explanations: Chinese when helpful.
- Learn core concepts by implementing small pieces personally.
- Choose simple, maintainable technologies appropriate for a beginner.

The technology stack should be selected deliberately rather than chosen for popularity.

## 11. Monetization

Possible future models:
- Free tier with a paid tier.
- Subscription of approximately €2–5 per month.
- A one-time purchase.

Do not prioritize payment integration before demonstrating real user value.

## 12. User Acquisition

Potential channels include GitHub, Reddit, YouTube, TikTok, X, and student communities.

Share progress honestly, collect feedback, and use real user problems to guide development.

## 13. Development Philosophy

- Build the smallest useful version first.
- Validate assumptions with real users.
- Prefer working software over unnecessary complexity.
- Keep changes small and understandable.
- Use existing open-source projects for learning and inspiration, not substantial copying.
- Document important design decisions.
- Never claim a feature works until it has been tested.

## 14. Learning Rules

For concepts the developer is learning:
1. Explain the concept simply.
2. Show a small example.
3. Give the developer a manageable task.
4. Let the developer implement it.
5. Review the implementation and explain mistakes.
6. Integrate it into the product.

The developer should understand the important code in the finished product.

## 15. Claude Collaboration Rules

Claude should act as a combination of:
- Programming teacher.
- Product manager.
- Technical advisor.

Claude should distinguish between teaching tasks and routine implementation tasks.

For important decisions, explain the trade-offs and recommend a clear option.

Avoid unnecessary dependencies, premature abstraction, and overengineering.

## 16. Time Commitment

Expected development time: approximately 5–10 hours per week when university work permits.

Academic responsibilities take priority when workload is high.

## 17. Success Criteria

Initial 90-day validation targets:
- Launch a usable MVP.
- Get 10 real international users to try it.
- Observe repeat usage from at least some users.
- Get at least one paying user who is not a friend or family member.

These are validation targets, not guaranteed outcomes.

## 18. First Milestone

Create the project documentation, learn Git fundamentals, build a minimal web application, implement the core tutoring workflow, and test it with real beginners.