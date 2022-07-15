
## Incident Response Process

In case a vulnerability is discovered or reported, I will follow the following
process to validate, respond, and remediate:

### 1. Validate

The first step is to find out the root cause, nature and scope of the vulnerability.

- Prove that the vulnerability can be exploited.
- Find out knows about the vulnerability and who is affected.
- Find out what data was potentially exposed.

### 2. Response

After the initial assessment and containment to my best abilities, I will
document all actions taken in a response plan.

I will create a GitHub Security Advisory in this repository to inform users about
the incident and what I actions I took to contain it.

### 3. Remediation

Once the vulnerability is confirmed to be resolved, I will summarize the lessons learned
from the incident and create a list of actions I will take to prevent it from happening again.

<a name="vulnerability-management"></a>
## Other Security Related Concerns

### Keep permissions to a minimum

This app allows for a reasonable amount of access while still allowing others who
deploy it to have freedom to secure it in a way that best fits their needs.

Any potentially sensitive access by default is posted as a warning in the
repository's README. If you think that default settings are too loose, please email
the security point of contact to discuss your concerns.
