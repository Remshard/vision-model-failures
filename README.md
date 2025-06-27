# vision-model-failures
Visual reasoning test cases for AI models — perspective, spatial logic, and multimodal failure analysis.
# Vision Model Failures

This project documents evaluation cases where AI image generation models struggle with basic spatial reasoning, geometric perspective, and physical consistency.

Each test highlights a gap in multimodal model understanding, particularly when rendering scenes with a defined viewpoint, motion context, or 3D structure.

---

##  Why This Matters
While visual models can produce high-quality outputs, they often rely on learned patterns rather than grounded physics or perspective rules. This repo captures those failures in ways that are measurable and repeatable.

---

##  Contents

- `halo-ringworld-perspective.md`: Tests a fixed camera viewpoint from a standing figure on a ringworld surface
- `hamster-pov-wheel-test.md`: Evaluates first-person close-up spatial distortion in motion

Each entry includes:
- The prompt
- The generated image
- A short evaluation
- Key takeaways for model interpretability and QA

---

##  For Researchers & Evaluators
These examples are useful for anyone working on:
- Multimodal model interpretability
- Vision-language QA pipelines
- Prompt stress-testing and synthetic benchmarks

