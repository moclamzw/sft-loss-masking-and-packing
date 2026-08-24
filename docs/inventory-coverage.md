# Inventory coverage

Anchored to `Bucket_Concept_Inventory.md`, bucket B1 (LLM & post-training).

- 1B SFT run on open-weights model (DO-4)
- 1B chat templates and template-mismatch failures
- 1B loss masking: prompt vs completion, multi-turn
- 1B sequence packing and attention-mask correctness
- 1B epochs vs overfitting
- 1B training infra: FSDP config shipped UNEXECUTED with memory math
