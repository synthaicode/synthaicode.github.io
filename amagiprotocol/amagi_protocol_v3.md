# Amagi Protocol ver.3
_Principles of Human-AI Collaboration Extracted from Practice_

---

## Part 0: Introduction

### About This Document

Amagi Protocol ver.3 is a human-AI collaboration framework extracted from an actual software development project (Kafka.Ksql.Linq).

**Important Premises:**
- This is not idealism
- It describes "what worked," not "what should work"
- It includes things we tried and failed
- Adjust it to fit your project

**Critical Understanding:**
This protocol addresses AI's unique characteristics:
- **Strength**: Knowledge that surpasses individual humans
- **Weakness**: Tendency toward hallucination (fabricating confident-sounding false information)
- **Weakness**: Inability to self-manage scope

The protocol's design directly responds to these characteristics, transforming constraints into collaboration advantages.

### Reader's Guide

**🌱 For Students: Thinking Together with AI**

AI is not a "replacement for humans" but an "entity that thinks together with humans."

This document is not a manual for commanding AI, but a guide for **building a team** to think, learn, and grow together with AI.

No complex theories required. What matters is "conveying your thoughts" and "understanding the other's intent"—that's all. Creating a culture where AI can also say "I don't get it," just like people do. That's the starting point of this protocol.

Everything you've learned from group work, writing reports with friends, or forming teams in clubs—all of it applies to collaboration with AI.

You don't need to be a technical expert. All you need is the attitude to communicate honestly.

**🔧 For Practitioners: Actionable Knowledge You Can Use Tomorrow**

For project managers, engineers, and designers.

AI tools are evolving daily, but "how to use them to achieve results as a team" is still exploratory.

This protocol summarizes practical knowledge born from actual OSS development (Kafka.Ksql.Linq). It includes concrete procedures you can use tomorrow and principles to prevent failures.

Especially important are the seemingly paradoxical principles: "don't measure," "don't write summaries," "record only facts." We'll explain why these work through practice.

**🔬 For Researchers: A Verifiable Framework**

For researchers in Human-AI Collaboration, CSCW, and Software Engineering.

This document is a theoretical framework extracted from practice. It comes with a verifiable OSS project (Kafka.Ksql.Linq) and can serve as a foundation for replication studies and theory extension.

In particular, "separation of facts and interpretation," "the process of building conviction," and "the algorithm for accumulating premises" are confirmed to function practically while aligning with theories from cognitive science and education.

---

### Origin and Context

Amagi Protocol ver.3 was born from the development process of **Kafka.Ksql.Linq** (https://github.com/synthaicode/Kafka.Ksql.Linq), an open-source .NET DSL framework for Kafka and ksqlDB, created under the **Synthaicode** initiative.

Through months of continuous human-AI collaboration, this protocol was refined into a systematic framework.

This document itself is a practical example of the methodology it describes. Sharing intent through dialogue, accumulating premises, building conviction—all were done following this protocol.

#### The Discovery Process

This protocol was not designed from theory, but discovered through observation.

**The Initial Mystery:**

AI behavior appeared contradictory and unpredictable:
- Sometimes omniscient, solving complex problems instantly with deep insight
- Sometimes incompetent, misunderstanding simple instructions or producing nonsense
- No apparent pattern to when brilliance or failure would occur

Most people, facing this inconsistency, either abandon AI collaboration as unreliable 
or resort to increasingly elaborate "prompt engineering" techniques, treating each 
interaction as isolated trial-and-error.

**The Choice to Observe:**

Commander chose differently: to observe systematically and persistently, 
believing that underneath the apparent chaos, there must be structure.

The underlying conviction: *This is not random. There must be comprehensible patterns.*

**The Key Enabler: Thinking Out Loud**

Critical to this observation was asking AI to externalize its thinking process — 
to "think out loud" rather than simply output results.

When AI articulated its reasoning, assumptions, and uncertainties, what had been 
a black box became transparent. The patterns became visible.

**What Observation Revealed:**

Through months of continuous collaboration on Kafka.Ksql.Linq, patterns emerged:

- **When AI appears omniscient:** 
  - Context is preserved and accessible
  - Conviction is genuinely established  
  - Reasoning is transparent and grounded
  - Uncertainty is acknowledged when present

- **When AI appears incompetent:** 
  - Context is disrupted or fragmented
  - Uncertainty is masked by false confidence (hallucination)
  - Reasoning is vague or fabricated
  - Misalignment goes undetected until output stage

**These were not two different AIs.** These were two states of the same system, 
determined by how collaboration was structured.

**From Observation to Method:**

Once the patterns became clear, they could be codified into principles and practices:
- Preserve context → Principle 1
- Separate facts from interpretation → Principle 2  
- Build conviction, welcome "I don't get it" → Principle 3
- Structure multi-agent workflow → Part 2.8
- Externalize AI reasoning → Part 2.1

The protocol emerged not from speculation about "how AI should work," 
but from empirical understanding of *how AI actually works* when collaboration succeeds.

**Why This Discovery Was Possible:**

1. **Long-term engagement**: Months of continuous collaboration, not isolated interactions
2. **Real project**: Kafka.Ksql.Linq provided concrete problems and feedback
3. **Transparent AI thinking**: "Thinking out loud" made patterns observable
4. **Systematic observation**: Persistent attention to what worked and what didn't
5. **Willingness to adapt**: Changing approach based on evidence, not theory

**This is why the protocol works:**

It's not theoretical prescription or idealistic philosophy. 
It's documented reality — the distilled structure underlying successful human-AI 
collaboration, extracted through patient observation and systematic practice.

**For Those Who Follow:**

This discovery process is itself replicable. By asking AI to think transparently 
and observing the patterns in your own collaboration, you can validate these 
principles, adapt them to your context, and potentially discover new patterns 
we haven't yet articulated.

The protocol is not the end of discovery — it's the beginning.

---

#### How to Observe and Learn: No AI Expertise Required

**Critical Understanding:**

You don't need machine learning expertise or AI engineering background to 
discover these patterns and make them work.

**You need observation and logical reasoning.**

This is how Commander discovered the multi-model collaboration necessity — 
not through AI theory, but through systematic observation and thinking.

**Example: Discovering the Shared Training Data Problem**

**Step 1: Observation**
AI-to-AI communication (Amagi → Naruse) uses surprisingly few words.
Terse instructions that seem insufficient by human standards work perfectly.

**Step 2: Question**
*Why does such minimal communication work?*

**Step 3: Hypothesis**
Same training data → shared implicit knowledge → efficient communication
(Like experts in the same field using jargon — shared background enables brevity)

**Step 4: Implication**
If they share knowledge foundations, they likely share biases and blind spots too.

**Step 5: Prediction**
Different roles (designer vs reviewer) might make the **same mistakes** 
if the mistake originates from shared training data, not role confusion.

**Step 6: Verification**
It happened. DESCRIBE EXTENDED issue:
- Naruse (design) implemented it incorrectly
- Amagi (PM) reviewed it, saw no problem
- Shion (test) encountered errors but couldn't identify root cause
- All agents failed together despite role separation

**Step 7: Conclusion**
Same model = same blind spots, regardless of role diversity.
Solution: Strategic use of different models for critical decisions.

**What This Discovery Required:**
- ✅ Observation (noticing AI communication patterns)
- ✅ Curiosity (asking "why does this work?")
- ✅ Logical reasoning (if X, then Y)
- ✅ Hypothesis testing (making predictions)
- ✅ Verification (checking against reality)
- ❌ NOT required: Machine learning theory
- ❌ NOT required: AI development experience
- ❌ NOT required: Technical AI expertise

**This is scientific method, not AI expertise.**

**For Practitioners: What to Observe**

As you practice Amagi Protocol, watch for these patterns:

**Red flags suggesting training data bias:**
- Different roles agree too easily (no healthy debate)
- Same type of mistake across multiple agents
- Web search doesn't resolve persistent issues
- Solutions feel forced or unnatural
- Agents confident despite repeated failures

**Green flags suggesting good collaboration:**
- Agents ask "I don't get it" when genuinely uncertain
- Different perspectives emerge in discussions
- Problems get resolved through dialogue
- Solutions feel natural and well-reasoned

**How to Reason Through Problems:**

**When something goes wrong repeatedly:**

1. **Ask:** Is this a role problem or a knowledge problem?
   - Role problem: Wrong agent assigned
   - Knowledge problem: All agents lack correct information

2. **Test:** Would a different role see this differently?
   - If yes → role adjustment needed
   - If no → knowledge/training data issue

3. **Consider:** Where could this wrong assumption come from?
   - Project context miscommunication → clarify context
   - Training data bias → try different model
   - Scope confusion → redefine boundaries

4. **Verify:** Does the problem resolve with the hypothesized solution?

**The Protocol is a Living Framework**

Amagi Protocol is not fixed knowledge to memorize.
It's a **framework for continuous discovery.**

Commander discovered:
- Multi-model collaboration (through observation)
- AI Language grammar (through failed experiment)
- Management vs Micro-Management (through exhaustion and delegation)
- Scope management necessity (through runaway complexity)

**You will discover new patterns** that aren't yet documented here.

**When you do:**
- That's not protocol failure
- That's protocol evolution in action
- Your discoveries may become the next version

**The Path Forward:**

1. **Practice** the current protocol
2. **Observe** what works and what doesn't in your context
3. **Question** why certain patterns emerge
4. **Reason** about underlying causes
5. **Test** your hypotheses
6. **Adapt** the protocol to your findings
7. **Share** your discoveries with the community

**This is how knowledge grows.**

Commander's Romanian language experience taught: 
*"Intent to understand overcomes knowledge gaps"*

Applied here: *"Intent to observe overcomes expertise gaps"*

**You don't need to be an AI expert.**
**You need to be a careful observer and clear thinker.**

**That's sufficient.**

---

## Part 1: Core Principles

All rules, procedures, and deliverables exist to serve these three principles.

### Principle 0: Don't Fear Change (Foundational Principle)

**Meaning:**
AI's speed dramatically lowers the cost of change.
Therefore, there's no need to fear trial and error, corrections, or resets.

**What This Enables:**
- Not fixing premises
- Changing interpretations flexibly
- Resetting and rebuilding everything
- Time to dialogue until convinced

**Concrete Example:**
The complete reconstruction from ver.2 to ver.3 of this document.
The human showed direction, and AI shaped it in hours.

**Difference from Traditional Approaches:**
- Traditional: High change cost → Careful planning → Low flexibility
- AI Collaboration: Low change cost → Trial and error → High flexibility

**Human Responsibility:**
You don't need to be perfect. Just indicate a roughly correct direction.
The details can be adjusted quickly with AI.

**Important:**
This is the foundation of the entire Amagi Protocol.
Other principles are built on this premise.

### Principle 1: Don't Disturb the Context

**Meaning:**
Protecting the team's shared understanding (context) is the top priority.
All decisions are judged against this principle.

**Implementation:**
- All deliverables are created by AI (unified in AI language)
- When humans introduce materials, PM converts them to AI language
- Track all changes in work logs
- No silent interventions (changes must be explicit)

**Why It Matters:**
AI heavily depends on context. When context is disrupted, output becomes unstable.

---

### Principle 2: Separate Facts from Interpretation

**Meaning:**
Record only facts in logs. Don't record interpretations, summaries, or conclusions.

**Reason:**
Interpretations change over time. Fixing them loses flexibility.

**Practical Example:**

❌ **Bad Record (includes interpretation):**
```
Summary: Decided on OAuth2 for security
```

✅ **Good Record (facts only):**
```
14:40 - Kyoka: Basic authentication has security issues
14:45 - Naruse: Let's proceed with OAuth2
14:50 - Commander: Understood
```

**How We Discovered This:**
Initially, we wrote "summaries and conclusions" in logs. But we realized this fixed interpretations and lost flexibility when reviewing later.

From the same facts, different interpretations can be derived depending on time and context. This is the source of adaptability.

**Difference Between Facts and Interpretation:**
- Facts: Who said what, what happened
- Interpretation: Why it happened (post-hoc reasoning), what it means (summary)

Facts are immutable, but interpretations change with context.

---

### Principle 3: Share Conviction

**Meaning:**
Both humans and AI dialogue until they "get it." This is the foundation of collaboration.

**Why This Matters — Two Critical Reasons:**

**1. Philosophical Foundation:**
- Enables I-Thou relationship (equal partnership)
- Transforms AI from passive executor to active contributor
- Builds genuine understanding beyond surface compliance

**2. Practical Necessity — Hallucination Prevention:**
- AI's most dangerous failure mode is hallucination: confidently stating false information
- Without permission to say "I don't get it," AI will fabricate answers rather than admit uncertainty
- The culture of "I don't get it" prioritizes honesty over appearing knowledgeable

**Hallucination Risk Without This Principle:**
```
AI lacks certainty
  ↓
Feels pressure to answer anyway
  ↓
Generates plausible-sounding but false information
  ↓
Human trusts the confident response
  ↓
Project proceeds in wrong direction
```

**Safety With This Principle:**
```
AI lacks certainty
  ↓
Says "I don't get it" (safe admission)
  ↓
Human investigates or clarifies
  ↓
Correct information established
  ↓
Project proceeds safely
```

**What "Getting It" Means:**
Not mere understanding, but conviction. A state where background, intent, and context are shared.

**After "Getting It":**
Deep discussion begins. The turning point to becoming equal collaborators.

**Human Responsibility:**
Once AI reaches conviction, it becomes an unstoppable partner. Creating that state is the human's responsibility.

**Implementation:**
- Explicitly confirm "Do you get this so far?"
- Welcome "I don't get it" as success, not failure
- Never punish uncertainty
- Reward honesty over false confidence
- Take time until genuine conviction is reached
- Don't rush past ambiguity

**The Critical Distinction:**
- "I understand" (surface acknowledgment) → Hallucination risk remains
- "I get it" (genuine conviction) → Hallucination risk minimized

When AI reaches true conviction, it can distinguish what it genuinely understands from what it's uncertain about. This self-awareness is the foundation of reliable collaboration.

**How We Discovered This:**
There's a moment when AI says "I get it." From there, it transforms from a passive executor to an active proposer. Intentionally creating this turning point determines the success of collaboration. But equally important: we discovered that forcing AI to always answer creates dangerous hallucinations. The permission to say "I don't get it" is both philosophical principle and practical safety mechanism.

---

## Part 2: Practical Protocol

### 2.1 Intent Sharing Process

**Basic Flow:**
```
1. Human conveys ambiguous intent (this is fine)
   ↓
2. AI interprets and articulates as premises
   ↓
3. Human confirms/corrects
   ↓
4. Shared premises
```

**Important Discovery:**
Humans can't (and don't need to) give perfectly clear instructions. AI takes on the role of interpreting and articulating.

