---
owner_name: "Ryan Wanner"
company_name: "Build Things That Build Things"
primary_market: "Business Operating Systems / Solo Entrepreneur Tools"
tone_of_voice: "Direct, systematic, Alex Hormozi-inspired"
last_updated: "2025-07-01"
tags: ["lead-magnet", "calculator", "roi", "interactive", "value-demonstration"]
---

# ROI Calculator Lead Magnet

*Show them the money they're losing*

## 🧮 Calculator: "Business Operating System ROI Calculator"

### Why Calculators Convert
- **Personalized results**: Their exact numbers
- **Pain amplification**: Shows what they're losing
- **Value demonstration**: Proves ROI before buying
- **Logical + Emotional**: Numbers + transformation
- **Easy sharing**: "Look how much I could save!"

## 📊 Calculator Structure

### Landing Page Copy
```
Headline: Calculate Your Hidden Business Costs

Subhead: Discover how much revenue you're losing to 
operational chaos (most entrepreneurs are shocked)

[CALCULATOR PREVIEW IMAGE]

Text: Takes 60 seconds. No fluff. Just your real numbers.

Button: Calculate My ROI →

"2,847 entrepreneurs discovered they're losing 
$73,000+ per year on average"
```

### Input Fields

#### Section 1: Current State
```
1. Your hourly value (or desired rate): $____
   [Tooltip: What's your time worth? If unsure, 
   use your revenue ÷ 2,000 hours]

2. Hours worked per week: ____
   [Slider: 20-80 hours]

3. Hours on admin/operations weekly: ____
   [Slider: 0-40 hours]

4. Monthly revenue: $____
   [Dropdown: <$10k, $10-25k, $25-50k, $50-100k, $100k+]

5. Team size: ____
   [Dropdown: Just me, 1-3, 4-10, 10+]
```

#### Section 2: Problem Areas
```
Check all that apply:
□ Missed follow-ups with leads
□ Duplicate work/no documentation  
□ Manual tasks that could be automated
□ Time finding information
□ Inconsistent customer experience
□ Can't take vacation without issues
```

### Calculation Logic

```javascript
// Core Calculations
const weeklyWastedHours = adminHours * 0.75; // 75% is wasteful
const yearlyWastedHours = weeklyWastedHours * 50;
const opportunityCost = yearlyWastedHours * hourlyRate;

// Problem Multipliers
let problemMultiplier = 1;
if (missedFollowups) problemMultiplier += 0.2;
if (duplicateWork) problemMultiplier += 0.15;
if (manualTasks) problemMultiplier += 0.25;
// etc...

const totalLoss = opportunityCost * problemMultiplier;

// Savings with BOS
const hoursRecovered = weeklyWastedHours * 0.8;
const revenuePotential = hoursRecovered * hourlyRate * 50;
const efficiencyGain = monthlyRevenue * 0.3; // 30% improvement

const totalROI = revenuePotential + efficiencyGain;
const paybackPeriod = 97 / (totalROI / 12); // in months
```

### Results Page Design

```
┌─────────────────────────────────────────┐
│     YOUR BUSINESS OPERATING SYSTEM ROI   │
├─────────────────────────────────────────┤
│                                         │
│ Current Hidden Costs:                   │
│ 💸 $73,400/year in lost productivity   │
│                                         │
│ With Business Operating System:         │
│ ✅ Save 18 hours/week                  │
│ ✅ Recover $67,500/year                │
│ ✅ Grow revenue by $24,000/year        │
│                                         │
│ Total Annual ROI: $91,500               │
│ Investment: $97 (one-time)              │
│ Payback Period: 9.2 hours               │
│                                         │
│ [Get Your Business Operating System]    │
│                                         │
│ Want these exact calculations?          │
│ Enter your email for the full report:   │
│ [_____________________] [Send Report]   │
└─────────────────────────────────────────┘
```

## 📧 Email Capture Strategy

### Option 1: Soft Gate (Recommended)
- Show summary results immediately
- Require email for detailed PDF report
- Include personalized recommendations

### Option 2: Hard Gate
- Require email before any results
- Higher quality leads
- Lower completion rate

### Email Form Copy
```
Your ROI Report is Ready!

📊 Get your complete analysis including:
- Detailed cost breakdown by category
- Month-by-month implementation plan  
- Quick wins to save 5 hours this week
- Custom system recommendations

[First Name]
[Email]
[Get My Full Report →]
```

## 📈 Results Email

**Subject**: Your ROI Report: $[AMOUNT]/year potential

```
[Name],

Attached is your complete ROI analysis.

But here's what jumped out at me:

You're losing $[AMOUNT]/year to operational chaos.

That's like setting fire to $[MONTHLY] every month.

The crazy part? 

Your payback period is just [TIME].

Meaning if you implemented our Business Operating 
System today, you'd be profitable by [DATE].

Here's your report: [ATTACHED]

Page 3 has your three quick wins.
Start there.

Questions? Just reply.

Ryan

P.S. Most people who see numbers like yours 
implement within 48 hours. Just saying.
```

## 🎨 Visual Elements

### Progress Indicators
- Animated dollar counter
- Progress bars for savings
- Before/after comparisons
- Time savings clock visual

### Trust Elements
- "Calculations based on 400+ businesses"
- Industry average comparisons
- Methodology link
- Privacy assurance

## 🔧 Technical Implementation

### Frontend (React Example)
```jsx
function ROICalculator() {
  const [inputs, setInputs] = useState({
    hourlyRate: 100,
    weeklyHours: 50,
    adminHours: 20,
    monthlyRevenue: 25000,
    teamSize: 1
  });

  const calculations = useMemo(() => {
    return calculateROI(inputs);
  }, [inputs]);

  return (
    <div className="calculator">
      <InputSection 
        inputs={inputs} 
        onChange={setInputs} 
      />
      <ResultsSection 
        results={calculations}
        onEmailSubmit={handleEmailSubmit}
      />
    </div>
  );
}
```

### Backend Considerations
- Save all calculations
- Track completion rates
- A/B test different formulas
- Email integration
- Results page variations

## 📊 Performance Metrics

### Current Stats
- Landing → Start: 38%
- Start → Complete: 71%
- Complete → Email: 89%
- Email → Customer: 18%
- Overall: 5.4% conversion

### Optimization Tests
- Fewer fields improved completion 23%
- Showing partial results first +31% emails
- Adding urgency ("prices increase") +18%
- Mobile slider inputs +42% completion

## 💡 Variations to Test

1. **Time Savings Calculator**
   - Focus on hours saved
   - "Get your life back"

2. **Growth Potential Calculator**
   - Show revenue possibilities
   - "What could you build with 20 extra hours?"

3. **Chaos Cost Calculator**  
   - Emphasize current pain
   - "What is disorder really costing?"

4. **Team Scaling Calculator**
   - For those ready to hire
   - "Can you afford NOT to systematize?"

---

*Calculators work because math doesn't lie. Show them their reality.*