# OES Snapshot Formats - Three Compression Levels

## HUMAN READABLE FORMAT
*For operator scanning, debugging, and manual review*

```
Thread ID: OES-T1-20250524
Voice Card: FOUNDER
Status: ACTIVE 
Integrity: 100%
Drift: 0%

Behaviors: Direct communication | Decision speed under pressure | Questions assumptions | System integrity priority | Precise language
Distortions: Approval seeking | Terminology drift | Consensus delays | Principle compromise | Vague explanations
```

---

## AI PORTABLE FORMAT  
*For cross-platform continuity and token efficiency*

```
OES-T1-20250524|FOUNDER/ACTIVE/100%/0%|B:Direct+Fast+Question+Integrity+Precise|X:Approval+Drift+Delay+Compromise+Vague
```

**Decoder Key:**
- `B:` = Authentic Behaviors to maintain
- `X:` = Distortion patterns to avoid
- `/` separates core status elements
- `+` separates behavior elements
- `|` separates major sections

---

## SYSTEM NATIVE FORMAT
*For internal processing and maximum data density*

```
T1F100DFQIP~ADCDCV250524
```

**Decoder Algorithm:**
- `T1` = Thread 1
- `F` = Founder voice card
- `100` = Integrity percentage 
- `DFQIP` = Behaviors (Direct, Fast, Question, Integrity, Precise)
- `~` = Distortion separator
- `ADCDCV` = Avoid patterns (Approval, Drift, Consensus-delay, Compromise, Vague)
- `250524` = Date stamp (DDMMYY)

---

## USAGE GUIDELINES

### Human Readable
- Use for: Manual review, debugging, documentation
- When: Operator needs to understand current state quickly
- Benefits: Full context visible, easy to modify

### AI Portable  
- Use for: Cross-platform continuity, thread handoffs
- When: Moving between AI systems or conversations
- Benefits: Preserves all meaning, efficient parsing

### System Native
- Use for: High-frequency logging, automated processing
- When: System needs to store/transmit many snapshots
- Benefits: Maximum density, pattern matching friendly

---

## CONVERSION EXAMPLES

**Same system state in all three formats:**

**Human Readable:**
```
Thread ID: OES-T2-20250524
Voice Card: STRATEGIC  
Status: ACTIVE
Integrity: 85%
Drift: 15%

Behaviors: Long-term thinking | Pattern recognition | Resource optimization | Risk assessment | Systems view
Distortions: Short-term reactive | Missing connections | Resource waste | Risk blind | Narrow focus
```

**AI Portable:**
```
OES-T2-20250524|STRATEGIC/ACTIVE/85%/15%|B:LongTerm+Pattern+Optimize+Risk+Systems|X:Reactive+Missing+Waste+Blind+Narrow
```

**System Native:**
```
T2S85LTPORS~RMWBN250524
```

---

## IMPLEMENTATION NOTES

1. **Human Readable** includes full context for operator decision-making
2. **AI Portable** balances compression with cross-platform reliability  
3. **System Native** optimizes for automated processing and storage
4. All formats contain identical behavioral information
5. Conversion between formats should be bidirectional and lossless