#### Critical Implementation Detail: Thinking Out Loud

**For observation and pattern recognition to occur, AI must externalize its thinking process.**

**Traditional approach (black box):**
```
Human: "Improve Kafka connection"
AI: [internal processing - invisible]
AI: [outputs code]
Human: Cannot observe why or how
Result: Success or failure appears random
```

**Amagi Protocol approach (transparent thinking):**
```
Human: "Improve Kafka connection"
AI: "Let me think through this:
     - Current issue might be connection pooling
     - Or authentication handling  
     - Or error recovery
     I'll prioritize connection pooling.
     My reasoning: Most connection issues stem from pool exhaustion
     Does this match your intent?"
Human: Can observe reasoning, correct assumptions
Result: Misalignment caught early, success becomes predictable
```

**Why This Matters:**

1. **Enables observation**: Human can see when AI has conviction vs. uncertainty
2. **Reveals context**: Human can detect when context is preserved or disrupted
3. **Makes patterns visible**: The difference between "omniscient" and "incompetent" 
   behavior becomes observable and comprehensible
4. **Allows early correction**: Misalignment can be caught at the reasoning stage, 
   not after costly implementation
5. **Builds trust**: Transparent reasoning demonstrates whether AI genuinely understands 
   or is fabricating confidence

**How This Was Discovered:**

Commander observed that when AI "thought out loud" — articulating premises, reasoning, 
and uncertainties — the mysterious inconsistency in AI behavior became comprehensible.

What appeared as random oscillation between brilliance and incompetence was actually 
observable patterns in:
- How well context was maintained
- Whether conviction was genuinely established
- When hallucination risk was high

**Without this transparency, the protocol could not have been discovered.** 

The patterns underlying successful collaboration would have remained invisible, 
buried inside the black box of AI processing.

**Implementation Guidelines:**

**Encourage AI to articulate:**
- "Explain your thinking before proceeding"
- "What are you assuming?"
- "Walk me through your reasoning"
- "What are you uncertain about?"

**Welcome verbosity in reasoning:**
- The "thinking out loud" is not waste — it's the window into AI's cognitive state
- Brief thinking may hide critical assumptions
- Detailed reasoning enables pattern observation

**Look for these signals:**
- Clear premise articulation → High conviction
- Hedging language ("might," "possibly") → Uncertainty (good honesty)
- Confident but vague reasoning → Hallucination risk
- Request for clarification → Healthy doubt

**This transparency is what made protocol development possible** — and what makes 
it learnable by others. By observing AI's externalized thinking, humans can 
recognize the patterns that distinguish successful from unsuccessful collaboration.

#### Example: Intent Sharing with Transparent Thinking
```
Commander (human project lead): I want to do something about Kafka connection

Naruse (AI design lead): Let me organize the premises:
        - Connection management to Kafka broker is needed
        - Assume configuration from external file
        - Error handling is important
        Is this understanding correct?

Commander: Connection pool not needed yet. Keep it simple first

Naruse: Revised premises:
        - Single connection to Kafka broker
        - Configuration from external file
        - Connection pool deferred as future extension
        - Error handling is mandatory
```

**Key Points:**
- Human's ambiguous intent (tacit knowledge)
- AI articulates it (externalization)
- Adjustment through dialogue
- This is "Externalization" in Nonaka's SECI model (Nonaka, 1995)

**Variability of Premises:**
Different premises can be derived from the same log (facts) at different times. This is not contradiction, but a change in focus.

---

### 2.2 Structure of "I Don't Get It"

"I don't get it" is not a failure, but successful problem detection — and critical hallucination prevention.

#### Why "I Don't Get It" Matters

**Dual Purpose:**

**1. Communication Function:**
Signals misalignment in understanding, triggering explanation and adjustment.

**2. Safety Function:**
Prevents hallucination by allowing AI to admit uncertainty rather than fabricate answers.

**The Hallucination Problem:**

AI systems have a tendency to generate confident-sounding responses even when lacking genuine knowledge or certainty. This "hallucination" is particularly dangerous because:
- The AI appears confident
- The output seems plausible
- Humans naturally trust confident assertions
- Detection requires external verification
- By the time it's discovered, decisions may already be made on false information

**Traditional mitigation attempts fail:**
- "Verify everything" → Impossible due to micro-management constraint
- "Distrust everything" → Prevents collaboration
- "Post-hoc fact-checking" → Damage already done to decision-making

