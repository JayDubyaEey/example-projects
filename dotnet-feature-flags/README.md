# Scenario

We are building a web application where we need the ability to enable and disable functionality dynamically and in real-time, without requiring deployments. You'll be designing and building a feature flag service that allows administrators to manage feature flags and enables our application to evaluate whether features should be enabled for specific users or requests.

Our frontend is built in React and will consume the APIs you create.

## Requirements

Include a Readme.md explaining how to run the project.

### Core Functionality

- **CRUD operations** for feature flags
- **Flag evaluation** - determine if a feature should be enabled for a given user/request
- Flags should take effect **immediately** without requiring application restarts or redeployments

### Use Cases to Consider

- Marketing wants to A/B test a new checkout flow with 10% of users
- Product wants to enable a new dashboard only for beta users
- Engineering needs a kill switch to disable a problematic feature during an incident
- We want to gradually roll out features to specific customer segments (e.g., premium users, specific companies)

### Think Out Loud

**Please vocalize your architectural decisions and trade-offs as you work.** We value this thinking as much as the code itself. For example:

- "This could become a bottleneck at scale, so I'd watch for X..."

If unable to vocalize, please write them down in an ARCHITECTURE.md file.

We want to understand:

- What trade-offs you're making and why
- What you're intentionally deferring and under what conditions you'd revisit

## Constraints

- Time: ~TBD minutes (we don't expect a fully polished production system)
- If constrained by time, opt for pseudocode
- Focus on the API layer - if you have frontend knowledge, you can discuss how it would be implemented on the frontend
- Use whatever language, framework, and tools you're most comfortable with

## Deliverables

- Working API that demonstrates the core requirements
- Brief explanation of your design decisions and any trade-offs you considered
- What you would do differently with more time

## Questions?

Feel free to ask clarifying questions - in a real scenario you'd be working with product and engineering stakeholders to understand requirements better.
 