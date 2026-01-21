# Example: Customer Support AI Project

This example shows how the Metric Mandate framework transforms a vague AI project idea into specific, measurable criteria.

## Initial Project Idea

"We want to use AI to help with customer support tickets."

## The Conversation

**User:** I want to use AI to help with customer support tickets.

**Claude:** Let's define what success looks like. Question 1: What specific number will change? "Help with tickets" isn't measurable. Are we talking about:
- Average resolution time?
- First response time?
- Customer satisfaction scores?
- Ticket volume handled per agent?

Pick ONE specific metric.

**User:** Average resolution time.

**Claude:** Good. Question 2: What is that number TODAY? I need your current baseline with a data source - not "about X hours" but actual measured data.

**User:** It's around 4-5 hours based on last quarter.

**Claude:** Close, but not specific enough. Pull the actual data. Is it 4.2 hours? 4.8 hours? The baseline needs to be precise or you won't know if you've improved. Can you check your ticket system for Q4 2024 data?

**User:** Okay, looking at Q4 2024... average resolution time was 4.2 hours across 12,000 tickets.

**Claude:** Perfect - that's a real baseline. Question 3: What's the minimum improvement that justifies the investment? If you're spending $50,000 on this implementation, what improvement makes that worthwhile? 10%? 30%? 50%?

**User:** I'd say at least 30% improvement to justify the cost.

**Claude:** Good. So you want to go from 4.2 hours to... what target?

**User:** Under 3 hours would be 30% improvement.

**Claude:** Actually, let me check that math. 30% of 4.2 hours is 1.26 hours, so 30% improvement would bring you to 2.94 hours. Is that your target? Under 3 hours?

**User:** Yes, under 3 hours.

**Claude:** Question 4: When will you measure? What's your timeline?

**User:** After 90 days in production.

**Claude:** Good - that's specific. Question 5: This is the hardest one - what result means you STOP? If after 90 days you've only achieved a 15% improvement instead of 30%, what do you do?

**User:** Hmm... I guess if we're not at least at 3.5 hours by day 60, that would be a red flag.

**Claude:** So your kill criteria is: if not below 3.5 hours by day 60, you'll reassess the approach. Correct?

**User:** Yes, exactly.

**Claude:** Perfect. Here's your complete Metric Mandate:

## Your AI Project Metric Mandate

| Question | Answer |
|----------|--------|
| **What number changes?** | Average ticket resolution time |
| **Current baseline?** | 4.2 hours (based on Q4 2024 data, 12,000 tickets) |
| **Minimum success?** | Under 3 hours (30% improvement) by day 90 |
| **Measurement timeline?** | 90 days of production use |
| **Kill criteria?** | If not below 3.5 hours by day 60, reassess approach |

## Status

✅ **Ready for implementation** - All questions answered with specific, measurable criteria

---

## Key Takeaways

Notice how the framework transformed:
- "Help with tickets" → Specific metric (resolution time)
- "Around 4-5 hours" → Precise baseline (4.2 hours from actual data)
- Vague improvement goal → Specific target (under 3 hours = 30% improvement)
- No timeline → Specific measurement point (90 days)
- No failure definition → Clear kill criteria (3.5 hours at day 60)

The final version might feel like overkill. It's not. It's the difference between a project that can succeed or fail — and therefore be learned from — versus a project that just continues indefinitely.