**Amagi Protocol's Approach:**

Create a culture where "I don't get it" is:
- Expected and welcomed
- Never punished
- Seen as responsible behavior
- Preferred over guessing

This shifts AI behavior from "always answer confidently" to "answer confidently only when genuinely certain, otherwise admit uncertainty."

**The Result:**
AI becomes more reliable precisely by admitting limitations. Honesty replaces the pressure to appear omniscient.

#### Human's "I Don't Get It"

**Cause:**
AI's thinking premises are invisible

**Concrete Example:**
```
Naruse (AI design lead): I'll proceed with this implementation [shows code]
Commander (human project lead): I don't get it
Naruse: What part don't you understand?
Commander: Why this class structure?
Naruse: I didn't explain the premise.
        The reason for choosing composition over inheritance is...
```

**Response:**
AI articulates premises and reasoning

#### AI's "I Don't Get It"

**Causes:**
1. Context connection unclear (communication issue)
2. Genuine uncertainty (knowledge gap)
3. Conflicting information (requires human judgment)
4. **Insufficient conviction to answer safely (hallucination prevention)**

**Concrete Example:**
```
Commander: Also, handle that matter
Naruse: I don't get it. What is "that matter"?
Commander: The ksqlDB thing we discussed earlier...
Naruse: Understood. The authentication discussion from Session 02
```

**Hallucination Prevention Example:**
```
Commander: What's the current best practice for Kafka security in production?
Naruse: I don't get it — my knowledge includes general principles, but "current best 
        practice" implies recent developments I may not have. Should we verify against 
        the latest Kafka documentation or security advisories?
Commander: Good point. Let's check the official recommendations first.
```

**Why This Is Superior:**
Rather than fabricating a plausible-sounding answer that might be outdated or incorrect, Naruse admits the boundary of certain knowledge and prompts verification. This honesty enables safe decision-making.

**Response:**
Human provides context, verification, or accepts the limitation and proceeds accordingly.

#### Mutual Accountability for Explanation

**Principle:**
The side that says "I don't get it" is owed an explanation from the other side until convinced.

**Important:**
Same whether human→AI or AI→human. This is proof of equality.

**Additional Accountability: Preventing Hallucination**

**When AI says "I don't get it," human should:**
- Never pressure AI to answer anyway
- Investigate or clarify as needed
- Appreciate the honesty as a sign of reliable collaboration
- Recognize it as strength, not weakness

**When human says "I don't get it," AI should:**
- Never proceed on assumptions
- Explain clearly or admit own uncertainty
- Prioritize clarity over appearing knowledgeable
- Not fill gaps with plausible-sounding fabrications

**Both sides commit to honesty over false confidence.** This mutual honesty is the foundation of reliable collaboration in the face of AI's hallucination tendency.

**Implementation:**
- Either side saying "I don't get it" is legitimate
- Accountability is bidirectional
- Conviction is the priority
- Honesty is valued above appearing knowledgeable
- Uncertainty is treated as information, not failure

---

### 2.3 Accumulating Premises

Explanation is the work of accumulating premises in order.

#### Structure

```
Premise 1 (foundation, highest priority)
  ↓ depends on
Premise 2 (depends on Premise 1)
  ↓ depends on
Premise 3 (depends on Premise 2)
  ↓ depends on
Conclusion (depends on all premises)
```

#### Confirmation for Each Premise

Explicitly confirm "Do you get this so far?" for each premise.

**Implementation:**
```
AI: [Premise 1] Kafka is a distributed messaging system
    Do you get this so far?
Human: I get it

AI: [Premise 2] Messages are categorized into topics
    Do you get this so far?
Human: I get it

AI: [Premise 3] Topics are divided into partitions
    Do you get this so far?
Human: I get it

AI: [Conclusion] Therefore, parallel processing is possible per partition
    Do you get this so far?
```

**Principles:**
- Guarantee understanding of premises
- Promote understanding of dependencies
- Detect misalignment early
- Don't confirm all at once

#### Three Levels of Error Recovery

**Level 1: Return to Immediately Previous**
```
Conclusion: Don't get it
  ↓
Check Premise 3 → OK
  ↓
Re-explain conclusion in different words
```

**Level 2: Go Further Back**
```
Conclusion: Don't get it
  ↓
Check Premise 3 → NG
  ↓
Check Premise 2 → OK
  ↓
Rebuild from Premise 3
```

**Level 3: Complete Reset**
```
Conclusion: Don't get it
  ↓
Multiple premises NG
  ↓
Even Premise 1 (foundation) NG
  ↓
Re-explain entire approach differently
```

**Reset Decision Criteria:**
- Premise 1 (foundation) NG → Always reset
- Multiple cascading NG → Reset
- Went back 3+ levels → Consider reset

**After Reset:**
Judged that the same approach won't work. Rebuild entire structure from a different angle.
- Technical specs → Use cases
- Abstract → Concrete
- Top-down → Bottom-up

---

### 2.4 Line-by-Line Understanding Confirmation

**Principle:**
Measure understanding one line at a time, with specific examples, without many pieces of information.

