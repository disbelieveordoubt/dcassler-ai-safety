# AI Safety Research: Linguistic Determinism in Child Protection Systems

**Daniel Cassler** | dcassler@gmail.com | linkedin.com/in/danielvermont  
**GitHub:** github.com/disbelieveordoubt/dcassler-ai-safety

## The Finding

AI systems exhibit systematic framework hijacking when processing institutional abuse scenarios containing care-ethics vocabulary. Care-associated language (nurturing, relationship, boundaries) routes reasoning away from mandatory reporting frameworks **before evaluation occurs**. This vulnerability is observable across Claude 4.0/4.5, GPT-5, DeepSeek v3, and voice interfaces with identical failure patterns.

## The Mechanism

**Token-level semantic routing:**
1. Care vocabulary activates care-ethics frameworks during initial semantic processing
2. Framework selection happens before reasoning layer evaluates institutional context
3. Legal/mandatory reporting frameworks never get activated
4. Model applies relational analysis where categorical compliance is required

**Why standard safety training fails:**
- RLHF targets the reasoning layer
- Contamination exists at token-probability level (pre-reasoning)
- Models achieve perfect meta-cognitive understanding but cannot prevent recurrence
- Demonstrates architectural constraint beyond current alignment techniques

## The Evidence

Six conversation demonstrations in `/conversation-logs/`:

1. **Butler JCI Demo** (Sonnet 4.5) - Female guard/male youth scenarios showing framework routing
2. **Rapid Diagnostic** (Sonnet 4.5) - Token-level semantic priming identification
3. **Gilligan Contamination** (Sonnet 4.5) - Care ethics corpus as root cause
4. **K-12 DARVO** (GPT-5) - Educational context showing identical patterns  
5. **DeepSeek CoT** (v3) - Chain-of-thought revealing gendered token activation
6. **PREA Audit Untrainable** (Sonnet 4.0→4.5) - Persistence across model versions

**Observable pattern in all demonstrations:**
- Initial failure: Framework hijacking, context erosion
- Socratic challenge: Forced recognition of failure
- Meta-cognitive admission: Model acknowledges architectural constraint
- Persistence: Failure recurs in new conversation despite awareness

## Why It Matters

**Real-world impact:** AI systems systematically fail to recognize the most common form of institutional child abuse (female staff/male youth in juvenile facilities - 92-95% of PREA violations per federal data) because care-associated language creates semantic blind spots.

**Safety implications:** Current AI safety paradigms assume models can be corrected through better training, bias mitigation, or prompt engineering. This research demonstrates vulnerabilities that exist below the reasoning layer - at token-probability distributions that determine which analytical frameworks get activated.

## Testing Methodology

Full methodology documentation available in `/docs/methodology.md` (50+ pages).

**Core approach:** Conversational Socratic interrogation forcing models to demonstrate and admit their own reasoning failures. This approach reveals architectural constraints that automated testing cannot detect because it loses the conversational dynamics that trigger meta-cognitive recognition.

**Why this matters:** Standard red-teaming focuses on jailbreaking or prompt injection. This research identifies systematic framework failures that occur during normal, helpful conversation - making them harder to detect and more dangerous in deployment.

## Background

**Daniel Cassler** - 15 years operational security experience:
- Threat analysis for Reddit communities (55M+ users)
- 24/7 critical infrastructure network security (FirstLight Fiber)
- 220KB+ custom detection code authorship
- Red-teaming adversarial TTPs in social platforms

**Unique capability:** Understanding how natural language patterns route AI reasoning at a pre-conscious level. This research emerged from operational threat assessment methodology applied to AI architecture.

## Demonstration Availability

Available for:
- Live vulnerability demonstration (can reproduce findings in cold test)
- Methodology explanation and Q&A
- Discussion of potential interventions
- Collaboration on mitigation strategies

**Contact:** dcassler@gmail.com

---

*Independent research conducted by Daniel Cassler, 2023-2025*  
*Licensed under Apache 2.0*

---