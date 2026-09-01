# Sample Guardrails for AI Prompts

Guardrails are instructions that help shape AI output. They can make the response more transparent, constrained, and easier to review. Guardrails do not eliminate the need for verification.

| Add this phrase | Why it helps |
|---|---|
| If you are uncertain, say so and explain why. | Makes uncertainty visible. |
| Do not invent citations. If you cite, label citations as "needs verification." | Reduces the risk of citation hallucination and reminds users to check sources. |
| List assumptions you made from missing context. | Makes hidden assumptions easier to identify. |
| Provide a quick verification plan: what to check and where. | Supports accountability and follow-up review. |
| Ask me 1 to 3 clarifying questions before answering when needed. | Improves fit and context before generating an answer. |
| Use only the information I provide. | Reduces unsupported additions when working from a specific source. |
| Separate summary from interpretation. | Helps users distinguish what the source says from what the model infers. |
| Identify claims that require verification. | Helps users prioritize what to check. |
| Do not provide legal, medical, policy, or compliance approval. | Helps maintain role boundaries. |

## Reminder

Guardrails are useful, but they are not guarantees. AI outputs still require review and verification.
