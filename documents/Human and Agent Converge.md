## Use Case Human and Agent converge on a Solution

### 1. **Use Case Title**

Haman starts by articulating a goal or desired results and interchanges solutions with an agent while refing the boundaries and policies for a complete solution

### 2. **Purpose / Goal**

The human rapidly approaches as satisfactory solution that might wind up be quite different than want was originally specified due to the realities of available solutions at an acceptable cost.

### 3. **Actors**

| Role | Description |
| --- | --- |
| **Primary Actor** | The human at a UX agent initiating the requst locally that has access to some of the humans' history that might be helpful. |
| **Secondary Actor(s)** | Supporting entities that are online with a wider range of options available.  Could wind up being many cloud agents. |

### 4. **Preconditions**

*What must be true before this use case begins?*

- Local UX agent is cryptographically bound to citizen identity in device hardware.
- The user probably starts the interaction with only a rough goal which will be amended as the interchange unfolds.
- Consent policy token is valid and defined in some well-accepted policy language.
- Cloud Agents' API is reachable and policy-compliant
- Is agent a fiduciary, depends on whether the cloud agent requires access to human assets.
  

### 5. **Trigger**

*What event initiates the use case?*

> For the puposes of this use case we consider that the human is creating a report on the behavior of AI agents in the granting of parol to humans.

### 6. **Main Flow (Basic Path)**

1. Agent constructs policy-compliant request which is traslated into a Cedar policy.
  
2. Consent token is attached and verified
  
3. Cloud API evaluates Cedar policy
  
4. Record is retrieved and returned to agent
  
5. Agent logs transaction ina ledger - a session or relationship is now in existence.
  
6. A response is sent to the user
  
7. Series of steps where user refines the required details which includes access not initially granted to the cloud AIs.
  
8. The user is told what to do to get access to the addition information.
  
9. The user makes a choice about granting or acquiring access to make the report richer.
  
10. Steps 6-9 are repeated until the user is satisfied with the result.
  
11. The connection and all of the accesses granted are terminated and no partial drafts remain beyond the bounds of the local user's device.
  

### 7. **Alternate Flows**

- **Consent Expired**: Agent prompts user to renew
  
- **Policy Denied**: Agent explains denial reason and suggests alternatives
  
- **Network Failure**: Agent retries or defers request
  

### 8. **Postconditions**

*What must be true after the use case completes?*

- Record is securely deleted
- Audit trail is updated with policy and statement of result
- User retains control over data usage
  

### 9. **Exceptions / Errors**

- Invalid delegation
  
- Revoked credentials
  
- API schema mismatch
  

### 10. **Stakeholders**

not germain
  
