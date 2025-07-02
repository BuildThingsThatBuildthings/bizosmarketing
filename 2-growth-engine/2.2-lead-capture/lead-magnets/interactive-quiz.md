---
owner_name: "Ryan Wanner"
company_name: "Build Things That Build Things"
primary_market: "Business Operating Systems / Solo Entrepreneur Tools"
tone_of_voice: "Direct, systematic, Alex Hormozi-inspired"
last_updated: "2025-07-01"
tags: ["lead-magnet", "quiz", "interactive", "personalization", "conversion"]
---

# Interactive Quiz Lead Magnet

*Personalized results = 3x higher conversions*

## 🎯 Quiz: "What's Your Business Chaos Score?"

### Why Quizzes Convert
- **Curiosity**: People need to know their score
- **Personalization**: Results feel custom-made
- **Micro-commitments**: Each question builds investment
- **Non-threatening**: Feels like fun, not selling
- **Shareability**: People love sharing results

## 📝 Quiz Structure

### Landing Page
```
Headline: What's Your Business Chaos Score?

Subhead: Take this 2-minute quiz to discover exactly 
what's keeping you stuck at 60-hour weeks

[IMAGE: Clean desk vs. chaotic desk]

Button: Start the Quiz →

Social Proof: "4,387 entrepreneurs discovered their 
#1 bottleneck with this quiz"
```

### Question Flow (7 Questions)

#### Q1: Business Stage
**How long have you been in business?**
- A) Less than 1 year [+3 chaos points]
- B) 1-3 years [+2 chaos points]
- C) 3-5 years [+1 chaos point]
- D) 5+ years [+0 chaos points]

#### Q2: Work Hours
**How many hours do you work per week?**
- A) 40 or less [+0 chaos points]
- B) 40-50 [+1 chaos point]
- C) 50-60 [+2 chaos points]
- D) 60+ [+3 chaos points]

#### Q3: Systems Check
**Which best describes your operations?**
- A) Everything is documented and automated [+0]
- B) Some systems, mostly manual [+1]
- C) Few systems, lots of one-offs [+2]
- D) What systems? Pure chaos [+3]

#### Q4: Team Status
**What's your team situation?**
- A) Just me doing everything [+3]
- B) A few contractors helping [+2]
- C) Small team, still very involved [+1]
- D) Team runs without me [+0]

#### Q5: Revenue Predictability
**How predictable is your revenue?**
- A) Feast or famine [+3]
- B) Some recurring, mostly project [+2]
- C) Mostly recurring, some variability [+1]
- D) Highly predictable MRR [+0]

#### Q6: Pain Point
**What's your biggest challenge right now?**
- A) Too many things need my attention [+3]
- B) Can't scale without working more [+3]
- C) Revenue plateau [+2]
- D) Team/delegation issues [+1]

#### Q7: Urgency
**When do you need this fixed?**
- A) Yesterday [+3]
- B) This quarter [+2]
- C) This year [+1]
- D) Just exploring [+0]

### Results Calculation
- **0-6 points**: Order Optimizer
- **7-12 points**: Scaling Struggler  
- **13-18 points**: Chaos Commander
- **19-21 points**: Burnout Boss

## 📊 Results Pages

### Email Capture (Before Results)
```
Almost there!

Your Business Chaos Score is ready.

Where should we send your personalized report?

[Name]
[Email]
[Button: Get My Score →]

"Plus: 3 immediate fixes for your #1 bottleneck"
```

### Results Page Template

#### For "Chaos Commander" (Most Common)
```
Your Business Chaos Score: 15/21

You're a CHAOS COMMANDER

[Progress Bar Visual: 71% Chaos]

What this means:
You're successful but drowning in your own success. 
Every growth spurt creates more chaos, and you're 
starting to wonder if this is sustainable.

The Good News:
You're exactly where most of our success stories 
started. Small changes create massive results.

Your #1 Bottleneck:
Lack of documented systems means everything 
runs through you.

Your Quick Wins:
1. Document your most repeated task TODAY
2. Create one email template you send weekly
3. Set up one automation this week

Your Success Probability:
87% of Chaos Commanders who implement systems 
reduce work hours by 40% in 90 days.

[CTA: Get Your Custom System Blueprint →]
```

## 🔧 Technical Setup

### Option 1: Simple (Typeform/Jotform)
- Use conditional logic
- Calculate score with formulas
- Redirect to results page
- Integrate with email platform

### Option 2: Advanced (Custom Build)
```javascript
// Quiz logic example
const questions = [
  {
    id: 1,
    text: "How long have you been in business?",
    options: [
      {text: "Less than 1 year", points: 3},
      {text: "1-3 years", points: 2},
      {text: "3-5 years", points: 1},
      {text: "5+ years", points: 0}
    ]
  },
  // ... more questions
];

function calculateResult(totalPoints) {
  if (totalPoints <= 6) return "Order Optimizer";
  if (totalPoints <= 12) return "Scaling Struggler";
  if (totalPoints <= 18) return "Chaos Commander";
  return "Burnout Boss";
}
```

### Option 3: No-Code (ConvertFlow/Outgrow)
- Drag-drop builder
- Built-in analytics
- A/B testing included
- Higher cost but faster

## 📧 Follow-Up Sequence

### Email 1: Immediate (With Results)
**Subject**: Your Business Chaos Score: [SCORE]/21

### Email 2: Day 1
**Subject**: Why you scored [RESULT_TYPE] (and how to fix it)

### Email 3: Day 3
**Subject**: [Name], Sarah had your exact score...

### Email 4: Day 5
**Subject**: The #1 system for [RESULT_TYPE] personalities

### Email 5: Day 7
**Subject**: Your chaos score expires tomorrow

## 📈 Performance Metrics

### Quiz Funnel Stats
- Landing → Start: 43%
- Start → Complete: 67%
- Complete → Email: 82%
- Email → Customer: 14%
- Overall: 5.2% visitor → customer

### Best Practices
- Keep to 5-10 questions max
- Show progress bar
- Use images/icons
- Make mobile-first
- Test load times

## 💡 Other Quiz Ideas

1. **"What's Your Business Scaling Style?"**
2. **"Find Your Revenue Ceiling"**
3. **"The Entrepreneur Personality Test"**
4. **"What's Blocking Your First $100K?"**
5. **"Discover Your Operations IQ"**

---

*Quizzes work because they make it about them, not you.*