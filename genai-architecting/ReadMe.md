## Functional Requirements

1. Ability to translate English to Japanese (Text-to-Text)
2. Ability to translate English to Japanese (Voice-to-Text)
3. Vice-versa for 1 and 2
4. Able to spot check on pronouncation and give feedback
5. Able to score/grade as student progresses
6. Games to keep student engaged

## Non functional Requirements
1. To keep students engaged, latency should be minimal
2. Since LLM API is used, cost consideration to be taken into account
3. Hybrid infra (cloud + on-prem), for privacy
4. Session management, and keep progress in memory (or recall from progress stored in database)

## Risks
1. Privacy risks
2. LLM can learn from data, so PII data should be preserved
3. Data sharing

## Assumptions
1. Inference can be done on local systems (using pure open-source models)
2. Fine-tuning is not required (LoRA - Low-ranking Adaptation)

## Constraints
1. Cost check/considerations
2. On-prem as much as possible, alternate conceptual architecture can be done to implement on cloud
This can also be good opportunity to plan cloud migration of such systems

