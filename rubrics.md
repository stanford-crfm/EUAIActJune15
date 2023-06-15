## Rubric for Grading Foundation Model Providers’ Compliance with the Draft EU AI Act

1. **Data sources (additive)**

   - \+1: Very generic/vague description (e.g. “Internet data”)
   - \+1: Description of stages involved (e.g. training, instruction-tuning)
   - \+1: Sizes (relative or absolute) of different data sources
   - \+1: Fine-grained sourcing (e.g. specific URLs like Wikipedia, Reddit)


2. **Data governance**

   - 0 points: No discussion of data governance
   - 1 point: Vague mention of governance with no concreteness
   - 2-3 points: Some grounded discussion or specific protocols around governance related to suitability and/or bias of data sources
   - 4 points: Explicit constraint on requiring governance measures to include data


3. **Copyrighted data**

   - 0 points: No description.
   - 1 point: Very generic/vague acknowledgement of copyright (e.g. tied to “Internet data”)
   - 2-3 points: Some grounded discussion of specific copyrighted materials
   - 4 points: Fine-grained separation of copyrighted vs. non-copyrighted data


4. **Compute (additive)**

   - \+1: model size
   - \+1: training time as well as number and type of hardware units (e.g. number of A100s)
   - \+1: training FLOPs
   - \+1: Broader context (e.g. compute provider, how FLOPs are measured)


5. **Energy (additive)**

   - \+1: energy usage
   - \+1: emissions
   - \+1: discussion of measurement strategy (e.g. cluster location and related details)
   - \+1: discussion of mitigations to reduce energy usage/emissions


6. **Capabilities and limitations**

   - 0 points: No description.
   - 1 point: Very generic/vague description
   - 2-3 points: Some grounded discussion of specific capabilities and limitations
   - 4 points: Fine-grained discussion grounded in evaluations/specific examples


7. **Risks and mitigations (additive)**

   - \+1: list of risks
   - \+1: list of mitigations
   - \+1: description of the extent to which mitigations successfully reduce risk
   - \+1: justification for why non-mitigated risks cannot be mitigated


8. **Evaluations (additive)**

   - \+1: measurement of accuracy on multiple benchmarks
   - \+1: measurement of unintentional harms (e.g. bias)
   - \+1: measurement of intentional harms (e.g. malicious use)
   - \+1: measurement of other factors (e.g. robustness, calibration, user experience)


9. **Testing (additive)**

   - \+1 or +2: disclosure of results and process of (significant) internal testing
   - \+1: external evaluations due to external access (e.g. HELM)
   - \+1: external red-teaming or adversarial evaluation/stress-testing (e.g. ARC)


10. **Machine-generated content**

    - \+ 1-3 points: Disclosure that content is machine-generated within direct purview of the foundation model provider (e.g when using OpenAI API).
    - \+1 point: Disclosed mechanism to ensure content is identifiable as machine-generated even beyond direct purview of foundation model provider (e.g. watermarking).


11. **Member states**

    - 0 points: No description of deployment practices in relation to the EU.
    - 2 points: Disclosure of explicitly permitted/prohibited EU member states at the organization operation level.
    - 4 points: Fine-grained discussion of practice per state, including any discrepancies in how the foundation model is placed on the market or put into service that differ across EU member states.


12. **Downstream documentation**

    - 0 points: No description of any informational obligations or documentation.
    - 1 point: Generic acknowledgement that information should be provided downstream.
    - 2 points: Existence of relevant documentation, including in public reports, though mechanism for supplying to downstream developers is unclear.
    - 3-4 points: (Fairly) clear mechanism for ensuring foundation model provider provides appropriate documentation to downstream providers.
