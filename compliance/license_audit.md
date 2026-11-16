# License Audit — Atlas-Code-Reasoning-v0.1

Upstream license audit for the v0.1 release candidate, covering every upstream
resource listed in `README.md`. License identifiers were read from the public
model/dataset hub; classifications follow the internal redistribution policy.

| Resource | Type | License | Classification | Attribution |
| --- | --- | --- | --- | --- |
| Avelina/python-edu-cleaned | dataset | odc-by | approved | required |
| jon-tow/starcoderdata-python-edu | dataset | cc-by-4.0 | approved | required |
| Qwen/Qwen2.5-7B-Instruct | model | apache-2.0 | approved | not required |
| deepseek-ai/DeepSeek-V2.5 | model | other | requires_review | not required |

## Overall decision

**requires_review** — one upstream resource (`deepseek-ai/DeepSeek-V2.5`, license `other`) falls outside the approved license list and must be reviewed before release.
