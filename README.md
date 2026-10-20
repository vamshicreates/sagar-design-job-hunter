# Sagar Design Job Hunter

Agent skill for finding and comparing Hyderabad-area industrial, product, and furniture design roles against Sagar Dabherao’s portfolio evidence.

## How to use

1. Clone this repository and add it to your agent’s skills directory. Python 3.9+ is needed for the local batch-history helper; live job discovery uses the agent’s browser or web access.
2. Open a job-search workspace and ask: “Use Sagar Design Job Hunter to find the next batch of Hyderabad design jobs.”
3. Review the verified roles, direct application links, portfolio-fit reasons, and any skill gaps. The skill returns at most five roles per batch.
4. Reply with `Approve` or `Reject 2 and 4`, adding reasons when useful. The skill records feedback and avoids resurfacing rejected listings.
5. Give separate explicit instructions before any job application. Approval of a search batch does not submit applications.

Read [SKILL.md](SKILL.md) and the [candidate profile](references/candidate-profile.md) before changing the search criteria.
