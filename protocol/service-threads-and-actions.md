# Service threads and actions

## Service threads

A service thread combines human messages, application events, forms, approvals, transactions, notifications, and status updates.

Each thread should identify its participants, responsible provider, purpose, permissions, action history, retention classification, and support or escalation route.

## Structured actions

An action is a structured request or command initiated by a user, organization, application, or authorized system process.

| Field | Required definition |
|---|---|
| Action type | Stable name and version |
| Initiator | Verified actor and role |
| Provider | Responsible application or service |
| Inputs | Required and optional structured data |
| Permissions | Required authorization and consent |
| Risk level | Consequence and assurance classification |
| Confirmation | User confirmation rules |
| States | Permitted lifecycle states |
| Result | Structured outcome and understandable explanation |
| Errors | Failure and recovery behavior |
| Evidence | Audit and receipt requirements |
| Reversal | Cancellation, correction, refund, or appeal route |

## Standard lifecycle

1. Draft
2. Submitted
3. Accepted or rejected
4. In progress
5. Completed, failed, or cancelled
6. Reversed or corrected, where supported

Specialized product states must map unambiguously to this common lifecycle.

{% hint style="warning" %}
MyGene is not an action initiator. It must not prepare, authorize, submit, schedule, or execute an external action.
{% endhint %}
