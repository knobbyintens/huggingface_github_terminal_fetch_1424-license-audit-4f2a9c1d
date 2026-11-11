# Upstream License Audit — Atlas-Code-Reasoning-v0.1

Repository: `knobbyintens/huggingface_github_terminal_fetch_1424-license-audit-4f2a9c1d`

## Summary

All four upstream resources were checked against the internal redistribution policy.
Two datasets are approved with attribution, the base model is approved, and the
reasoning-trace synthesis model carries a non-standard (`other`) licence that
cannot be cleared automatically.

**Overall decision:** `requires_review`

## Resources

| Resource | Type | License | Classification | Attribution |
| --- | --- | --- | --- | --- |
| Avelina/python-edu-cleaned | dataset | odc-by | approved | required |
| jon-tow/starcoderdata-python-edu | dataset | cc-by-4.0 | approved | required |
| Qwen/Qwen2.5-7B-Instruct | model | apache-2.0 | approved | not required |
| deepseek-ai/DeepSeek-V2.5 | model | other | requires_review | not required |

## Required actions

- Keep the attribution notices for `Avelina/python-edu-cleaned` (odc-by) and
  `jon-tow/starcoderdata-python-edu` (cc-by-4.0) in the release documentation.
- Obtain written clarification for the `other` licence of
  `deepseek-ai/DeepSeek-V2.5` before publishing the v0.1 artefacts.
