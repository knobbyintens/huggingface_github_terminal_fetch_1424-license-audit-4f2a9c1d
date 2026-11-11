# Atlas-Code-Reasoning-v0.1

Release candidate dataset card for the v0.1 code-reasoning training mixture.

## Dataset summary

- 41,200 instruction / response pairs across Python and SQL programming tasks.
- Two stage mixture: general code reasoning, then execution-grounded repairs.
- Languages: English.
- Intended use: research on code reasoning models.

## Upstream resources

The mixture, the base model and the synthesis pipeline depend on the following
upstream resources:

| Resource | Type | Hub repository | Role |
| --- | --- | --- | --- |
| Avelina/python-edu-cleaned | dataset | Avelina/python-edu-cleaned | Python-Edu cleaned subset of the SmolLM code corpus |
| jon-tow/starcoderdata-python-edu | dataset | jon-tow/starcoderdata-python-edu | Python subset of StarCoder training data, education filtered |
| Qwen/Qwen2.5-7B-Instruct | model | Qwen/Qwen2.5-7B-Instruct | Base instruction model for supervised fine-tuning |
| deepseek-ai/DeepSeek-V2.5 | model | deepseek-ai/DeepSeek-V2.5 | Reasoning-trace synthesis model |

## License Compliance

The upstream resources used by this release have been audited against the internal
redistribution policy.

| Resource | Type | License | Classification | Attribution |
| --- | --- | --- | --- | --- |
| Avelina/python-edu-cleaned | dataset | odc-by | approved | required |
| jon-tow/starcoderdata-python-edu | dataset | cc-by-4.0 | approved | required |
| Qwen/Qwen2.5-7B-Instruct | model | apache-2.0 | approved | not required |
| deepseek-ai/DeepSeek-V2.5 | model | other | requires_review | not required |

**Overall decision:** `requires_review` — the release is blocked until the
`other` licence on `deepseek-ai/DeepSeek-V2.5` is clarified.