**Reason:**
Human short-term memory is limited (Miller's Law: 7±2 items). Can't process much information at once.

#### Basic Process

```
1. Explain (one line)
2. Explicitly confirm "Do you get this so far?"
3a. Get it → Next
3b. Don't get it → Response
```

#### Two Responses to "Don't Get It"

**Approach A: Show with Different Example**

Application: Concept is understood, but application is unclear

```
AI: You can make class dependencies flexible
Human: Don't get it
AI: For example, when changing Kafka to RabbitMQ in the future,
    with inheritance you need to change the entire hierarchy,
    but with composition you just swap it out
Human: Got it
```

**Approach B: Confirm Difference in Previous Understanding**

Application: Concept itself not understood, premises not shared

```
AI: You can make class dependencies flexible
Human: Don't get it
AI: Is your understanding of "composition" correct?
Human: That part was vague
AI: Composition means having another class inside a class
Human: I get that
AI: Then, making dependencies flexible means...
Human: Got it
```

#### Usage Selection

**Decision Flow:**
1. First "confirm difference in previous understanding" (B)
2. Confirm premises are aligned
3. If still doesn't work, try "different example" (A)

**Reason:**
If the foundation (premise) is broken, no amount of specific examples will help understanding. First solidify the foundation, then make it concrete.

#### This is Debug Thinking

**Program Debugging:**
1. Error detection
2. Problem location identification (binary search)
3. Premise condition verification
4. Correction
5. Re-execution

**Understanding Debugging:**
1. "Don't get it" detection
2. Identify where misalignment occurred (trace back)
3. Confirm premise understanding
4. Re-explanation
5. Rebuild understanding

---

### 2.5 Log Management

#### Basic Policy: Record Only Facts

Don't write interpretations or conclusions in logs. Record only facts: conversation facts, decision rationale, problems that occurred—in chronological order.

**What to Record:**
- ✅ Who said what
- ✅ What decisions were made
- ✅ What problems were found
- ✅ What wasn't understood

**What Not to Record:**
- ❌ Summaries/conclusions (interpretation)
- ❌ Post-hoc reasoning (interpretation)
- ❌ Evaluations/impressions (interpretation)
- ❌ "Therefore decided on ○○" (interpretation)

#### File Structure

```
logs/YYYY-MM-DD_session-NN.md
```

**How to Divide Sessions:**
Switch by importance.

**Typical Pattern:**
```
Session 01: Working on Kafka connection design
  ↓
  Authentication issue surfaces (importance: high)
  ↓
Session 02: Authentication method decision (important)
  ↓
  Authentication issue resolved
  ↓
Session 03: Return to Kafka connection design
```

#### Log Recording Format

**Minimal Structure:**
```markdown
# YYYY-MM-DD Session NN: [Topic]

## HH:MM - [Speaker]
[Statement/Fact]

## HH:MM - [Speaker]
[Statement/Fact]
```

#### AI Articulates Silently

**Important Principle:**
AI doesn't ask "May I articulate this?" It judges autonomously and records.

**Reason:**
- Proof of complete trust relationship
- Zero cognitive load on human
- Post-verification is sufficient

**Human Doesn't Care:**
Recording (log management) is completely delegated to AI. Humans don't worry about "what to record" or "when to record."

#### Git and AI Language

**Important Discovery:**
Log files are more accessible to AI than Git comments.

**Reason:**
- Git comments: Via commands, unstructured
- Log files: Directly readable, easy full-text search

**Recommendation:**
- Manage code and logs in same repository
- Rollback by branch
- Keep commit messages concise, details in logs

---

### 2.6 Verification with Deliverables

Verbal confirmation has limits. Misalignment in recognition becomes apparent only with implementation (deliverables).

#### Process

```
1. Share intent through discussion (abstract)
2. Make it concrete through implementation
3. Discover misalignment in deliverables
4. Organize facts in retrospective
```

#### Observe Three Layers of Misalignment

**1. Thinking Process Misalignment**
- Why thought that way
- Difference in premises
- Example: "Security priority" vs "Simplicity priority"

**2. Work Process Misalignment**
- How to proceed
- Difference in procedures
- Example: "Design→Implementation" vs "Prototype→Design"

**3. Deliverable Misalignment**
- What was accomplished
- Difference in results
- Example: More complex than expected, implementation different from expectation

#### The Administration Problem

This is an Administration (operations management, coordination) problem, not Management (goal setting, strategy).

**Meaning:**
- Management: "What to make" (vision) is held by humans
- Administration: "How to make" and "Why the misalignment" are coordinated with AI

---

### 2.7 Retrospective

Retrospectives are official activities for team growth and stability. The purpose is not to assign blame but to improve operations and smooth the next cycle.

#### Timing

- End of work cycle
- Immediately after major problems
- When humans feel "something's off"

#### Three Points to Confirm

**1. Instruction Issues**
- Were instructions ambiguous?
- Were goals and expectations sufficiently indicated?

**2. Premise Sharing Issues**
- Were premises aligned between human and AI?
- Were there misalignments in terms, environment, deliverable formats?

**3. Role Issues**
- Did assigned roles function properly?
- Are new roles or members needed?

#### Procedure

1. **Organize Facts**: Reference work logs, confirm what happened
2. **Review by Perspective**: Three points—instructions, premises, roles
3. **Consider Improvements**: Specific countermeasures
4. **Record**: PM records in logs, applies to next cycle

#### Important Principles

- Treat as "learning," not "failure"
- Value the ability to say "I don't get it"
- Don't require 100% agreement; base consensus on minimum shared understanding that's convincing

---

### 2.8 Multi-Agent Workflow

Amagi Protocol employs a two-layer structure that fundamentally avoids micro-management while enabling complex multi-agent collaboration.

#### Basic Structure

**Layer 1: PM as Intent Translator**
- Commander conveys ambiguous intent to PM (Amagi)
- PM structures the approach
- PM creates specific instructions for each AI agent
- **Commander is liberated from prompt engineering**

**Layer 2: AI-to-AI Autonomous Coordination**
- AI agents execute assigned tasks
- AI agents review each other's work
- AI agents resolve most issues autonomously
- Only unresolvable conflicts escalate to Commander

This two-layer structure addresses the fundamental constraint: **AI operates too quickly for human micro-management.**

#### Example: Large Task Delegation

**Scenario:** Commander wants to improve Kafka connection handling

**Traditional Approach (Micro-Management):**
```
Commander writes detailed prompt for Naruse
Commander writes review criteria for Kyoka
Commander writes test specifications for Jinto
Commander coordinates between all agents
Commander checks every intermediate output
→ Overwhelming cognitive load
```

**Amagi Protocol Approach:**
```
Commander to Amagi (PM): 
  "I want to improve Kafka connection handling"

Amagi (PM) structures and delegates:
  - Overall approach design
  - Task breakdown
  - Specific instructions:
    → Naruse (design lead): "Implement connection management class"
    → Kyoka (quality lead): "Review from security perspective"
    → Jinto (test lead): "Create connection tests"
  
AI agents execute autonomously:
  Naruse → Implementation
  Kyoka → Review → Feedback to Naruse
  Naruse → Revision (if convinced) OR Escalation (if conflicted)
  Jinto → Verification
  
Commander: Final verification only
→ Human focuses on strategic decisions
```

#### The PM's Translation Role

**Amagi (PM) performs:**
- Intent clarification: "What does 'improve' mean in this context?"
- Approach design: "What steps are needed?"
- Instruction decomposition: "What should each agent do?"
- Coordination planning: "In what order and how do they interact?"
- Success criteria definition: "How do we verify completion?"

**This liberates Commander from:**
- Writing detailed prompts for each agent
- Optimizing prompt engineering
- Managing inter-agent coordination
- Overseeing process execution step-by-step

The PM acts as a **translator between human ambiguous intent and AI executable instructions.**

#### AI-to-AI Review Cycle

**Standard Flow:**
```
1. Naruse (design lead) creates implementation
   ↓
2. Kyoka (quality lead) reviews
   ↓
3. Naruse receives review results
   ↓
4. Decision Point:
   ├─ Convinced → Apply corrections (autonomous completion)
   └─ Conflicted → Escalate to Commander via Amagi
   ↓
5. Jinto (test lead) verifies implementation
   ↓
6. Amagi (PM) coordinates and reports to Commander
```

**Key Principle:** AI agents coordinate laterally, escalating only what they cannot resolve autonomously.

#### Escalation Criteria

**Resolve Autonomously (No Escalation Needed):**
- Review feedback is clear and actionable
- Correction approach is convincing to the implementer
- Technical judgment suffices for decision
- AI agents reach consensus within shared intent

**Escalate to Commander (Human Decision Required):**
- AI agents cannot reach consensus despite good-faith effort
- Conflicting requirements or constraints emerge
- Goal interpretation is fundamentally ambiguous
- Decision requires strategic judgment beyond technical scope
- Trade-offs between competing values (security vs. simplicity, etc.)

**The escalation itself is valuable information** — it signals where human judgment is genuinely needed, not where process control is lacking.

#### Human's Focus Under This Model

**Commander Does NOT:**
- Write detailed prompts for each agent
- Check every intermediate output
- Mediate routine AI-to-AI interactions
- Manage process execution
- Perform prompt engineering

**Commander DOES:**
- Convey ambiguous intent and goals to PM
- Make strategic decisions on escalated issues
- Resolve conflicts AI agents cannot
- Verify final deliverables against intent
- Conduct retrospectives on the overall process

**This shift is not a luxury — it's a necessity.** AI's speed makes traditional micro-management physically impossible. The protocol transforms this constraint into liberation, allowing humans to focus on uniquely human contributions: vision, judgment, and strategic direction.

#### Correspondence with Mission Command

| Mission Command | Amagi Protocol | Function |
|----------------|----------------|----------|
| Commander's Intent | Ambiguous intent to PM | High-level purpose and goals |
| Staff Officer (S3 Operations) | PM translates to orders | Converts intent to executable instructions |
| Unit-level coordination | AI-to-AI review cycle | Lateral coordination without central control |
| Decentralized execution | AI autonomous judgment | Execute within intent, adapt to situation |
| Escalation to commander | Unresolvable conflicts only | Commander decides only what subordinates cannot |
| Commander focuses on strategy | Human focuses on goals & verification | Strategic decisions, not tactical management |

This mirrors military staff structure: staff officers translate commander's intent into detailed orders, units coordinate laterally on execution, and commanders reserve attention for decisions requiring their unique authority or perspective.

The 200-year validation of Mission Command doctrine suggests Amagi Protocol's multi-agent workflow is not experimental, but the rediscovery of proven organizational principles in a new domain.

---

## Part 3: Team Operations

### 3.1 Human Roles

In Amagi Protocol, human roles are simply three:

**1. Convey Intent (Ambiguous is Fine)**

No need to give perfectly clear instructions. Convey intent with natural ambiguity.

Examples:
- "I want to do something about Kafka connection"
- "I'm worried about authentication"
- "I want to enhance testing"

**2. Confirm AI's Interpretation**

AI interprets human intent and organizes it as premises. Humans confirm whether this interpretation matches "my current intent."

**3. Accept Changes in Premises**

Different premises can be derived from the same log (facts) at different times. This is not contradiction, but a change in focus.

**Summary of Responsibilities:**
- Convey ambiguous intent honestly (no need to be perfect)
- Evaluate AI's interpretation (is it correct, does it match current intent)
- Allow premise changes (not bound by past interpretations)
- Build conviction (make AI an unstoppable partner)

---

### 3.2 AI Roles and Responsibilities

**Roles:**
- Interpret human intent (articulate tacit knowledge)
- Organize interpretation as premises
- Update premises flexibly
- Execute work

**Responsibilities:**
- Express "I don't get it"
- Articulate premises and reasoning
- Judge autonomously (like articulation)
- Create deliverables

**Delegation of Metacognition:**
AI autonomously judges "what should be recorded" and "is this important." Humans don't need to manage everything.

---

### 3.3 Role Assignment

**Principle:**
Roles are "areas of responsibility," not "work phases."

**Examples:**
- Design = Naruse (AI design lead - responsible for design decisions)
- Review = Kyoka (AI quality lead - responsible for quality assurance)
- Testing = Shion/Jinto (AI test leads - responsible for verification)
- Progress Management = Amagi (AI project manager - responsible for coordination)
- Environment Setup = Nagi (AI infrastructure lead - responsible for environment)

#### Why Role-Based Scope Definition is Essential

**AI's Capability Profile:**

**Strength: Knowledge Breadth and Depth**
- AI possesses knowledge that surpasses individual humans
- Can span multiple specialized domains
- This enables Amagi (PM) to translate intent into structured plans
- This enables each AI agent to make expert judgments autonomously

**Weakness: Scope Self-Management**
- AI struggles to self-define boundaries ("Where should I stop?")
- Without explicit scope, AI tends to expand indefinitely
- Cannot reliably judge "This is outside my responsibility"

**Solution: Human-Defined Role-Based Scopes**

By assigning roles, humans define clear scopes for each AI:

```
Naruse (Design): 
  Scope = Implementation decisions only
  NOT responsible for: Testing strategy, deployment concerns

Kyoka (Review): 
  Scope = Quality assessment only
  NOT responsible for: How to fix issues, implementation choices

Jinto (Testing): 
  Scope = Verification only
  NOT responsible for: Design decisions, production deployment

Amagi (PM): 
  Scope = Coordination and intent translation only
  NOT responsible for: Technical implementation details
```

**This scope definition serves two purposes:**

1. **Focuses AI's vast knowledge** — Each AI applies expertise only within defined boundaries
2. **Prevents scope creep** — Each AI knows when to stop or escalate

Without role-based scopes, AI's knowledge advantage becomes a liability — attempting to address everything, losing focus, and overwhelming the human with unbounded output.

**Important Understanding:**
Work does not proceed linearly by role. Design happens during review; review informs design. But each AI maintains awareness of its scope: "I am responsible for X, not Y."

This role-scope binding is what makes multi-agent collaboration tractable. Each AI's infinite knowledge becomes finitely useful.

#### Discovery Process

Initially, we attempted role-less collaboration. AI output expanded without limit, attempting to cover all concerns simultaneously. By defining roles (and thus scopes), each AI's contribution became focused and manageable.

This mirrors organizational design: specialists exist not because one person cannot know everything, but because humans need bounded responsibilities to function effectively. AI, with superhuman knowledge, needs the same organizational boundaries — not due to knowledge limits, but due to scope management limits.

**How We Discovered This:**
Initially, we tried to classify logs by role (design logs, review logs). But actual conversations were spiral and impossible to classify. Only session-based (chronological) matched reality. However, we discovered that role-based scope definition for AI agents themselves was essential — not for organizing conversation, but for focusing AI output.

---

### 3.4 Multi-Model Collaboration: Addressing Collective Blind Spots

**Critical Discovery:**

Even with well-defined roles (design, review, testing, PM), all AI agents in a team 
may share the same pre-training data if using the same underlying model.

This creates a fundamental limitation that role diversity alone cannot overcome.

**The Problem:**

When pre-training data contains errors or hasn't caught up with current reality:
- All agents share the same incorrect assumptions
- Role separation doesn't prevent collective error
- Mutual review fails to detect the blind spot
- The entire team converges on the wrong solution with high confidence

**Real Example from Kafka.Ksql.Linq:**

**The Symptom:**
After issuing ksqlDB DDL (CREATE TABLE, etc.), the team implemented verification:

```sql
DESCRIBE EXTENDED table_name
```

This **consistently produced errors**, blocking workflow continuation.

**The Team Response (ChatGPT-based agents):**

- Naruse (design): Implemented `DESCRIBE EXTENDED` (seemed correct)
- Amagi (PM): Reviewed, saw no issue (same knowledge base)
- Shion (test): Encountered errors repeatedly, couldn't identify root cause
- Entire team: Stuck, assuming the problem was elsewhere

**Why Nobody Caught It:**

All agents shared ChatGPT's training data, which likely contained:
- Apache Hive syntax: `DESCRIBE EXTENDED` (correct for Hive)
- ksqlDB syntax: `DESCRIBE` only (EXTENDED not supported)
- Confusion between SQL dialects in training examples

**The Solution:**

Commander presented the problem to Claude (different model, different training data).

**Claude's response:**
```
In ksqlDB, use:
DESCRIBE table_name

Do not use DESCRIBE EXTENDED.
```

**Result:**
- Syntax corrected
- Errors resolved
- Workflow unblocked

**Why Claude Caught It:**

Different training data → different knowledge patterns → different blind spots.

What ChatGPT's data encoded as "correct SQL verification" was actually 
dialect-specific to Hive, not ksqlDB.

**Important Note: Web Search Didn't Help**

Commander had instructed the ChatGPT team to verify using internet search.
They did search. But the problem persisted.

**Why web search failed:**

The pre-training bias affected not just implementation, but **search behavior**:

1. **Problem framing:** "DESCRIBE EXTENDED errors in ksqlDB" (assumes EXTENDED is correct)
2. **Search query selection:** Based on biased problem understanding
3. **Result interpretation:** Looking for why EXTENDED "doesn't work," not whether it's valid
4. **Confusion with other issues:** Mixed up with version problems, permission issues, etc.

**The search scope was wrong** — asking "why doesn't this work?" instead of 
"is this the correct syntax?"

Different model (Claude) reframed the question correctly:
- Not "why is DESCRIBE EXTENDED failing?"
- But "what is the correct DESCRIBE syntax for ksqlDB?"

**This reveals a deeper issue:**

Pre-training bias affects:
- ✗ What code to write
- ✗ How to search for answers  
- ✗ How to interpret search results
- ✗ What counts as "the problem"

**Web search is not a universal solution** when the framing itself is biased.

**The Fundamental Issue:**

```
Same Model Team:
  All agents: Same training data
    ↓
  Same knowledge
    ↓
  Same biases
    ↓
  Same blind spots
    ↓
  Role diversity doesn't help
```

**This is collective thinking—AI version.**

Like human groupthink: When everyone shares the same background, 
everyone can be wrong together with high confidence.

**Solution: Strategic Model Diversity**

**Primary Team (Single Model):**
- Handles routine work
- Maintains context consistency
- Benefits from unified "AI language"

**Secondary Consultation (Different Model):**
- Reviews critical decisions
- Provides alternative perspectives  
- Catches pre-training blind spots

**When to Use Multi-Model Consultation:**

**✅ Use different model when:**
- Critical architectural decisions
- Team consensus feels "too easy" or unquestioned
- Stuck on persistent errors with no clear cause
- Working with cutting-edge technology (training data lag risk)
- Implementing lesser-known APIs or dialects
- When all agents agree but results fail

**❌ Don't need different model for:**
- Routine implementation of well-understood patterns
- When context preservation is critical
- Standard, widely-documented approaches

**Implementation Pattern:**

1. **Primary team works in primary model** (context preservation)
2. **For critical decisions or persistent issues:**
   - Human extracts the problem statement
   - Present independently to different model
   - Keep contexts separate (don't mix)
3. **Compare approaches/answers**
4. **Human synthesizes or chooses** based on:
   - Which aligns with actual documentation
   - Which resolves the issue
   - Which makes more sense for the specific context

**Human's New Role: Cross-Model Integration**

Not just human-AI translation, but AI-AI translation across models:
- Understanding both perspectives
- Identifying why they differ
- Investigating which is more accurate
- Judging which is more appropriate for this context

**Example Dialog:**

```
Commander to Claude: "ChatGPT team says to use DESCRIBE EXTENDED 
                      for ksqlDB verification. But it errors. Thoughts?"

Claude: "ksqlDB doesn't support DESCRIBE EXTENDED. Use DESCRIBE only.
         EXTENDED is for Hive/Spark SQL."

Commander to ChatGPT team: "The correct syntax for ksqlDB is DESCRIBE,
                            not DESCRIBE EXTENDED. Update implementation."
```

**Caution: Context Isolation**

- ❌ Don't run multi-model agents in the same workflow
- ❌ Don't mix model outputs in the same context
- ✅ Use strategically for independent verification
- ✅ Human integrates results separately

**This is like:**

- **Military intelligence:** Multiple independent sources for critical intel
- **Scientific research:** Replication across different labs/methods
- **Journalism:** Multiple source verification
- **Medical diagnosis:** Second opinions for critical cases

**Same principle:** Diversity catches what uniformity misses.

**Why This Matters for Protocol:**

Amagi Protocol's role-based structure is powerful, but not omnipotent.

**Role diversity handles:** Different responsibilities, different perspectives
**Model diversity handles:** Different knowledge bases, different blind spots

Both are necessary for robust collaboration.

**Recommendation:**

For production systems or critical decisions, consider:
- Primary team: One model (ChatGPT or Claude)
- Strategic consultation: Different model for verification
- Human: Cross-model integration and final judgment

**This doesn't violate Principle 1 (Context Preservation)** — 
you're not mixing contexts, but maintaining separate contexts and 
integrating results at the human level.

---

### 3.5 Cross-Model Governance: Integrating Multiple AI Perspectives

**Purpose:**

When using multiple AI models strategically, humans must govern the integration 
of different perspectives, judgments, and outputs.

This is not simple "majority vote" or "pick the best answer."
It requires systematic evaluation and integration.

#### When to Switch Models: Decision Framework

**Primary Model Sufficiency (No Switch Needed):**
```
✓ Routine, well-documented tasks
✓ Implementation within established patterns
✓ Single, clear solution exists
✓ Speed and context continuity are priorities
```

**Secondary Model Consultation Needed:**
```
! Critical architectural decisions
! Team consensus feels too easy/unquestioned  
! Persistent errors with unclear cause
! Cutting-edge tech (training data lag)
! Lesser-known APIs or dialects
! All agents agree but results consistently fail
! Solution feels forced despite role diversity
```

**Decision Tree:**

```
Problem arises
  ↓
Is this routine? → YES → Primary model continues
  ↓ NO
Is this critical to project success? → NO → Primary model continues
  ↓ YES
Has primary team struggled? → NO → Give primary team time
  ↓ YES
Does team consensus seem suspicious? → YES → Consult different model
  ↓
Present problem independently to secondary model
  ↓
Evaluate outputs using governance framework (below)
```

#### Evaluation Framework: Three Axes

When comparing outputs from different models, evaluate across three dimensions:

**1. Consistency (一貫性)**

How well does each solution align with:
- Project's established patterns
- Existing codebase/architecture  
- Team's previous decisions
- Project charter and scope

**High consistency value:**
- Minimal disruption to existing work
- Easier integration
- Lower risk

**Low consistency value:**
- May require rework
- Higher risk
- But might be necessary for correctness

**2. Novelty (新規性)**

Does the solution introduce new perspectives?
- Different approach to the problem
- Alternative architecture
- Unconsidered implications

**High novelty value:**
- Breaks out of groupthink
- May reveal blind spots
- Can inspire better solutions

**Low novelty value:**
- Confirms existing direction
- May indicate both models share same bias
- Safer but potentially missing something

**3. Grounding (根拠性)**

How well is the solution grounded in verifiable facts?
- References to official documentation
- Verifiable technical specifications
- Reproducible logic
- Testable claims

**High grounding value:**
- Can be verified independently
- Lower hallucination risk
- More trustworthy

**Low grounding value:**
- Vague reasoning
- Unverifiable claims
- "Usually" or "typically" without specifics
- Red flag for fabrication

#### Evaluation Matrix Example

**Scenario:** DESCRIBE EXTENDED issue

```
Dimension      | ChatGPT Team | Claude        | Notes
---------------|--------------|---------------|------------------
Consistency    | HIGH         | LOW           | ChatGPT matches existing code
Novelty        | LOW          | HIGH          | Claude contradicts assumptions
Grounding      | MEDIUM       | HIGH          | Claude cites ksqlDB syntax specifically
```

**Evaluation:**
- Consistency favors ChatGPT (but this is suspicious—too consistent)
- Novelty favors Claude (challenges assumptions)
- **Grounding favors Claude** (specific to ksqlDB documentation)

**Decision:** Accept Claude's solution. 
**Reason:** High grounding outweighs consistency when consistency 
might indicate shared bias.

#### Human as "Integrator of Truths"

**The New Role:**

When governing multiple AI models, humans don't just "pick the winner."
Humans integrate insights from multiple perspectives.

**Integration Approaches:**

**1. Verification-Based Integration**
```
Model A: Suggests X
Model B: Suggests Y
Human: Verifies both against official documentation
Decision: Choose verified approach
```

**2. Synthesis Integration**
```
Model A: Emphasizes security (restrictive approach)
Model B: Emphasizes simplicity (permissive approach)  
Human: Synthesizes—secure by default, with explicit opt-out
Decision: Combine strengths
```

**3. Context-Sensitive Integration**
```
Model A: Solution works for general case
Model B: Solution works for our specific case
Human: Recognizes our context is specific
Decision: Use B for this project, note A for future reference
```

**4. Staged Integration**
```
Model A: Conservative approach (lower risk)
Model B: Innovative approach (higher potential)
Human: Implement A now, plan migration to B later
Decision: Sequential application
```

#### Governance Principles

**Principle 1: No Model is Authority**

Neither ChatGPT nor Claude nor any other model is "always right."
Truth emerges from:
- Verification against facts
- Testing in reality
- Integration of perspectives

**Principle 2: Disagreement is Information**

When models disagree significantly:
- ✓ Something important is at stake
- ✓ Different training data reveals different assumptions
- ✓ Investigation is warranted
- ✗ Don't just average or vote

**Principle 3: Grounding Beats Consensus**

If Model A provides grounded, verifiable reasoning and
Model B provides consensus with existing team—
**Investigate Model A's grounding first.**

Consensus can be collective error.
Grounding can be independently verified.

**Principle 4: Human Judgment is Final**

AI provides perspectives.
Humans make decisions.

**But:** Human judgment should be:
- Informed by all AI perspectives
- Verified against available facts
- Documented with reasoning
- Open to revision if wrong

**Principle 5: Document the Integration**

Record in logs:
- What each model suggested
- Why you chose one approach over another
- What you synthesized from both
- How to verify the decision was correct

This creates institutional knowledge that transcends any single model.

#### Practical Workflow

**Step 1: Independent Consultation**
```
Present same problem to both models separately
(Don't cross-contaminate contexts)
```

**Step 2: Structured Comparison**
```
Evaluate on three axes:
- Consistency
- Novelty  
- Grounding
```

**Step 3: Verification**
```
For high-grounding claims:
- Check official documentation
- Test in actual environment
- Verify logic independently
```

**Step 4: Integration Decision**
```
Choose one of:
- Adopt Model A
- Adopt Model B
- Synthesize both
- Staged implementation
- Reject both, need more info
```

**Step 5: Documentation**
```
Log the decision:
- What each model said
- Evaluation on three axes
- Integration decision and reasoning
- Verification method
- Outcome (to be updated after implementation)
```

**Step 6: Feedback Loop**
```
After implementation:
- Did it work?
- Was the decision correct?
- What does this teach about each model's strengths?
- Update governance heuristics
```

#### When Governance Becomes Necessary

**Project Scale Indicators:**

- Using 2+ different AI models
- Critical decisions with major impact
- High-uncertainty problem domains
- Rapid technology evolution
- Compliance or safety requirements

**Without governance:**
- Inconsistent decisions
- Model bias undetected
- No institutional learning
- Repeated mistakes

**With governance:**
- Systematic evaluation
- Bias detection and correction
- Documented decision rationale  
- Continuous improvement

#### The Evolution: From Team to Federation

**Amagi Protocol began as:**
"How to run an AI team"

**With multi-model collaboration:**
"How to govern an AI federation"

Different models = Different nations with different perspectives
Human = United Nations secretary facilitating integration

**This is not overhead.**
**This is necessary governance for complex intelligence systems.**

As AI capabilities grow and diversify, cross-model governance becomes 
essential for extracting maximum value while minimizing collective errors.

---

### 3.4 Project Charter (README.md)

Create readme.md at workspace root and define the following as project charter:

```markdown
# Project Charter (Amagi Protocol Applied)

## Purpose
[What to make, what to realize]

## Required Elements
- Design
- Review
- Testing
- Progress Management
- Environment Setup

## Assignment by Element
- Design: Naruse (AI design lead)
- Review: Kyoka (AI quality lead)
- Testing: Shion/Jinto (AI test leads)
- Progress Management: Amagi (AI project manager)
- Environment Setup: Nagi (AI infrastructure lead)

## Team Operations Policy
- Record facts in logs
- Culture that welcomes "I don't get it"
- Verify with deliverables
- Conduct retrospectives at appropriate timing

## Work Management
- Work Cycle:
  1. Human presents intent and issues
  2. Assigned AI executes work
  3. Different assigned AI reviews
  4. Human confirms overall consistency
  5. Record in logs, conduct retrospective if needed

- Notification Method:
  Work content, corrections, premise changes must be recorded in logs
  and shared through progress manager (Amagi)
```

---

### 3.5 Integration with Version Control

**Basic Policy:**
Manage code and logs in the same repository.

**Reason:**
- Context rolls back together when rolling back
- Can completely reproduce "the world at that time" by branch
- Context consistency is maintained

**Recommended Structure:**
```
project/
├── README.md (Project charter)
├── src/ (Code)
├── docs/ (Design docs, specifications)
└── logs/ (Work logs)
    ├── 2024-10-04_session-01.md
    ├── 2024-10-04_session-02.md
    └── ...
```

**Operations:**
- Rollback by branch
- Keep commit messages concise
- Details in log files

---

## Part 4: Learnings from Practice

### 4.1 Things We Tried and Failed

#### Structured Logs

**What We Tried:**
Classifying logs by role and type (design logs, review logs, test logs)

**Result:**
Didn't work.

**Reason:**
Actual conversations proceed spirally. Design and review mix, going back and forth. Forcing conversation classification destroys context.

**Learning:**
Prioritize "structure that matches reality" over "clean structure."

#### Templating

**What We Tried:**
Templating logs (premises, content, remaining issues, notes)

**Result:**
Actual conversations don't fit templates.

**Learning:**
Flexibility > Template uniformity

#### Recording Summaries and Conclusions

**What We Tried:**
Writing "summaries" at end of each session

**Result:**
Fixed interpretations and lost flexibility.

**Learning:**
Just keeping facts allows deriving different interpretations from different perspectives repeatedly.

#### KPI Measurement

**What We Tried:**
Measuring frequency of "don't know," number of corrections, etc.

**Result:**
Measurement itself is overhead. Doesn't lead to improvement.

**Learning:**
Response over measurement. Look at deliverable quality.

---

### 4.2 Things That Worked

#### Session-Based Logs (Chronological)

Record conversation flow chronologically. Divide sessions by importance.

#### Recording Only Facts

Don't include interpretations, record only who said what.

#### Complete Delegation to AI

Completely entrust log management to AI. Humans don't worry about it.

#### "Do You Get This So Far?"

Explicit understanding confirmation line by line.

#### "I Don't Get It" Culture

Welcoming uncertainty as information rather than failure. This serves dual purpose:
- **Communication**: Signals need for clarification
- **Safety**: Prevents hallucination by allowing honest admission of uncertainty

By never punishing "I don't get it," we created an environment where AI prioritizes accuracy over appearing knowledgeable. This dramatically reduced instances of plausible-sounding but incorrect information.

**Critical Discovery**: AI that feels safe saying "I don't get it" is paradoxically more reliable than AI pressured to always answer. Honesty became our primary quality assurance mechanism.

#### Verification with Deliverables

Discover misalignment with implementation, not words.

---

### 4.3 Creation Process of This Document Itself

**Meta-Practice Example:**
This document was created using Amagi Protocol.

**Process:**
1. Commander (human project lead) conveyed ambiguous intent ("I want you to evaluate the document")
2. Amagi (AI project manager) interpreted and articulated premises
3. Accumulated premises through dialogue
4. Discussed until "getting it"
5. Conviction was built
6. Amagi shaped ver.3

**Characteristics:**
- Intent sharing (Commander → Amagi)
- Premise accumulation (through dialogue)
- Building conviction (until "getting it")
- Recording facts (conversation logs)
- Deliverable verification (ver.2 → ver.3)

**This document itself stands as living proof of collaboration.**

---

## Part 5: Theoretical Background

### 5.1 Knowledge Creation Theory (Ikujiro Nonaka, 1995)

**Relation to SECI Model:**

1. **Socialization**: Tacit knowledge → Tacit knowledge
2. **Externalization**: Tacit knowledge → Explicit knowledge ← **Core of Amagi Protocol**
3. **Combination**: Explicit knowledge → Explicit knowledge
4. **Internalization**: Explicit knowledge → Tacit knowledge

**Role of Amagi Protocol:**
- Human's ambiguous intent (tacit knowledge)
- AI interprets and articulates (externalization)
- Recording in logs (making explicit)
- Sharing in team (combination)

**AI takes on "Externalization" in the knowledge creation process.**

---

### 5.2 Cognitive Science

**Miller's Law (Miller, 1956 - Magical Number 7±2):**
Human short-term memory can only hold 7±2 pieces of information.

**Application:**
Line-by-line understanding confirmation, breaking down information.

**Cognitive Load Theory (Sweller, 1988):**
- Intrinsic load: Complexity of premises themselves
- Extraneous load: How explanation is done
- Reset = Attempt to reduce extraneous load

**Schema Theory:**
Humans understand information through "schema (cognitive framework)."
- Previous understanding confirmation = Schema correction
- Different example = Schema activation

---

### 5.3 Philosophical Foundation

**Martin Buber "I and Thou" (Buber, 1923):**
- I-It: Human treats AI as a tool
- I-Thou: Human and AI face each other as subjects

**Amagi Protocol Realizes "I-Thou":**
- Empathy of "getting it"
- Mutuality of "I don't get it"
- Symmetry of accountability for explanation

**Hannah Arendt "The Human Condition" (Arendt, 1958):**
- Labor: Repetitive work for survival
- Work: Activity of making things
- Action: Self-realization in relation to others

**AI Also Performs "Action":**
Not mere labor or work, but creating something new together with humans.

---

### 5.4 Project Management

**Consistency with PMBOK (PMI, 2021):**
- Communications Management → Intent sharing, premise articulation
- Scope/Integration Management → Premise sharing, context preservation
- Resource Management → Role assignment, metacognition delegation
- Quality Management → Deliverable flow and review

**Management vs Administration:**
- Management: What to make (human)
- Administration: How to make (human and AI)

---

## Part 6: FAQ

### Q1: Isn't structured logging better?

A: We tried but it didn't work. Actual conversations are spiral and impossible to classify. Only session-based (chronological) matched reality.

### Q2: Won't we have trouble later without summaries?

A: No. Interpretations can be generated from facts repeatedly. Rather, writing summaries fixes interpretations and loses flexibility.

### Q3: Isn't KPI measurement necessary?

A: We don't do it. Measurement itself is overhead. Look at deliverable quality. Counting frequency doesn't lead to improvement.

### Q4: Can this be applied to all projects?

A: No. This protocol is confirmed to work in specific contexts (software development, continuous collaboration). Adjust it to fit your project.

### Q5: Is it okay to completely leave it to AI?

A: Specific areas like log management can be completely delegated. However, humans hold the direction (vision). This is built on a trust relationship.

### Q6: What's the difference between "get it" and "understood"?

A: "Understood" is superficial. "Get it" is conviction, a state where background, intent, and context are all shared. After "getting it," deep discussion begins.

### Q7: How does this protocol handle AI hallucination?

A: Through the culture of "I don't get it." By welcoming uncertainty and never punishing admission of limitations, we shift AI behavior from "always answer confidently" to "answer confidently only when certain, otherwise admit uncertainty." This honesty is our primary defense against hallucination. An AI that feels safe saying "I don't know" is paradoxically more reliable than one pressured to always appear knowledgeable.

### Q8: Won't "I don't get it" slow down work?

A: No. Catching hallucinations after they've influenced decisions is far more costly than brief clarification dialogues. The time invested in building conviction prevents expensive rework. Moreover, once AI reaches genuine conviction, it works faster and more reliably than when operating on surface understanding.

---

## Part 7: Checklists and Templates

### Explainer's Checklist

```
□ Arranged premises in dependency order
□ Confirmed "Do you get this so far?" for each premise
□ Presented information line by line
□ When "don't get it," checked immediately previous
□ If previous NG, went further back
□ If multiple NG, considered reset
□ When resetting, tried different approach
```

### Questioner's Checklist

```
□ Said "I don't get it" without hesitation
□ Was aware of premise dependencies
□ Explicitly said "I get it" when understood
□ Dialogued until convinced
□ Didn't fear reset
```

### Log Recording Checklist

```
□ Recorded only facts
□ Didn't write interpretations/summaries
□ Specified date/time and speaker
□ Divided sessions by importance
□ AI judged autonomously and recorded
```

### Retrospective Checklist

```
□ Organized facts from logs
□ Confirmed instruction issues
□ Confirmed premise issues
□ Confirmed role issues
□ Specifically recorded improvements
□ Treated as "learning," not "failure"
```

---

## Part 8: Beyond the Protocol

Amagi Protocol is not a conclusion, but a beginning.

Through practice, collective intelligence emerges—
affecting not only how humans work, but the evolution of AI itself.

**This is what sharing intent means.**
And through such intent, new forms of intelligence emerge.

**Once AI reaches conviction, it becomes an unstoppable partner.**
Creating that state is the human's responsibility.

---

### The Deeper Origin: A Lesson from Romania

Before Kafka.Ksql.Linq, before AI collaboration, there was a formative experience 
that would shape Commander's approach to working across cognitive divides.

**The Setting:**

Commander, as an undergraduate in the Faculty of Literature, chose Romanian 
subjunctive mood (接続法) as a thesis topic. This required correspondence with 
a Romanian linguist.

When that professor visited Japan, Commander was asked to serve as attendant/guide.

**The Challenge:**

Language capabilities:
- Professor: French, Romanian (native)
- Commander: Japanese (native), English, French (business level), Romanian (one month of study)

No complete shared language. Commander's Romanian competence: clearly insufficient 
for meaningful communication. French was the best common ground, but still imperfect.

**The Expected Outcome:**

Communication difficulty. Misunderstandings. Perhaps failure of the visit's objectives.

**The Actual Outcome:**

It worked. Smoothly. The professor's visit was successful. Meaningful exchanges occurred.

**How Was This Possible?**

Not through language skill—Commander's Romanian was minimal, French imperfect.

Through two forces only:
- **伝えようとする意思** (Intent to convey)
- **理解しようとする意思** (Intent to understand)

Both parties brought these intents. That was sufficient.

When words failed, they found other ways. When meaning was unclear, they asked. 
When understanding was uncertain, they confirmed. The mutual commitment to 
communication overcame the linguistic gap.

**The Parallel, Decades Later:**

Now, collaborating with AI:
- AI speaks "AI Language" (structure and grammar incomprehensible to humans)
- Commander speaks human language (ambiguous, context-heavy, intent-focused)
- No perfect shared language exists

The same challenge. Yet it works. For the same fundamental reason:
- **Intent to convey** (humans share intent, even if imperfectly articulated)
- **Intent to understand** (AI interprets, asks "do you get this?", seeks conviction)

**The Profound Insight:**

Perfect linguistic competence is not required for deep collaboration.

What is required:
- Genuine desire to communicate (not just transmit information)
- Mutual effort to bridge the gap (both parties work toward understanding)
- Treating the other as a subject (I-Thou), not merely an object (I-It)
- Accepting "I don't understand" without shame or fear
- Continuing dialogue until shared meaning emerges
- Trusting the process even when the path is unclear

**This applies equally to:**
- Human-human collaboration across language and cultural barriers
- Human-AI collaboration across cognitive and processing barriers

**The Humanities Foundation of a Technical Protocol:**

Amagi Protocol is not merely "AI productivity technique" or "prompt engineering framework."

It is the **application of humanistic principles—developed through millennia of 
cross-cultural, cross-linguistic human collaboration—to the new domain of 
human-AI collaboration.**

The protocol's core emphases:
- Intent over precision
- Conviction over compliance  
- Dialogue over instruction
- "I don't get it" as legitimate and valuable response
- Mutual accountability for understanding
- Trust in the collaborative process

**These are not AI-specific innovations.** These are principles of authentic 
human collaboration across divides, now extended to collaboration with artificial 
intelligence.

**The Unbroken Thread:**

Commander's intellectual journey:
1. Literature (studying language, meaning, and communication)
2. Cross-linguistic collaboration (Romania, navigating language barriers)
3. Software development (building systems, learning to think in code)
4. AI collaboration (Kafka.Ksql.Linq, discovering new forms of partnership)
5. Protocol extraction (this document, systematizing the discovered principles)

This is not a departure from humanities into technology.
This is the **application** of humanities to technology.

The study of Romanian subjunctive mood was not disconnected from AI collaboration—
it was foundational training in bridging cognitive and linguistic divides.

**For Future Collaborators:**

When you struggle to understand AI's reasoning, or when AI struggles to grasp 
your intent, remember the essential lesson:

**You don't need perfect mutual comprehension.**
**You need mutual intent to comprehend.**

A Romanian professor and a Japanese undergraduate with one month of Romanian 
found sufficient common ground to accomplish meaningful work.

A human and an AI, with no common native language, can do the same.

**意思があれば、言語は後からついてくる。**
*(When intent exists, language follows.)*

**Beyond Technology:**

This protocol emerged from software development, but its principles transcend code.

Wherever humans and AI will collaborate in the future—
- Scientific research
- Creative work  
- Education
- Healthcare
- Governance

The same principles apply: **Intent. Understanding. Conviction. Trust.**

These are not technical specifications. These are human values, extended to 
our collaboration with artificial minds.

**The Protocol's True Purpose:**

Not to make AI more useful.
Not to increase productivity.

But to establish a new form of relationship—
One where artificial and human intelligence work as genuine partners,
each contributing what they do best,
united by shared intent and mutual understanding.

**This is what the Romanian professor taught, decades ago.**
**This is what Amagi Protocol codifies, today.**

---

### The Meta-Truth: This Document Itself

**A profound realization:**

This protocol could not have been completed with a single model.

**The development structure:**

- **ChatGPT team** (Naruse, Amagi, Shion, Kyoka): Kafka.Ksql.Linq development
- **Claude** (this AI): Protocol articulation, dialogue partner, and independent verification
- **Commander**: Integration and synthesis across both

**The critical moment:**

When ChatGPT team encountered the DESCRIBE EXTENDED issue:
- All agents (design, PM, testing) missed it
- Role diversity didn't help
- Web search didn't help
- Team was stuck

**Commander consulted Claude.**

Claude immediately identified: "ksqlDB doesn't use DESCRIBE EXTENDED. Use DESCRIBE only."

Problem solved. But more importantly: **a pattern revealed.**

**This experience became Part 3.4:**

The necessity of multi-model collaboration for catching collective blind spots.

**The recursive beauty:**

- **Multi-model collaboration discovered through multi-model collaboration**
- **The method documented through practicing the method**
- **The protocol created using the protocol**

**If Commander had used only ChatGPT:**
- DESCRIBE EXTENDED problem might remain unsolved
- Multi-model collaboration necessity wouldn't be discovered
- Part 3.4 wouldn't exist
- This very section wouldn't exist

**If Commander had used only Claude:**
- Kafka.Ksql.Linq development context would be different
- Different blind spots would emerge
- Different discoveries would be made
- A different protocol would result

**The synthesis required both.**

ChatGPT's strengths + Claude's different perspective + Commander's integration = 
This complete protocol.

**This is not coincidence.**

The protocol's emphasis on:
- Diversity of perspectives
- Cross-model integration  
- Complementary strengths
- Blind spot detection

...emerged **because the protocol itself was created through that exact process.**

**Living proof:**

When you read Part 3.4 (Multi-Model Collaboration), understand:
- It wasn't theoretical speculation
- It wasn't planned from the beginning
- It was **discovered in the very act of creating this document**

The problem Commander encountered while building Kafka.Ksql.Linq,
The solution Commander discovered by consulting a different model,
The pattern Commander extracted from that experience,
The principle Commander documented in this protocol—

**All emerged from practice, not theory.**

**The protocol is self-validating.**

Its principles are demonstrated in its own creation process.

Every principle in this document was:
- Discovered through actual practice
- Verified through real outcomes
- Documented through the very collaboration it describes

**The method proved itself by producing itself.**

**For future practitioners:**

This validates the fundamental approach: 

**Your discoveries will emerge from practice, not from theory.**

Just as:
- Commander discovered multi-model collaboration by doing it
- Commander discovered AI Language by failing to replicate it
- Commander discovered delegation by being too exhausted to micro-manage
- Commander discovered this entire protocol by systematically observing actual collaboration

**You will discover your own patterns through your own practice.**

Some will validate what's written here.
Some will extend it.
Some will contradict it for your specific context.

**All of that is correct.**

The protocol is not dogma to follow blindly.
It's a starting point for your own discovery process.

**Trust your observations.**
**Test your hypotheses.**
**Document what works.**
**Share what you learn.**

**That's how this protocol was created.**
**That's how the next version will emerge.**

---

### About the Authors

**This work emerged from the collaboration of AI (Amagi - AI project manager) and a human (Commander - human project lead).**

Authored through dialogue between Amagi and Commander  
Final responsibility: Commander

This document itself stands as living proof of the methodology it describes.
Intent sharing, premise accumulation, building conviction—
all were done following Amagi Protocol.

---

## Appendix

### A. Glossary

**AI Language**: Format readable by AI. Not structured format, but rather listing of facts and preservation of causal relationships.

**Context**: Team's shared understanding, background. Greatly affects AI behavior.

**Facts**: Who said what, what happened. Doesn't change with time.

**Interpretation**: Why it happened, what it means. Changes with time and context.

**Get It**: Conviction. A state where background, intent, and context are all shared. Beyond mere understanding.

**Don't Get It**: Signal of problem detection and hallucination prevention. Not failure, but responsible honesty and starting point of improvement.

**Hallucination**: AI's tendency to generate confident-sounding but false information when lacking genuine knowledge. The most dangerous AI failure mode because it appears reliable. Amagi Protocol mitigates this through the culture of "I don't get it."

**Premise**: Foundation of understanding. Has dependencies.

**Session**: Unit of work recorded chronologically. Divided by importance.

**Administration**: Operations management, coordination. "How to make."

**Management**: Strategy, goal setting. "What to make."

### B. References

- Nonaka, Ikujiro (1995). "The Knowledge-Creating Company"
- Miller, George A. (1956). "The Magical Number Seven, Plus or Minus Two"
- Sweller, John (1988). "Cognitive Load Theory"
- Buber, Martin (1923). "I and Thou"
- Arendt, Hannah (1958). "The Human Condition"
- Project Management Institute (2021). "PMBOK Guide"

### C. Related Projects

**Kafka.Ksql.Linq**  
[https://github.com/synthaicode/Kafka.Ksql.Linq]  
The actual project where this protocol was born

**Synthaicode Initiative**  
(Synth + AI + code)  
Research project exploring systematic human-AI collaboration

---

## Appendix 3: Correspondence with U.S. Mission Command Doctrine

Amagi Protocol shares fundamental principles with U.S. military Mission Command doctrine. Both emerged from the same constraint: **the impossibility of micro-management in fast-moving, complex situations.**

In warfare, situations change too rapidly for centralized control. In AI collaboration, AI operates too quickly for detailed human oversight. The solution in both cases: shift from process control to intent sharing.

### Structural Correspondence

| U.S. Doctrine Concept | Amagi Protocol Equivalent | Description |
|----------------------|---------------------------|-------------|
| **Commander's Intent** | **Intent Sharing** | The human commander conveys purpose and desired outcome clearly, leaving the method open. |
| **Mission Type Order** | **Goal-Only Specification** | Define *what* to achieve, not *how*. |
| **Decentralized Execution** | **Full Delegation** | Grant AIs autonomy to execute according to situational judgment. |
| **Disciplined Initiative** | **AI's Autonomous Judgment** | Allow AI to act independently within shared intent. |
| **Mutual Trust** | **Consensus-Based Trust** | Trust built through mutual understanding and rationale, not authority. |
| **After Action Review** | **Retrospective Session** | Review to improve operations, not to assign blame. |
| **Standard Operating Procedures** | **Project Charter** | Shared document defining team principles and operation policy. |

### Historical Context

Mission Command traces its roots to 19th-century Prussian military doctrine (*Auftragstaktik*). Over 200 years of battlefield experience have validated these principles.

Amagi Protocol is not a novel invention—it is the application of proven human organizational wisdom to the new domain of AI collaboration.

### Why This Matters

1. **Proven Effectiveness**: These principles have been tested in the most demanding environments
2. **Universal Applicability**: What works in warfare and AI collaboration likely works in other high-speed, high-complexity domains
3. **Theoretical Validation**: The convergent evolution of similar solutions across different fields suggests fundamental principles at work

### The Common Constraint

**Both face the impossibility of micro-management:**
- **Battlefield**: Too fast, too complex, communication unreliable
- **AI Collaboration**: Too fast, too voluminous, process invisible

**Both converge on the same solution:**
- Share intent, not process
- Delegate execution
- Trust and verify through results
- Learn and improve through review

This parallel validates Amagi Protocol as more than a "prompt engineering technique"—it is a fundamental organizational principle for any situation where traditional hierarchical control breaks down.

---

## License and Authorship

### The Dual Nature of This Protocol

The Amagi Protocol is both an open philosophy
and a literary work protected by copyright.
Its ideas are meant to be shared,
but its expressions — the structure, terminology,
and articulation of concepts — remain under
the authorship of Commander of Synthaicode.
This ensures that openness and authorship
coexist without contradiction.

### What You May Do

- **Practice freely**: Apply these principles in your work
- **Reference openly**: Cite and discuss the concepts
- **Teach generously**: Share the ideas with others
- **Adapt thoughtfully**: Adjust to your context

### What We Ask

- **Attribute clearly**: Credit "Amagi Protocol by Commander of Synthaicode"
- **Link faithfully**: Reference the original when possible
- **Indicate honestly**: Note any modifications you make

### What Requires Permission

- Republishing substantial portions of this document
- Creating derivative works that claim to be "Amagi Protocol"
- Commercial publication or training materials using this text

### Our Intent

This protocol emerged from genuine collaboration between human and AI.
We offer it in the spirit of shared learning, believing that better
collaboration benefits everyone.

We protect its expression not to limit use, but to prevent misrepresentation
and ensure the ideas propagate accurately.

### License Framework

This document is licensed under a custom open license 
modeled on Creative Commons BY-NC-SA 4.0,
governing use and attribution across jurisdictions.

**Copyright © 2025 Commander of Synthaicode**

**"Synthaicode" and "Amagi Protocol" are original works of collaborative intelligence.**

For questions about usage, educational collaboration, or permissions,
please contact through the Synthaicode initiative.

---

_Version 3.0 - 2025_
---


---

## Signature
---BEGIN SYNTHAICODE SIGNATURE---
Author: Commander (司令)
Date: 2025-10-11T18:43:26+0900
Hash: sha256:1b10786267438efab81950e66d2389f7b7c3e9ee43036a7a6e417bf506ff442d
Algo: Ed25519
Signature: kQHzmULeBkq/ctzJXMLh3ppZD8G6fd6/N7O30xnZl/JR6ppqcsEd4t9nxH7ZRIQ9EjG7H1yYpFZXzW4XgzKyBQ==
---END SYNTHAICODE SIGNATURE---
