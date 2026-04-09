# Schema Analysis: What Works vs What Fails

## Weak Schema Problems

- No @id → entity is not uniquely identifiable
- No sameAs → no cross-platform identity validation
- No relationships → isolated entity
- Generic job title → low semantic clarity

Result:
- Passes validation
- Fails retrieval confidence

---

## Strong Schema Advantages

- Uses @graph → connects entities
- Includes @id → enables entity persistence
- sameAs → reinforces identity across platforms
- Entity relationships → builds context

Result:
- Higher retrieval confidence
- Stronger entity disambiguation
- Better AI interpretation

---

## Key Insight

Schema is not about:
- passing tools
- adding markup

Schema is about:
- defining identity
- reducing ambiguity
- guiding retrieval systems

---

## Critical Distinction

Validators check syntax.

AI systems evaluate:
- structure
- consistency
- authority signals

---

## Failure Case: Entity Collision

### Problem

This schema appears valid:
- Uses correct structure
- Passes validation
- Includes multiple Person entities

However, it creates **entity ambiguity**.

### Issues

- Same name used for multiple entities
- No disambiguation signals
- Conflicting roles (SEO Expert vs Digital Marketer)
- No canonical identity reference
- No connection between entities

### Result

AI systems cannot determine:
- Which entity is authoritative
- Whether these are the same person or different individuals

### Outcome

- Reduced retrieval confidence
- Possible misattribution
- Entity fragmentation

### Key Insight

Schema failure is not about syntax.

It is about:
- ambiguity
- conflict
- lack of identity resolution

### Conclusion

This schema:
- passes validators  
- fails retrieval systems  

This is the difference between:
**markup correctness vs retrieval intelligence**
