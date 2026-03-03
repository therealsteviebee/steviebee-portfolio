# 1‑Page Value Memo — Stevie Bee (Desktop Support Engineer)  
**Theme:** Retain, formalize scope, and reduce operational risk during transition

## Executive Summary
I own and operate automations that reduce support load, increase service responsiveness, and prevent workflow failure between Slack, Jira Service Management, Confluence knowledge, Azure Functions, and Microsoft 365. These systems are now embedded in day-to-day support motion and directly impact employee productivity, support capacity, and operational risk.

**Recommendation:** retain and formally scope this function through the transition to preserve continuity and maintain the velocity of automation-driven support improvements.

---

## Business Impact (estimated; refine with actual volumes)
- **Deflection + faster answers:** ~**5–12 hours/week** of support capacity reclaimed by resolving common questions in Slack via KB retrieval + LLM fallback, reducing repetitive handling.
- **Faster escalation + better ticket quality:** reduced back-and-forth on escalations by auto-threading context and standardizing intake; avoids “missing info” delays.
- **Visibility + fewer follow-ups:** public Jira comment + automation-result mirroring into Slack threads reduces “any update?” pings and context switching (est. **2–6 hours/week** saved across teams).

> Conservative model: 25 Slack support pings/day × 20% deflection × 6 minutes saved = 30 minutes/day (~2.5 hours/week) **from deflection alone**.  
> Moderate model: 40/day × 25% × 6 minutes = 60 minutes/day (~5 hours/week).

---

## Risk Reduction (why this matters in a sale / transition)
- **Continuity risk:** these workflows involve multiple external systems (Slack, Atlassian, Azure, Graph). Ownership and operational knowledge are concentrated; loss of ownership increases incident probability and MTTR.
- **Policy risk:** public-only comment mirroring prevents accidental disclosure of internal notes, reducing compliance and privacy risk.
- **Deployment discipline:** full rebuild + redeploy pipelines reduce drift and breakage from ad-hoc portal edits.

---

## Unique Ownership / Responsibilities
- Queue-driven Slack bot processing, intent routing, and thread-safe responses
- Confluence KB retrieval + LLM fallback behavior (no dead ends)
- Jira Service Management escalation + durable issue/thread correlation
- Callback endpoints posting automation outcomes back into originating Slack threads
- Public-only Jira comment mirroring; internal notes excluded by policy
- Diagnostic endpoints + operational troubleshooting patterns
- End-to-end redeploy packaging and release reliability improvements

---

## 90‑Day Transition Plan (high leverage)
**0–30 days:** document architecture + runbooks, harden monitoring/alerts, formalize ownership boundaries  
**31–60 days:** add intent analytics + deflection reporting; refine policy guardrails by channel/team  
**61–90 days:** expand automation coverage (top 10 repetitive intents), reduce ticket noise, improve onboarding docs for support engineers

---

## Retention / Role Suggestion (flexible)
- Formalize role scope as: **IT Ops Automation Engineer / Platform Automation Engineer** (non-manager track)  
- Success metrics: deflection rate, queue depth, MTTR for automation incidents, adoption across support channels  
- Compensation: align to scope; consider retention bonus with “good leaver” protections if role changes post-close
