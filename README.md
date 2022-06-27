# Zero Trust ML (ZTML)

This architecture ensures end-to-end verification and enforcement 
of trustworthy policies from ML governance to ML production.
Like the Zero-Trust Cloud Security Policy, the architecture has a 
Policy Enforcement Point (PEP) and a Policy Decision Point (PDP).
ZTML PEP ensures that trust policy rules provided by the policy
administrator in the ZTML PDP engine is immediately applied 
at each phase of the ML project and its related ML pipelines, 
at each interaction between the trustor (user, auditor) and the trustee (ML system),
at the entry of an ML system (i.e., on input data before access by the
ML system), and at the exit of an ML system (i.e., on predictions before
an action is made).


[1] https://arxiv.org/abs/2206.11981

[2] https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207.pdf
