---
{"dg-publish":true,"permalink":"/prompting-vocabulary/scale-of-change/","dg-note-properties":{}}
---


Descriptors for how much adjustment intensity to apply when modifying features. Use these precision terms to control edit intensity from imperceptible to extreme.

  
## Very Subtle Adjustments (near-imperceptible, ideal for identity-preserving edits)  
  
- Minimally    
- Slightly    
- Just a touch    
- Barely    
- Imperceptibly  
  
> Example: "Slightly enlarge the eyes" → preserves natural appearance without doll-like effect.  
  
## Moderate Adjustments (noticeable but realistic)  
  
- Somewhat    
- Gently    
- Modestly    
- A bit    
- Mildly  
  
> Example: "Somewhat soften skin texture" → reduces harshness without plastic look.  
  
## Clear Adjustments (obvious change, still within plausible realism)  
  
- Noticeably    
- Clearly    
- Distinctly    
- Appreciably  
  
> Example: "Noticeably brighten the background" → creates separation without HDR overkill.  
  
## Strong Adjustments (dramatic but not extreme)  
- Significantly    
- Markedly    
- Considerably  
  
> Use sparingly—can trigger stylization if overused.  
  
## Extreme Adjustments (for artistic or non-realistic intent only)  
- Dramatically    
- Greatly    
- Extremely    
- Massively  
  
> ⚠️ Avoid in identity-critical edits (e.g., facial features)—often leads to loss of likeness.  
  
  
## Prompting Best Practices with Magnitude Modifiers  
  
- Combine with constraints:    
  “Slightly enlarge eyes, but keep iris color, shape, and eye direction unchanged.”  
- Avoid stacking intensifiers:    
  ❌ "Very significantly enlarge" → ambiguous and model-unstable.    
  ✅ "Markedly enlarge" → clear and single-scale.  
- Use negative framing for reduction:    
  “Slightly reduce nose width” > “Make nose smaller” (more precise).  
