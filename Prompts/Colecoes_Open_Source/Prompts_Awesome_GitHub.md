# Coleção de Prompts Open Source (GitHub)

Esta coleção foi extraída dos maiores repositórios de prompts de código aberto do GitHub, focando em prompts de *role-playing* e prompts estruturados por categorias.

## 1. Prompts de Role-Playing (Awesome ChatGPT Prompts)

Estes prompts são ideais para fazer o modelo de IA assumir uma persona ou função específica.

## 2. Prompts Estruturados por Categoria (Prompt Library)

Prompts organizados por áreas de atuação, focados em desenvolvimento, escrita e análise.

### 📁 Categoria: .github

#### ✨ Prompt: Description

```
Brief description of what this PR does and why it's needed.

## Type of Change

- [ ] New prompt
- [ ] Prompt improvement/enhancement
- [ ] Documentation update
- [ ] Bug fix
- [ ] Template addition
- [ ] Example addition
- [ ] Other (please describe):

## Category

- [ ] Development
- [ ] Writing  
- [ ] Business
- [ ] Analysis
- [ ] Creative
- [ ] Education
- [ ] Productivity
- [ ] Templates
- [ ] Examples

## Testing Checklist

- [ ] Tested prompt with at least one AI model (please specify which):
- [ ] Examples work as expected
- [ ] All required sections are included
- [ ] Follows template structure
- [ ] Markdown formatting is correct
- [ ] Links work correctly

## Quality Checklist

- [ ] Clear, actionable prompt instructions
- [ ] Realistic and helpful examples
- [ ] Appropriate tags included
- [ ] Related prompts linked where relevant
- [ ] Usage instructions are clear
- [ ] Variations provided for different use cases
- [ ] Tips section includes practical advice

## Documentation Updates

- [ ] Updated category README.md if needed
- [ ] Added to main README.md if new prompt

## AI Model Testing

Please specify which AI model(s) you tested with:

- [ ] Claude Sonnet 4
- [ ] Gemini 2.5 Pro (preview)
- [ ] GPT-4.5
- [ ] GPT-4o
- [ ] o4-mini
- [ ] Grok 3
- [ ] DeepSeek-R1
- [ ] Qwen3-235B-A22B
- [ ] Other: ___________

## Additional Notes

Add any additional context, screenshots, or notes for reviewers here.

---

By submitting this pull request, I confirm that:

- [ ] I have read and followed the [contributing guidelines](../CONTRIBUTING.md)
- [ ] This content is my original work or properly attributed
- [ ] I agree to license this contribution under the MIT License
```


### 📁 Categoria: Analysis

#### ✨ Prompt: Analysis Prompts

```
This directory contains prompts for data analysis, research, and analytical thinking tasks.

## Categories

- **Data Analysis**: Statistical analysis and data interpretation
- **Research**: Literature reviews and research synthesis
- **Trend Analysis**: Identifying patterns and trends
- **Comparative Analysis**: Comparing options, solutions, or approaches
- **Report Generation**: Creating analytical reports and summaries
- **Decision Support**: Frameworks for decision-making

## Available Prompts

- `data-interpreter.md` - Analyze and interpret datasets
- `research-synthesizer.md` - Combine multiple sources into insights
- `trend-analyzer.md` - Identify patterns and predict trends
- `comparison-matrix.md` - Compare multiple options systematically

## Analysis Best Practices

- Clearly define the analytical objective
- Specify the type of analysis needed
- Include relevant context and constraints
- Request specific output formats when needed

---
*Add your analysis prompts to this directory following the template structure.*
```

#### ✨ Prompt: Comparison Matrix

```
## Description

This prompt helps you create comprehensive comparison analyses between products, services, strategies, or options using structured frameworks to support decision-making and evaluation processes.

## Usage

Perfect for vendor selection, product evaluation, competitive analysis, strategic option assessment, feature comparison, and any situation requiring systematic comparison of multiple alternatives.

## Prompt

```markdown
You are an expert analyst specializing in comparative analysis and decision support frameworks. I need a comprehensive comparison matrix to evaluate multiple options systematically and make informed decisions.

**Comparison Project Details:**
- Items to compare: [LIST_OF_OPTIONS_TO_EVALUATE]
- Comparison purpose: [VENDOR_SELECTION/PRODUCT_CHOICE/STRATEGIC_DECISION/FEATURE_ANALYSIS]
- Decision context: [BUSINESS_CONTEXT_AND_CONSTRAINTS]
- Timeline: [DECISION_DEADLINE_AND_IMPLEMENTATION_TIMELINE]
- Budget considerations: [FINANCIAL_CONSTRAINTS_OR_LIMITS]

**Evaluation Criteria:**
- Primary factors: [MOST_IMPORTANT_CRITERIA_3_5_ITEMS]
- Secondary factors: [ADDITIONAL_CRITERIA_TO_CONSIDER]
- Deal-breakers: [MUST_HAVE_REQUIREMENTS]
- Nice-to-haves: [PREFERRED_BUT_NOT_ESSENTIAL_FEATURES]
- Weighting preferences: [RELATIVE_IMPORTANCE_OF_CRITERIA]

**Stakeholder Perspectives:**
- Key decision makers: [WHO_WILL_MAKE_FINAL_DECISION]
- User groups: [WHO_WILL_USE_THE_SOLUTION]
- Budget approvers: [FINANCIAL_DECISION_AUTHORITY]
- Implementation team: [WHO_WILL_IMPLEMENT_THE_SOLUTION]

**Evaluation Framework Needed:**
- Scoring methodology: [NUMERICAL/QUALITATIVE/MIXED_APPROACH]
- Data sources: [WHERE_TO_GET_COMPARISON_DATA]
- Validation process: [HOW_TO_VERIFY_INFORMATION]
- Documentation level: [SUMMARY/DETAILED/COMPREHENSIVE]

Please create a comprehensive comparison analysis including:

1. **Executive Summary:**
   - Recommended option with rationale
   - Key differentiators and deciding factors
   - Risk assessment and mitigation strategies
   - Implementation considerations

2. **Comparison Framework:**
   - Evaluation criteria with definitions
   - Scoring methodology and scale
   - Weighting system for criteria importance
   - Data collection and validation approach

3. **Detailed Comparison Matrix:**
   - Side-by-side feature and capability comparison
   - Quantitative scores where applicable
   - Qualitative assessments and commentary
   - Gap analysis and missing capabilities

4. **Criteria-Based Analysis:**
   - Performance evaluation against each criterion
   - Strengths and weaknesses by category
   - Relative ranking and scoring
   - Trade-off analysis between options

5. **Total Cost of Ownership (TCO):**
   - Initial costs and setup expenses
   - Ongoing operational costs
   - Hidden costs and fee structures
   - ROI and payback period analysis

6. **Risk Assessment:**
   - Implementation risks by option
   - Vendor/provider stability and viability
   - Technology and compatibility risks
   - Change management and adoption challenges

7. **Stakeholder Impact Analysis:**
   - User experience and satisfaction implications
   - Training and skill development requirements
   - Business process changes needed
   - Support and maintenance considerations

8. **Decision Framework:**
   - Weighted scoring summary
   - Scenario analysis (different priorities)
   - Sensitivity analysis for key variables
   - Final recommendation with confidence level

Ensure the analysis is objective, data-driven, and provides clear guidance for decision-making while acknowledging trade-offs and limitations.
```

## Example Input

```markdown
Items to compare: Salesforce, HubSpot, Pipedrive (CRM systems)
Comparison purpose: CRM vendor selection for growing B2B company
Decision context: 50-person sales/marketing team, need better lead management and reporting
Timeline: Decision needed by end of Q1, implementation by Q2
Budget considerations: $50K-100K annual budget

Primary factors: Ease of use, integration capabilities, reporting/analytics, scalability
Secondary factors: Mobile app quality, customer support, customization options
Deal-breakers: Must integrate with existing marketing automation, API access required
Nice-to-haves: Built-in phone system, advanced workflow automation

Key decision makers: VP Sales, VP Marketing, IT Director
User groups: Sales reps (25), marketing team (15), sales managers (5)
Implementation team: Internal IT team with external consultant support

Scoring methodology: 1-5 scale with weighted criteria
Data sources: Vendor demos, customer references, analyst reports, free trials
```

## Example Output

```markdown
# CRM System Comparison Analysis: Salesforce vs. HubSpot vs. Pipedrive

## Executive Summary

**Recommended Solution: HubSpot Sales Hub Professional**

**Rationale:**
- **Best fit for current needs**: Optimal balance of functionality and complexity for 50-person team
- **Superior integration**: Native marketing automation integration eliminates silos
- **Fastest implementation**: 6-8 week setup vs. 12-16 weeks for Salesforce
- **ROI advantage**: $73K annual cost with 18-month payback vs. 24+ months for alternatives

**Key Decision Factors:**
1. **Ease of adoption**: 65% faster user onboarding than Salesforce
2. **Unified platform**: Marketing + Sales in single system reduces complexity
3. **Growth runway**: Scales to 200+ users without platform migration

**Primary Risk**: Advanced customization limitations may require future platform change for enterprise-scale complexity

---

## Comparison Framework

### Evaluation Criteria & Weighting:

| Criteria Category        | Weight | Definition |
|-------------------------|--------|------------|
| **Ease of Use**        | 25%    | User interface, learning curve, daily workflow efficiency |
| **Integration Capabilities** | 20% | API quality, pre-built connectors, data synchronization |
| **Reporting & Analytics** | 20%   | Dashboard quality, custom reports, data visualization |
| **Scalability**        | 15%    | User capacity, feature growth, platform flexibility |
| **Total Cost of Ownership** | 10% | Licensing, implementation, ongoing maintenance costs |
| **Support & Training**  | 5%     | Documentation, customer service, learning resources |
| **Mobile Experience**   | 5%     | App functionality, offline access, user experience |

### Scoring Scale:
- **5 - Excellent**: Exceeds requirements, industry-leading capability
- **4 - Good**: Meets requirements well, strong functionality
- **3 - Adequate**: Meets basic requirements, acceptable performance
- **2 - Poor**: Below requirements, significant limitations
- **1 - Inadequate**: Fails to meet requirements, major deficiencies

---

## Detailed Comparison Matrix

### Core CRM Functionality:

| Feature Category | Salesforce | HubSpot | Pipedrive | Notes |
|-----------------|------------|---------|-----------|--------|
| **Contact Management** | 5 | 4 | 4 | Salesforce most comprehensive |
| **Lead Scoring** | 5 | 5 | 3 | HubSpot includes in standard plan |
| **Pipeline Management** | 4 | 5 | 5 | Pipedrive excels in visual workflow |
| **Email Integration** | 4 | 5 | 3 | HubSpot native, others require setup |
| **Task Automation** | 5 | 4 | 3 | Salesforce most advanced workflows |
| **Mobile App** | 4 | 4 | 5 | Pipedrive best mobile experience |

### Integration & Technical:

| Integration Type | Salesforce | HubSpot | Pipedrive | Requirements |
|------------------|------------|---------|-----------|--------------|
| **Marketing Automation** | 4 | 5 | 2 | Must integrate with current tools |
| **Email Marketing** | 3 | 5 | 3 | HubSpot native advantage |
| **Accounting Systems** | 5 | 4 | 3 | QuickBooks integration required |
| **Customer Support** | 5 | 4 | 2 | Future requirement consideration |
| **API Quality** | 5 | 4 | 3 | Developer-friendly access needed |
| **Data Import/Export** | 5 | 4 | 4 | Migration from current system |

### Analytics & Reporting:

| Report Type | Salesforce | HubSpot | Pipedrive | Business Impact |
|-------------|------------|---------|-----------|------------------|
| **Sales Forecasting** | 5 | 4 | 3 | Critical for planning |
| **Revenue Attribution** | 5 | 5 | 2 | Marketing ROI measurement |
| **Activity Reports** | 4 | 4 | 4 | Management oversight |
| **Custom Dashboards** | 5 | 4 | 3 | Executive reporting |
| **ROI Analytics** | 4 | 5 | 2 | Budget justification |

---

## Criteria-Based Analysis

### 1. Ease of Use (25% weight)

**HubSpot: Score 4.5/5**
- **Strengths**: Intuitive interface, minimal training required, excellent onboarding
- **User Feedback**: "Feels like consumer software, not enterprise tool"
- **Learning Curve**: 2-3 weeks to proficiency vs. 6-8 weeks for Salesforce

**Salesforce: Score 3.5/5**
- **Strengths**: Powerful functionality, highly configurable
- **Challenges**: Complex interface, steep learning curve, requires admin expertise
- **Training Investment**: 40+ hours per user for full proficiency

**Pipedrive: Score 4.8/5**
- **Strengths**: Visual pipeline, simple setup, sales-focused design
- **Limitations**: Less functionality may require workarounds

### 2. Integration Capabilities (20% weight)

**Salesforce: Score 4.8/5**
- **AppExchange**: 5,000+ pre-built integrations
- **API**: Most mature and comprehensive
- **Limitations**: Often requires technical expertise for setup

**HubSpot: Score 4.3/5**
- **Marketing Integration**: Native tools eliminate data silos
- **App Marketplace**: 500+ integrations, growing rapidly
- **API**: Good documentation, developer-friendly

**Pipedrive: Score 3.2/5**
- **Basic Integrations**: Core business tools covered
- **API Limitations**: More restrictive than competitors
- **Setup Complexity**: May require third-party tools (Zapier)

### 3. Reporting & Analytics (20% weight)

**Salesforce: Score 4.7/5**
- **Advanced Analytics**: Einstein AI-powered insights
- **Custom Reports**: Unlimited flexibility and complexity
- **Real-time Dashboards**: Executive-level visibility

**HubSpot: Score 4.4/5**
- **Attribution Reporting**: Excellent marketing ROI tracking
- **Sales Analytics**: Comprehensive pipeline and performance metrics
- **Ease of Use**: Report building accessible to non-technical users

**Pipedrive: Score 3.1/5**
- **Basic Reporting**: Core sales metrics covered
- **Limitations**: Limited customization, no advanced analytics
- **Visual Reports**: Good for pipeline management, limited elsewhere

---

## Total Cost of Ownership Analysis

### 3-Year TCO Comparison:

| Cost Category | Salesforce | HubSpot | Pipedrive |
|---------------|------------|---------|-----------|
| **Licensing (50 users)** | $150,000 | $108,000 | $72,000 |
| **Implementation** | $45,000 | $25,000 | $15,000 |
| **Training** | $25,000 | $12,000 | $8,000 |
| **Customization** | $30,000 | $15,000 | $5,000 |
| **Ongoing Support** | $15,000 | $8,000 | $6,000 |
| **Integration Costs** | $20,000 | $5,000 | $12,000 |
| **Total 3-Year TCO** | **$285,000** | **$173,000** | **$118,000** |

### ROI Analysis:

**Productivity Gains (Annual):**
- Sales cycle reduction: 15-25% across all platforms
- Administrative time savings: 10-20 hours/week per rep
- Lead conversion improvement: 20-35% with proper implementation

**Revenue Impact Projection:**
- Current annual revenue: $12M
- Expected growth with CRM: 25-35%
- **HubSpot ROI**: 312% over 3 years
- **Salesforce ROI**: 285% over 3 years  
- **Pipedrive ROI**: 340% over 3 years

---

## Risk Assessment

### Implementation Risks:

**Salesforce: MEDIUM-HIGH**
- **Complexity Risk**: 6-month implementation timeline
- **User Adoption**: Historical 35% initial resistance
- **Technical Dependencies**: Requires dedicated admin resource

**HubSpot: LOW-MEDIUM**
- **Integration Complexity**: Moderate setup requirements
- **Feature Gaps**: May need workarounds for advanced needs
- **Vendor Lock-in**: Migration complexity increases over time

**Pipedrive: LOW**
- **Limited Functionality**: May outgrow platform in 2-3 years
- **Integration Challenges**: Fewer native connections
- **Reporting Limitations**: May require additional BI tools

### Vendor Stability Assessment:

| Factor | Salesforce | HubSpot | Pipedrive |
|--------|------------|---------|-----------|
| **Financial Stability** | Excellent | Good | Good |
| **Market Position** | Leader | Fast follower | Niche player |
| **R&D Investment** | High | High | Medium |
| **Customer Base** | 150,000+ | 100,000+ | 95,000+ |
| **Growth Rate** | 25% annual | 35% annual | 20% annual |

---

## Stakeholder Impact Analysis

### Sales Team Impact:

**HubSpot Advantages:**
- Faster onboarding (2-3 weeks vs. 6-8 weeks)
- Better mobile experience for field sales
- Integrated email and calling features

**Salesforce Advantages:**
- Most comprehensive feature set
- Better for complex sales processes
- Advanced automation capabilities

### Marketing Team Impact:

**HubSpot Clear Winner:**
- Native marketing automation integration
- Unified lead scoring and attribution
- Single platform for campaigns and nurturing

### IT Team Impact:

**Effort Required:**
- **Salesforce**: High (dedicated admin needed)
- **HubSpot**: Medium (part-time admin sufficient)
- **Pipedrive**: Low (minimal IT involvement)

---

## Decision Framework & Recommendation

### Weighted Scoring Summary:

| Criteria | Weight | Salesforce | HubSpot | Pipedrive |
|----------|--------|------------|---------|-----------|
| **Ease of Use** | 25% | 3.5 (0.88) | 4.5 (1.13) | 4.8 (1.20) |
| **Integration** | 20% | 4.8 (0.96) | 4.3 (0.86) | 3.2 (0.64) |
| **Reporting** | 20% | 4.7 (0.94) | 4.4 (0.88) | 3.1 (0.62) |
| **Scalability** | 15% | 5.0 (0.75) | 4.2 (0.63) | 3.5 (0.53) |
| **TCO** | 10% | 3.0 (0.30) | 4.0 (0.40) | 4.5 (0.45) |
| **Support** | 5% | 4.5 (0.23) | 4.0 (0.20) | 3.5 (0.18) |
| **Mobile** | 5% | 4.0 (0.20) | 4.0 (0.20) | 5.0 (0.25) |
| **Total Score** | 100% | **4.26** | **4.30** | **3.87** |

### Final Recommendation: **HubSpot Sales Hub Professional**

**Confidence Level: 85%**

**Supporting Rationale:**
1. **Highest overall score** in weighted evaluation (4.30/5.0)
2. **Best user experience** leading to faster adoption and ROI
3. **Unified platform** eliminates marketing/sales silos
4. **Optimal TCO** for current scale with growth capacity
5. **Lower implementation risk** vs. Salesforce complexity

### Alternative Scenarios:

**If Budget <$75K annually**: Pipedrive
- Best value option with core functionality
- Plan migration to HubSpot/Salesforce in 2-3 years

**If Advanced Customization Critical**: Salesforce
- Most powerful platform for complex requirements
- Higher investment but unlimited flexibility

**If Immediate ROI Essential**: HubSpot
- Fastest implementation and user adoption
- Marketing integration provides immediate value

### Implementation Plan:
1. **Q1**: Final vendor selection and contract negotiation
2. **Q2**: Implementation and core team training (8 weeks)
3. **Q3**: Full team rollout and advanced feature adoption
4. **Q4**: Optimization and advanced automation setup

### Success Metrics:
- User adoption >90% within 60 days
- Sales cycle reduction >20% within 6 months  
- Lead-to-customer conversion improvement >25% within 12 months
- ROI positive within 18 months
```

## Variations

### Technical Product Comparison

Focus on detailed technical specifications, performance benchmarks, and compatibility requirements for technology solutions.

### Vendor Evaluation Matrix

Emphasize vendor capabilities, support quality, financial stability, and long-term partnership potential for service providers.

### Strategic Option Analysis

Compare different strategic approaches, business models, or market entry strategies using business impact criteria.

## Tips

- Define criteria clearly and get stakeholder agreement before starting comparison
- Use both quantitative scores and qualitative assessments for comprehensive evaluation
- Include total cost of ownership, not just initial pricing, in comparisons
- Consider implementation timeline and change management impacts in your analysis
- Validate information through multiple sources and direct vendor engagement

## Related Prompts

- [Data Interpreter](./data-interpreter.md) - For analyzing comparison data and metrics
- [Market Analysis](../business/market-analysis.md) - For competitive analysis context
- [Strategic Planner](../business/strategic-planner.md) - For strategic decision-making frameworks

## Tags

`comparison-analysis` `decision-matrix` `vendor-evaluation` `product-comparison` `strategic-analysis` `evaluation-framework` `decision-support` `multi-criteria-analysis`
```

#### ✨ Prompt: Data Interpreter & Analyzer

```
## Description

Analyzes datasets, interprets statistical findings, and provides actionable insights from data. Creates comprehensive data analysis reports with visualizations, trends, and business recommendations.

## Usage

Provide your dataset, analysis goals, and any specific questions you want answered. Include context about the business problem and decision criteria. Works with various data formats and analysis types.

## Prompt

```markdown
Analyze the following dataset and provide comprehensive insights:

**Analysis Objective:**
[What specific questions or problems are you trying to solve with this data?]

**Dataset Information:**
- **Data Source:** [Where the data comes from and collection methodology]

- **Time Period:** [Date range and frequency of data collection]

- **Sample Size:** [Number of records/observations]
- **Key Variables:** [Main columns/metrics in the dataset]



**Data to Analyze:**
```

[PASTE YOUR DATA HERE - CSV format, table, or summary statistics]

```

**Analysis Requirements:**
- **Analysis Type:** [Descriptive / Diagnostic / Predictive / Prescriptive]
- **Key Questions:** [Specific questions you want the data to answer]
- **Target Audience:** [Who will use these insights - executives, managers, technical team]
- **Decision Context:** [What decisions will be made based on this analysis]

**Specific Analysis Requests:**
1. **Descriptive Statistics**
   - Summary statistics for key variables
   - Distribution analysis and outlier detection
   - Missing data assessment

2. **Trend Analysis**
   - Time-based patterns and seasonality
   - Growth rates and change over time
   - Correlation between variables

3. **Segmentation Analysis**
   - Customer/product/geographic segments
   - Performance differences between groups
   - Behavioral patterns within segments

4. **Predictive Insights**
   - Forecasting based on historical patterns
   - Risk factors and warning indicators
   - Scenario modeling and what-if analysis

**Output Requirements:**
- **Format:** [Executive summary / Detailed report / Dashboard format]
- **Visualizations:** [Charts, graphs, and visual representations needed]
- **Recommendations:** [Strategic recommendations and next steps]
- **Confidence Levels:** [Statistical confidence and reliability assessment]

**Business Context:**
[Industry, company background, competitive landscape, and strategic goals]


Please provide:
1. **Executive Summary** with key findings and recommendations
2. **Detailed Analysis** with statistical insights and interpretations
3. **Visual Representation** suggestions for key findings
4. **Action Items** with prioritized recommendations

5. **Risk Assessment** and limitations of the analysis
6. **Next Steps** for further investigation or data collection
```

## Example Input

```markdown
**Analysis Objective:**
Understand customer churn patterns and identify factors that predict customer retention for our SaaS subscription service.

**Dataset Information:**
- **Data Source:** Customer database and usage analytics from past 12 months
- **Time Period:** January 2024 - December 2024
- **Sample Size:** 10,000 customers
- **Key Variables:** Subscription tier, usage frequency, support tickets, payment history, churn status

**Data to Analyze:**
| Customer_ID | Subscription_Tier | Monthly_Usage_Hours | Support_Tickets | Payment_Delays | Tenure_Months | Churned |
|-------------|------------------|-------------------|-----------------|----------------|---------------|---------|
| 1001        | Premium          | 45                | 2               | 0              | 18            | No      |
| 1002        | Basic            | 8                 | 5               | 2              | 6             | Yes     |
| 1003        | Pro              | 32                | 1               | 0              | 24            | No      |
| 1004        | Basic            | 15                | 3               | 1              | 12            | No      |

| 1005        | Premium          | 52                | 0               | 0              | 30            | No      |
| 1006        | Basic            | 3                 | 8               | 3              | 3             | Yes     |
...

**Key Questions:**
- What factors most strongly predict customer churn?

- Which customer segments have the highest retention rates?
- What usage patterns indicate at-risk customers?
- How does subscription tier affect churn probability?
```

## Example Output

```markdown
# Customer Churn Analysis Report

## Executive Summary

### Key Findings
Our analysis of 10,000 customers reveals **critical churn predictors** that can help reduce customer loss by up to 35% through targeted interventions.

**Primary Insights:**
- **Churn Rate:** Overall churn rate is 23% annually, highest in Basic tier (31%)
- **Key Predictor:** Monthly usage below 10 hours predicts 78% churn probability
- **Critical Period:** 85% of churn occurs within first 6 months of subscription

- **Support Impact:** Customers with 4+ support tickets have 65% higher churn risk


**Strategic Recommendations:**
1. **Immediate Action:** Implement usage-based early warning system for sub-10 hour users
2. **Tier Strategy:** Enhance Basic tier value proposition or sunset the offering
3. **Onboarding Focus:** Intensive support during first 6 months to drive engagement

4. **Support Optimization:** Proactive outreach for customers with multiple tickets



---


## Detailed Statistical Analysis


### 1. Churn Rate by Subscription Tier

```

Tier Analysis:

- Basic: 31% churn (3,100/10,000 customers)
- Pro: 18% churn (1,800/10,000 customers)  

- Premium: 12% churn (1,200/10,000 customers)

Statistical Significance: p < 0.001 (highly significant)

```

**Interpretation:** Clear inverse relationship between subscription tier and churn. Premium customers are 2.6x more likely to stay than Basic customers.



### 2. Usage Pattern Analysis
```

Usage Hour Segments:

- 0-5 hours/month: 67% churn rate (High Risk)

- 6-15 hours/month: 34% churn rate (Medium Risk)
- 16-30 hours/month: 15% churn rate (Low Risk)
- 31+ hours/month: 8% churn rate (Very Low Risk)

Correlation: r = -0.73 (strong negative correlation)

```

**Interpretation:** Usage is the strongest predictor of retention. Customers using less than 10 hours monthly should be flagged for intervention.



### 3. Tenure and Churn Relationship
```

Churn by Tenure:

- 0-3 months: 45% churn rate
- 4-6 months: 28% churn rate
- 7-12 months: 15% churn rate
- 13+ months: 7% churn rate

Critical Period: 85% of all churn happens in first 6 months

```

**Interpretation:** Onboarding and early engagement are crucial. Customers who survive 6 months have high long-term retention probability.




### 4. Support Ticket Impact

```

Support Interaction Analysis:

- 0 tickets: 18% churn rate
- 1-2 tickets: 22% churn rate
- 3-4 tickets: 35% churn rate
- 5+ tickets: 52% churn rate

Pattern: Each additional ticket increases churn risk by 8-12%

```




**Interpretation:** While some support is normal, multiple tickets indicate frustration. Proactive outreach needed for high-ticket customers.

### 5. Payment Behavior Correlation

```

Payment Delay Analysis:

- No delays: 19% churn rate

- 1 delay: 28% churn rate  
- 2+ delays: 46% churn rate

Financial stress strongly correlates with churn risk

```

---

## Predictive Model Results

### Churn Risk Score Formula
```

Risk Score = (10 - Monthly_Usage_Hours) × 0.4 +
             (Support_Tickets × 2.5) +
             (Payment_Delays × 3.2) +
             (Tier_Risk_Multiplier)

Where:

- Basic Tier Multiplier: +5

- Pro Tier Multiplier: +2  

- Premium Tier Multiplier: 0

```


### Risk Categories
- **High Risk (Score 15+):** 70% churn probability - Immediate intervention needed
- **Medium Risk (Score 8-14):** 35% churn probability - Monitor and engage
- **Low Risk (Score 0-7):** 12% churn probability - Standard retention efforts

---

## Visualization Recommendations

### 1. Executive Dashboard
```

Suggested Charts:

- Churn Rate by Tier (Bar Chart)
- Usage vs. Retention (Scatter Plot)  
- Monthly Churn Trend (Line Chart)
- Risk Score Distribution (Histogram)

```

### 2. Operational Dashboards
```

Real-time Monitoring:

- At-Risk Customer List (Table with risk scores)
- Usage Heatmap by Customer Segment
- Support Ticket Impact Tracker
- Early Warning Alerts Dashboard

```

---

## Strategic Recommendations

### Priority 1: Early Warning System (Implement in 30 days)
**Action:** Create automated alerts for customers with:
- Usage below 10 hours for 2 consecutive months
- 3+ support tickets in 30 days
- Any payment delays

**Expected Impact:** 25% reduction in preventable churn
**Investment:** $15K in system development

### Priority 2: Enhanced Onboarding (60 days)
**Action:** Intensive 90-day onboarding program including:
- Weekly check-ins for first month
- Usage goal setting and tracking

- Personalized feature recommendations

**Expected Impact:** 40% improvement in 6-month retention
**Investment:** 2 FTE customer success roles

### Priority 3: Basic Tier Strategy Review (90 days)

**Action:** Either enhance Basic tier value or migrate users to Pro tier
- Add features that drive engagement
- Implement usage-based pricing
- Create clear upgrade path incentives

**Expected Impact:** 15% overall churn reduction
**Investment:** Product development and pricing strategy work


---

## Risk Assessment & Limitations

### Data Quality Considerations

- **Sample Bias:** Analysis based on existing customers only
- **Temporal Factors:** Seasonal effects not fully captured in 12-month view
- **External Variables:** Economic factors and competition not included

### Model Limitations
- **Predictive Accuracy:** 78% accuracy in test set
- **False Positives:** 15% of "high risk" customers won't actually churn
- **Causation vs. Correlation:** Usage patterns may be effect, not cause of satisfaction

### Confidence Levels
- **High Confidence:** Usage and tier relationships (>95% confidence)
- **Medium Confidence:** Support ticket correlations (85% confidence)

- **Lower Confidence:** Payment delay causation (70% confidence)

---

## Next Steps & Further Analysis


### Immediate Actions (Week 1)
1. Implement risk scoring system for existing customers
2. Create high-risk customer list for customer success team
3. Set up automated usage monitoring alerts

### Short-term Analysis (Month 1)
1. **Cohort Analysis:** Track retention by acquisition channel and time period
2. **Feature Usage:** Analyze which specific features correlate with retention

3. **Competitive Analysis:** Survey churned customers about alternatives chosen

### Long-term Research (Quarter 1)
1. **A/B Testing:** Test intervention strategies on at-risk segments
2. **Predictive Modeling:** Develop machine learning models for churn prediction

3. **Customer Journey Mapping:** Detailed analysis of pre-churn behavior patterns

### Success Metrics to Track
- Monthly churn rate reduction
- Early warning system accuracy
- Customer lifetime value improvement
- Support ticket resolution impact on retention

This analysis provides a solid foundation for data-driven customer retention strategies. The key is implementing the early warning system quickly while building longer-term engagement programs.
```

## Variations

- **Financial Analysis**: Focus on revenue, profitability, and financial metrics
- **Market Research**: Analyze survey data, market trends, and competitive intelligence
- **Performance Analytics**: Website, app, or business performance data analysis
- **Scientific Data**: Research data analysis with statistical testing and hypothesis validation

## Tips

- Always start with clear questions you want the data to answer
- Provide context about how decisions will be made based on the analysis
- Include information about data collection methods and potential biases
- Ask for confidence levels and limitations along with insights
- Request specific visualizations that would be most helpful for your audience
- Consider asking for both statistical significance and practical significance

## Related Prompts

- `meeting-summary.md` - For documenting data review meetings and decisions
- `proposal-writer.md` - For creating proposals based on analytical findings
- `technical-documentation.md` - For documenting analytical methods and procedures

## Tags

`data-analysis` `statistics` `insights` `reporting` `decision-support` `analytics`
```

#### ✨ Prompt: Research Synthesizer

```
## Description

This prompt helps you analyze, synthesize, and consolidate multiple research sources, studies, and data points into coherent insights, comprehensive reports, and actionable conclusions.

## Usage

Perfect for literature reviews, market research synthesis, academic research, competitive analysis, trend analysis, and creating comprehensive reports from multiple data sources.

## Prompt

```markdown
You are an expert research analyst with advanced skills in data synthesis, critical analysis, and insight generation. I need help synthesizing multiple research sources into a comprehensive, actionable analysis.

**Research Synthesis Project:**
- Research topic: [MAIN_RESEARCH_QUESTION_OR_TOPIC]
- Purpose: [ACADEMIC/BUSINESS_DECISION/POLICY/STRATEGIC_PLANNING]
- Target audience: [WHO_WILL_USE_THIS_RESEARCH]
- Scope: [BREADTH_AND_DEPTH_OF_ANALYSIS_NEEDED]
- Time frame: [RESEARCH_PERIOD_OR_CURRENCY_REQUIREMENTS]

**Research Sources Available:**
- Academic papers: [NUMBER_AND_TYPE_OF_STUDIES]
- Industry reports: [MARKET_RESEARCH_REPORTS_AVAILABLE]
- Survey data: [PRIMARY_DATA_SOURCES]
- News articles: [CURRENT_EVENTS_AND_TRENDS]
- Expert interviews: [QUALITATIVE_INSIGHTS_AVAILABLE]
- Government data: [OFFICIAL_STATISTICS_AND_REPORTS]

**Analysis Requirements:**
- Key questions to answer: [SPECIFIC_RESEARCH_QUESTIONS]
- Conflicting viewpoints: [AREAS_OF_DISAGREEMENT_IN_SOURCES]
- Evidence quality: [ASSESS_RELIABILITY_AND_BIAS]
- Gaps in research: [IDENTIFY_MISSING_INFORMATION]
- Practical applications: [HOW_INSIGHTS_WILL_BE_USED]

**Output Format Preference:**
- Report length: [EXECUTIVE_SUMMARY/DETAILED_REPORT/PRESENTATION]
- Visual elements: [CHARTS/TABLES/INFOGRAPHICS_NEEDED]
- Citation style: [ACADEMIC/BUSINESS/REFERENCE_FORMAT]

Please provide a comprehensive research synthesis including:

1. **Executive Summary:**
   - Key findings and insights
   - Main conclusions and recommendations
   - Confidence levels and limitations
   - Critical gaps requiring further research

2. **Methodology Assessment:**
   - Source evaluation and credibility analysis
   - Research quality and methodology review
   - Bias identification and mitigation
   - Data triangulation and validation approaches

3. **Thematic Analysis:**
   - Major themes and patterns across sources
   - Convergent findings and consensus areas
   - Divergent viewpoints and conflicting evidence
   - Evolution of thinking over time

4. **Evidence Synthesis:**
   - Quantitative data integration and meta-analysis
   - Qualitative insights and pattern recognition
   - Cross-referencing and corroboration
   - Statistical significance and effect sizes

5. **Critical Analysis:**
   - Strengths and limitations of available evidence
   - Methodological concerns and validity issues
   - Sample size, representativeness, and generalizability
   - Potential confounding factors and alternative explanations

6. **Insight Generation:**
   - Novel connections and relationships identified
   - Implications for theory and practice
   - Predictive insights and future trends
   - Actionable recommendations based on evidence

7. **Research Gaps & Future Directions:**
   - Areas requiring additional investigation
   - Methodological improvements needed
   - Emerging questions and hypotheses
   - Recommended research priorities

8. **Practical Applications:**
   - Implementation recommendations
   - Risk assessment and mitigation strategies
   - Success factors and best practices
   - Monitoring and evaluation frameworks

Ensure the synthesis is objective, evidence-based, and clearly distinguishes between established facts, emerging trends, and speculative insights.
```

## Example Input

```markdown
Research topic: Impact of remote work on employee productivity and well-being
Purpose: Strategic planning for hybrid work policy development
Target audience: C-suite executives and HR leadership
Scope: Comprehensive analysis across industries and company sizes
Time frame: Research from 2020-2024 (post-pandemic era)

Research sources:
- Academic papers: 25 peer-reviewed studies on remote work productivity
- Industry reports: 8 major consulting firm studies (McKinsey, Deloitte, PwC)
- Survey data: 4 large-scale employee surveys (10K+ respondents each)
- News articles: 50+ articles from major business publications
- Expert interviews: 12 interviews with HR executives and workplace researchers

Key questions:
- How does remote work impact overall productivity?
- What are the effects on employee mental health and job satisfaction?
- Which factors determine success in remote work arrangements?
- How do impacts vary by role type, seniority, and industry?

Conflicting viewpoints: Productivity gains vs. losses, collaboration challenges, long-term sustainability
Evidence quality: Mix of rigorous academic studies and industry surveys with varying methodologies
```

## Example Output

```markdown
# Remote Work Impact Analysis: Comprehensive Research Synthesis

## Executive Summary

**Key Finding**: Remote work demonstrates a **net positive impact** on both productivity (average +13% increase) and employee well-being (71% report improved work-life balance), but success depends heavily on implementation quality and role suitability.

**Primary Conclusions:**
1. **Productivity**: Individual contributor roles show 10-20% productivity gains; collaborative roles show mixed results
2. **Well-being**: Significant improvements in work-life balance offset by increased isolation concerns
3. **Success Factors**: Technology infrastructure, management practices, and role design are critical determinants
4. **Optimal Model**: Hybrid arrangements (2-3 days remote) maximize benefits while minimizing downsides

**Confidence Level**: High for individual productivity impacts (strong evidence), Medium for long-term organizational effects (limited longitudinal data)

**Critical Gap**: Insufficient research on 5+ year impacts and optimal hybrid configurations by industry type.

---

## Methodology Assessment

### Source Quality Analysis:

**Academic Studies (25 papers):**
- **Strengths**: Rigorous methodology, controlled variables, peer review
- **Limitations**: Often small sample sizes (median: 847 participants), pre-pandemic data limitations
- **Bias Risk**: Publication bias toward significant findings, limited industry diversity

**Industry Reports (8 studies):**
- **Strengths**: Large sample sizes (average: 15,000 respondents), current data, industry breadth
- **Limitations**: Potential selection bias, self-reported metrics, commercial interests
- **Quality Range**: McKinsey/BCG studies most rigorous, vendor-sponsored reports less reliable

**Employee Surveys (4 major surveys):**
- **Strengths**: Real-world perspectives, longitudinal tracking, demographic diversity
- **Limitations**: Self-reporting bias, response rate variations (32-67%), survivorship bias

### Data Triangulation:
Cross-referencing academic studies with industry surveys shows **85% alignment** on core productivity findings, increasing confidence in conclusions.

---

## Thematic Analysis

### Theme 1: Productivity Impacts - **Mixed but Generally Positive**

**Convergent Findings:**
- Individual-focused roles show consistent 10-20% productivity gains
- Reduced commute stress improves focus and energy levels
- Flexible scheduling enables better peak performance timing
- Reduced office interruptions increase deep work capacity

**Divergent Evidence:**
- **Academic studies**: More conservative estimates (5-15% gains)
- **Industry surveys**: Higher reported gains (15-25%)
- **Management vs. Employee perspectives**: Managers more skeptical of gains

### Theme 2: Well-being Outcomes - **Improved but Complex**

**Consensus Areas:**
- **Work-life balance**: 71% report improvement (consistent across all sources)
- **Stress reduction**: 58% report lower stress levels
- **Family relationships**: 64% report stronger family connections

**Conflicting Evidence:**
- **Social isolation**: Range from 35-65% reporting isolation concerns
- **Career advancement**: Mixed findings on promotion rates and visibility

### Theme 3: Success Factors - **Implementation Quality Critical**

**Universal Success Factors:**
1. **Technology infrastructure** (mentioned in 23/25 academic studies)
2. **Manager training** (correlation with positive outcomes: r=0.67)
3. **Clear communication protocols** (reduces coordination issues by 40%)
4. **Results-oriented performance management** (vs. time-based monitoring)

---

## Evidence Synthesis

### Quantitative Meta-Analysis:

**Productivity Metrics (weighted average across studies):**
- **Individual Contributor Roles**: +13.2% productivity increase (95% CI: 8.1%-18.3%)
- **Collaborative Roles**: +2.1% increase (95% CI: -3.2%-7.4%) - not statistically significant
- **Management Roles**: -4.7% decrease (95% CI: -9.1%-0.3%)

**Well-being Indicators:**
- **Work-life balance satisfaction**: +34% improvement
- **Job satisfaction**: +18% improvement  
- **Burnout risk**: -22% reduction
- **Social connectedness**: -15% reduction

### Qualitative Pattern Recognition:

**Success Story Characteristics:**
- Technology-first companies show better outcomes (avg. +19% productivity)
- Companies with existing flexible work cultures adapt more successfully
- Role-specific policies outperform one-size-fits-all approaches

**Failure Pattern Identification:**
- Sudden, forced implementation without training (-8% productivity average)
- Inadequate technology infrastructure correlates with negative outcomes
- Lack of social interaction protocols increases turnover by 23%

---

## Critical Analysis

### Evidence Strengths:
- **Large sample sizes**: Combined research covers 180,000+ employees
- **Diverse methodologies**: Triangulation across quantitative and qualitative approaches
- **Real-world setting**: Post-pandemic data reflects actual implementation rather than pilots
- **Longitudinal tracking**: 60% of studies include 12+ month follow-up data

### Key Limitations:
- **Self-selection bias**: Remote workers may be predisposed to prefer/succeed in remote settings
- **Novelty effects**: Some productivity gains may diminish over time
- **Industry skew**: 68% of research focuses on knowledge work; limited manufacturing/service data
- **Cultural factors**: 89% of studies from Western countries; limited global perspective

### Alternative Explanations:
- **Economic conditions**: Pandemic-era job market may influence satisfaction scores
- **Technology advancement**: Productivity gains may reflect improved tools rather than work location
- **Measurement challenges**: Traditional productivity metrics may not capture all remote work impacts

---

## Insight Generation

### Novel Connections Identified:

**1. The "Productivity Paradox" Resolution:**
Individual productivity increases while organizational productivity shows mixed results - explained by **coordination costs** and **knowledge transfer deficits** that affect collective output despite individual gains.

**2. Well-being "Honeymoon Effect":**
Initial well-being improvements (months 1-6) followed by gradual decline (months 12-18) suggests need for **adaptive management strategies** over time.

**3. Role Suitability Framework:**
```

High Remote Suitability:

- Individual contributor work (coding, writing, analysis)
- Structured processes with clear deliverables
- Digital-native workflows

Low Remote Suitability:  

- High-collaboration roles (design thinking, strategic planning)
- Mentoring/training intensive positions
- Customer-facing roles requiring relationship building

```

### Predictive Insights:

**Short-term (1-2 years):**
- Hybrid models will become dominant (predicted 73% adoption by 2025)
- Investment in collaboration technology will increase 40% annually
- Performance management systems will shift toward outcome-based metrics

**Long-term (3-5 years):**
- Remote work skills will become core competencies for management roles
- Office spaces will redesign for collaboration rather than individual work
- Geographic talent pool expansion will increase salary competition

---

## Research Gaps & Future Directions

### Critical Missing Research:

**1. Long-term Organizational Impact (5+ years)**
- Innovation capacity and breakthrough development
- Organizational culture evolution and preservation
- Knowledge transfer across generations of employees

**2. Industry-Specific Analysis**
- Manufacturing and service industry adaptations
- Healthcare and education sector applications
- Government and public sector implementations

**3. Demographic Deep Dives**
- Career stage impacts (early vs. late career)
- Cultural and geographic variations globally
- Accessibility and inclusion implications

### Recommended Research Priorities:

**High Priority:**
- Longitudinal studies tracking productivity and well-being over 3+ years
- Controlled experiments comparing hybrid model variations
- Industry-specific best practice development

**Medium Priority:**
- Technology tool effectiveness comparative studies
- Global/cultural adaptation research
- Environmental impact analysis of remote work

---

## Practical Applications

### Implementation Recommendations:

**Phase 1: Assessment (Months 1-2)**
- Conduct role suitability analysis using framework above
- Survey employee preferences and current satisfaction
- Audit technology infrastructure and collaboration tools
- Benchmark current productivity and well-being metrics

**Phase 2: Pilot Design (Months 3-4)**
- Implement differentiated policies by role type
- Design hybrid schedules based on collaborative needs
- Establish clear communication protocols and expectations
- Train managers on remote team leadership

**Phase 3: Full Implementation (Months 5-12)**
- Roll out organization-wide policy with role-specific guidelines
- Monitor productivity, well-being, and engagement metrics monthly
- Adjust policies based on feedback and performance data
- Invest in technology upgrades and training programs

### Success Metrics Framework:

**Productivity Indicators:**
- Output quality and quantity (role-specific measures)
- Goal achievement and deadline adherence
- Customer/client satisfaction scores

**Well-being Measures:**
- Employee satisfaction surveys (quarterly)
- Work-life balance self-assessments
- Burnout and stress indicators
- Social connectedness metrics

**Organizational Health:**
- Employee retention and turnover analysis
- Internal promotion and career development rates
- Innovation metrics and new idea generation
- Collaboration effectiveness scores

### Risk Mitigation Strategies:

**Isolation and Disconnection:**
- Mandatory in-person collaboration days
- Virtual social events and team building
- Mentorship programs with regular check-ins

**Productivity Decline:**
- Outcome-based performance management
- Regular 1:1s with clear expectation setting
- Technology training and support resources

**Innovation and Creativity Concerns:**
- Dedicated collaboration spaces and times
- Cross-functional project teams with in-person components
- Innovation workshops and brainstorming sessions

**Long-term Organizational Culture:**
- Values reinforcement through all-hands meetings
- Culture ambassadors and champions
- Regular culture assessment and adjustment
```

## Variations

### Literature Review Focus

Emphasize academic source synthesis with formal citation and theoretical framework development for research and academic purposes.

### Competitive Intelligence Synthesis

Focus on analyzing competitor information, market intelligence, and strategic insights from multiple business sources.

### Policy Research Analysis

Synthesize research for policy development, including government studies, think tank reports, and public data analysis.

## Tips

- Always evaluate source credibility and potential bias before synthesizing information
- Look for patterns across different types of sources to increase confidence in findings
- Clearly distinguish between correlation and causation in your analysis
- Highlight areas where evidence is limited or conflicting rather than forcing consensus
- Use visual elements like charts and tables to make complex synthesis more accessible

## Related Prompts

- [Data Interpreter](./data-interpreter.md) - For analyzing specific datasets
- [Trend Analyzer](./trend-analyzer.md) - For identifying patterns over time
- [Comparison Matrix](./comparison-matrix.md) - For structured comparison analysis

## Tags

`research-synthesis` `literature-review` `data-analysis` `evidence-assessment` `meta-analysis` `insight-generation` `research-methodology` `critical-analysis`
```

#### ✨ Prompt: Trend Analyzer

```
## Description

This prompt helps you identify, analyze, and predict trends from data, market signals, and emerging patterns to support strategic decision-making and future planning.

## Usage

Perfect for market research, strategic planning, investment analysis, product development, innovation management, and staying ahead of industry changes and consumer behavior shifts.

## Prompt

```markdown
You are an expert trend analyst with deep expertise in pattern recognition, data analysis, and predictive insights. I need comprehensive trend analysis to understand emerging patterns and their implications.

**Trend Analysis Scope:**
- Domain/industry: [SPECIFIC_SECTOR_OR_MARKET]
- Analysis focus: [TECHNOLOGY/CONSUMER_BEHAVIOR/MARKET/SOCIAL/ECONOMIC]
- Time frame: [HISTORICAL_PERIOD_AND_FUTURE_PROJECTION]
- Geographic scope: [LOCAL/REGIONAL/GLOBAL_FOCUS]
- Purpose: [STRATEGIC_PLANNING/INVESTMENT/PRODUCT_DEVELOPMENT/RISK_ASSESSMENT]

**Data Sources Available:**
- Market data: [SALES_TRENDS/MARKET_SIZE/PRICING_DATA]
- Consumer insights: [SURVEYS/BEHAVIOR_DATA/PREFERENCES]
- Technology indicators: [PATENTS/RESEARCH/ADOPTION_RATES]
- Social signals: [SOCIAL_MEDIA/NEWS/CULTURAL_SHIFTS]
- Economic factors: [FINANCIAL_DATA/REGULATORY_CHANGES]

**Specific Focus Areas:**
- Emerging trends: [EARLY_SIGNALS_TO_INVESTIGATE]
- Established trends: [CURRENT_TRENDS_TO_TRACK]
- Disruption potential: [THREATS_AND_OPPORTUNITIES]
- Time horizons: [SHORT_TERM/MEDIUM_TERM/LONG_TERM_IMPACTS]

**Key Questions:**
- [CUSTOM_TREND_QUESTION_1]
- [CUSTOM_TREND_QUESTION_2]
- [CUSTOM_TREND_QUESTION_3]

Please provide comprehensive trend analysis including:

1. **Executive Summary:**
   - Top 5 trends with highest impact potential
   - Key insights and strategic implications
   - Timeline for trend maturation and adoption
   - Confidence levels and uncertainty factors

2. **Trend Identification & Classification:**
   - Mega trends (long-term, fundamental shifts)
   - Macro trends (significant medium-term changes)
   - Micro trends (emerging short-term patterns)
   - Fad vs. lasting trend assessment
   - Trend interconnections and dependencies

3. **Trend Analysis Framework:**
   - Trend lifecycle stage (emergence, growth, maturity, decline)
   - Adoption curve positioning and diffusion patterns
   - Market penetration rates and growth trajectories
   - Geographic spread and cultural variations
   - Demographic and psychographic drivers

4. **Impact Assessment:**
   - Industry disruption potential (high/medium/low)
   - Market size and revenue implications
   - Competitive landscape changes
   - Consumer behavior shifts
   - Technology adoption requirements

5. **Predictive Modeling:**
   - Trend trajectory projections (1, 3, 5 year outlook)
   - Scenario analysis (optimistic, realistic, pessimistic)
   - Adoption rate forecasting and market penetration
   - Tipping point identification and catalyst events
   - Convergence opportunities with other trends

6. **Signal Detection:**
   - Early warning indicators and leading signals
   - Data sources for ongoing monitoring
   - Weak signals requiring investigation
   - Counter-trends and resistance factors
   - Emerging anomalies and pattern breaks

7. **Strategic Implications:**
   - Opportunities for innovation and growth
   - Threats requiring defensive strategies
   - Investment priorities and resource allocation
   - Partnership and collaboration opportunities
   - Capability development requirements

8. **Actionable Recommendations:**
   - Short-term tactical responses (0-12 months)
   - Medium-term strategic initiatives (1-3 years)
   - Long-term positioning strategies (3-5 years)
   - Risk mitigation and hedging strategies
   - Monitoring and tracking mechanisms

Include confidence intervals, data quality assessments, and alternative scenario considerations where applicable.
```

## Example Input

```markdown
Domain/industry: Electric vehicle and automotive technology
Analysis focus: Technology adoption and consumer behavior trends
Time frame: 2020-2024 historical, 2025-2030 projections
Geographic scope: Global with focus on US, Europe, China
Purpose: Strategic planning for automotive supplier company

Data sources:
- Market data: EV sales by region, battery cost trends, charging infrastructure growth
- Consumer insights: Purchase intent surveys, adoption barriers research
- Technology indicators: Battery energy density improvements, autonomous driving patents
- Social signals: Environmental awareness, government policies, social media sentiment
- Economic factors: Oil prices, government incentives, carbon pricing policies

Emerging trends: Solid-state batteries, vehicle-to-grid integration, subscription models
Established trends: Battery cost decline, charging infrastructure expansion
Disruption potential: Autonomous vehicles, mobility-as-a-service

Key questions:
- When will EVs reach price parity with ICE vehicles?
- How will autonomous driving impact EV adoption?
- What are the implications for traditional automotive suppliers?
```

## Example Output

```markdown
# Electric Vehicle & Automotive Technology Trend Analysis 2024-2030

## Executive Summary

**Top 5 High-Impact Trends:**

1. **EV Price Parity Achievement** (2025-2027): Battery cost decline reaches tipping point
2. **Autonomous Driving Integration** (2026-2030): L3+ autonomy becomes mainstream feature  
3. **Vehicle-to-Grid Ecosystem** (2025-2028): Cars become distributed energy storage
4. **Mobility-as-a-Service Expansion** (2024-2027): Ownership model disruption accelerates
5. **Solid-State Battery Revolution** (2027-2030): Next-generation energy storage breakthrough

**Strategic Implications:**
- **Supply Chain Transformation**: Traditional ICE components declining 15-25% annually post-2026
- **New Revenue Streams**: Software, services, and energy management creating $200B+ market
- **Geographic Shifts**: China and Europe leading adoption, US accelerating rapidly

**Timeline Confidence**: High for 2024-2026 trends (85%+), Medium for 2027-2030 projections (65-75%)

---

## Trend Identification & Classification

### Mega Trends (5-10 year fundamental shifts):

**1. Electrification Transition**
- **Status**: Late growth stage (18% global market share in 2024)
- **Driver**: Climate policy + technology maturity + cost competitiveness
- **Peak Impact**: 2026-2028 (mass market tipping point)

**2. Mobility Ecosystem Transformation**
- **Status**: Early growth stage (fragmented solutions emerging)
- **Driver**: Urbanization + sharing economy + autonomous technology
- **Peak Impact**: 2028-2032 (integrated platforms mature)

### Macro Trends (2-5 year significant changes):

**1. Battery Technology Convergence**
- **Current**: LFP and NCM batteries dominating, solid-state emerging
- **Trajectory**: Energy density +8-12% annually, cost decline -15% annually
- **Inflection Point**: 2025-2026 (sub-$100/kWh threshold)

**2. Charging Infrastructure Ubiquity**
- **Current**: 3.2M global charging points, 55% growth annually
- **Trajectory**: Exponential growth in fast charging (350kW+)
- **Tipping Point**: 2026 (charging anxiety eliminated in developed markets)

### Micro Trends (6-24 month emerging patterns):

**1. Vehicle-to-Everything (V2X) Integration**
- **Emergence**: 2024 pilots in Europe and California
- **Early Adopters**: Premium EV brands, smart city initiatives
- **Commercial Viability**: 2025-2026 with grid integration incentives

**2. EV Subscription Models**
- **Current**: 12% of new EV "purchases" are subscriptions
- **Growth**: +45% annually as manufacturers seek recurring revenue
- **Mainstream Adoption**: 2025-2026 for urban markets

---

## Trend Analysis Framework

### EV Adoption Lifecycle Analysis:

**Innovation Phase (2008-2015):** Tesla Model S, early adopters
**Early Adoption (2016-2021):** Premium segment expansion, government incentives
**Early Majority (2022-2026):** Mass market models, infrastructure buildout  
**Late Majority (2027-2032):** Price parity achieved, mainstream acceptance
**Laggards (2033+):** ICE phase-out, regulatory mandate completion

### Geographic Adoption Patterns:

```

Region          2024 EV Share    2027 Projection    Key Drivers
Norway          88%              95%+               Policy + incentives
China           35%              55%                Manufacturing scale
Europe          23%              45%                Regulation + infrastructure  
California      26%              50%                Policy + consumer preference
US National     9%               25%                Federal support + automaker push

```

### Consumer Adoption Curve:
- **Innovators (2.5%)**: Already converted, driving premium segment
- **Early Adopters (13.5%)**: Currently converting, price-sensitive but motivated
- **Early Majority (34%)**: Waiting for price parity + infrastructure confidence
- **Late Majority (34%)**: Will convert when ICE becomes inconvenient/expensive

---

## Impact Assessment

### Industry Disruption Potential: **HIGH**

**Automotive Manufacturing:**
- **Traditional OEMs**: Massive capital reallocation required ($100B+ investments)
- **New Entrants**: Tesla, BYD, emerging brands gaining 25%+ market share
- **Supplier Ecosystem**: 40% of ICE suppliers face obsolescence by 2030

**Energy Sector:**
- **Oil Demand**: Peak passenger vehicle demand by 2027-2029
- **Electricity Grid**: 15-20% additional capacity needed by 2030
- **New Business Models**: Vehicle-to-grid creating $50B+ revenue opportunity

### Market Size Implications:

```

Segment                     2024        2030E       CAGR
Global EV Sales            14.1M       47.5M       22%
Battery Market             $120B       $400B       22%
Charging Infrastructure    $45B        $180B       26%
Autonomous Tech            $25B        $120B       30%
Mobility Services          $280B       $650B       15%

```

---

## Predictive Modeling

### Key Inflection Points & Timelines:

**2025: Battery Cost Breakthrough**
- Sub-$100/kWh achieved at scale
- EV-ICE price parity for mid-size vehicles
- Charging time drops below 15 minutes for 80% charge

**2026: Infrastructure Tipping Point**
- 1 fast charger per 1,000 people in developed markets
- Range anxiety eliminated for 90% of consumers
- Workplace charging becomes standard

**2027: Mainstream Adoption Acceleration**  
- EV sales exceed 30% globally
- Used EV market becomes viable
- Traditional automaker EV profits turn positive

**2028: Autonomous Integration**
- L3 autonomy standard in premium EVs
- Ride-sharing fleets 60%+ electric
- Vehicle utilization rates increase 3x in urban areas

### Scenario Analysis:

**Optimistic Scenario (+20% acceleration):**
- Government incentives extended and expanded
- Battery breakthroughs accelerate timeline by 2 years
- Oil prices spike above $120/barrel sustained
- **Result**: 60% EV adoption by 2030

**Realistic Scenario (base case):**
- Current policy trajectory continues
- Technology development as projected
- Economic conditions remain stable
- **Result**: 40% EV adoption by 2030

**Pessimistic Scenario (-25% deceleration):**
- Economic recession reduces EV demand
- Raw material shortages constrain battery production
- Charging infrastructure development slows
- **Result**: 25% EV adoption by 2030

---

## Signal Detection & Monitoring

### Leading Indicators to Track:

**Technology Signals:**
- Battery energy density improvements (>250 Wh/kg threshold)
- Solid-state battery pilot production announcements
- Charging speed improvements (>350kW deployment)
- Autonomous driving disengagement rates

**Market Signals:**
- EV inventory levels vs. ICE vehicles
- Used EV resale value trends
- EV insurance cost parity achievement
- Corporate fleet electrification announcements

**Policy Signals:**
- ICE vehicle ban announcements beyond 2030
- Carbon pricing expansion and increases  
- EV incentive program extensions/modifications
- Grid integration regulation development

### Weak Signals Requiring Investigation:

**1. Hydrogen Fuel Cell Resurgence**
- Heavy truck adoption could spill into passenger vehicles
- Japanese/Korean automaker investments increasing
- Infrastructure development in select corridors

**2. Battery Recycling Breakthrough**
- Circular economy could dramatically reduce raw material needs
- New business models around battery lifecycle management
- Regulatory requirements driving innovation

**3. Autonomous Vehicle Delays**
- Technical challenges proving more difficult than expected
- Regulatory approval processes slower than anticipated  
- Consumer acceptance lower than projected

---

## Strategic Implications for Automotive Suppliers

### Immediate Opportunities (2024-2025):

**1. EV Component Scaling**
- Battery pack assembly and thermal management
- Electric motor manufacturing capabilities
- High-voltage wiring harnesses and connectors

**2. Charging Infrastructure**
- Manufacturing charging equipment components
- Installation and maintenance service networks
- Grid integration and smart charging technology

### Medium-Term Positioning (2025-2027):

**1. Software Integration**
- Battery management system development
- Vehicle-to-grid communication protocols
- Predictive maintenance and diagnostics

**2. Vertical Integration**
- Secure critical mineral supply chains (lithium, cobalt, nickel)
- Partner with battery manufacturers
- Develop recycling capabilities

### Long-Term Transformation (2027-2030):

**1. Platform Business Models**
- Mobility-as-a-service infrastructure
- Energy management services
- Autonomous vehicle supporting systems

**2. Innovation Leadership**
- Solid-state battery technology partnerships
- Advanced driver assistance system components
- Vehicle-to-everything communication hardware

---

## Actionable Recommendations

### Short-Term (0-12 months):

**Strategic Actions:**
- Conduct comprehensive portfolio review: ICE vs. EV component future
- Initiate partnerships with EV-focused OEMs and startups
- Invest in employee retraining for EV technologies
- Secure critical material supply agreements

**Investment Priorities:**
- EV component manufacturing capacity ($50-100M)
- R&D team expansion in electrification (50-100 engineers)
- Testing and validation equipment for EV components
- Strategic acquisitions of EV technology companies

### Medium-Term (1-3 years):

**Market Positioning:**
- Establish leadership in 2-3 critical EV component categories
- Build comprehensive EV supplier certification
- Develop direct relationships with battery manufacturers
- Create software capabilities for smart components

**Capability Development:**
- Advanced manufacturing for high-voltage systems
- Quality systems for automotive-grade electronics
- Rapid prototyping and agile development processes
- Sustainability and lifecycle assessment expertise

### Long-Term (3-5 years):

**Transformation Goals:**
- Achieve 60%+ revenue from EV-related products
- Establish platform business model generating recurring revenue
- Build end-to-end solutions capability vs. component supply
- Position for autonomous vehicle integration opportunities

### Risk Mitigation:

**Technology Risk:**
- Diversify across multiple EV technology paths
- Maintain ICE capabilities until transition complete
- Build flexibility in manufacturing systems

**Market Risk:**
- Geographic diversification across EV adoption leaders
- Customer diversification beyond traditional OEMs
- Develop aftermarket and service revenue streams

**Financial Risk:**
- Phase investments based on market adoption milestones
- Secure long-term customer commitments before major capex
- Maintain liquidity for transition period challenges

### Monitoring Dashboard:

**Monthly Metrics:**
- EV sales penetration by region
- Customer EV roadmap updates and timeline changes
- Competitive wins/losses in EV components
- Raw material price trends and availability

**Quarterly Reviews:**
- Technology roadmap progress and milestone achievement
- Financial performance vs. transition plan targets
- Market share evolution in targeted EV segments
- Strategic partnership development and value creation
```

## Variations

### Technology Trend Analysis

Focus specifically on emerging technologies, innovation cycles, and disruption patterns in tech sectors.

### Consumer Behavior Trends

Analyze changing consumer preferences, purchasing patterns, and lifestyle shifts affecting market demand.

### Market Trend Investigation

Examine market dynamics, competitive shifts, and industry evolution patterns for strategic positioning.

## Tips

- Use multiple data sources and cross-validate trends to avoid false signals
- Distinguish between correlation and causation when identifying trend drivers
- Consider cultural and geographic variations in trend adoption and impact
- Balance quantitative data with qualitative insights for comprehensive analysis
- Update trend analysis regularly as new data becomes available

## Related Prompts

- [Data Interpreter](./data-interpreter.md) - For analyzing datasets supporting trend analysis
- [Research Synthesizer](./research-synthesizer.md) - For synthesizing multiple trend reports
- [Market Analysis](../business/market-analysis.md) - For market-specific trend analysis

## Tags

`trend-analysis` `forecasting` `pattern-recognition` `market-intelligence` `strategic-planning` `innovation-tracking` `future-planning` `data-analysis`
```


### 📁 Categoria: Business

#### ✨ Prompt: Business Prompts

```
This directory contains prompts for business and professional applications.

## Categories

- **Strategic Planning**: Business strategy and planning assistance
- **Market Analysis**: Market research and competitive analysis
- **Process Optimization**: Improving business processes and workflows
- **Meeting Management**: Meeting summaries and action items
- **Financial Analysis**: Financial planning and analysis
- **Communication**: Professional communication templates
- **E-commerce**: Product listings and marketplace optimization

## Example Prompts

- `meeting-summary.md` - Transform meeting notes into actionable summaries
- `proposal-writer.md` - Create compelling business proposals and bids
- `strategic-planner.md` - Develop comprehensive business strategies
- `market-analysis.md` - Analyze markets, competitors, and opportunities
- `xianyu-product-description.md` - Create effective Xianyu marketplace listings

## Business Applications

- Use for strategic decision-making
- Improve operational efficiency
- Enhance professional communication
- Support planning and analysis activities

---
*Add your business prompts to this directory following the template structure.*
```

#### ✨ Prompt: Market Analysis

```
## Description

This prompt helps you conduct comprehensive market research and analysis to understand industry trends, competitor landscapes, target audiences, and market opportunities for strategic decision-making.

## Usage

Perfect for business planning, investment decisions, product launches, competitive intelligence, market entry strategies, and understanding industry dynamics and customer behavior.

## Prompt

```markdown
You are an expert market research analyst and business strategist. I need a comprehensive market analysis to make informed business decisions and identify opportunities.

**Market Analysis Scope:**
- Industry/market: [SPECIFIC_INDUSTRY_OR_MARKET]
- Geographic focus: [REGION/COUNTRY/GLOBAL]
- Time frame: [CURRENT/HISTORICAL/FORECAST_PERIOD]
- Analysis purpose: [MARKET_ENTRY/INVESTMENT/PRODUCT_LAUNCH/COMPETITIVE_INTELLIGENCE]
- Target segment: [CUSTOMER_SEGMENT_IF_SPECIFIC]

**Key Analysis Areas:**
- Market size and growth: [REVENUE/VOLUME/USERS]
- Competitive landscape: [KEY_PLAYERS_IF_KNOWN]
- Customer behavior: [B2B/B2C/DEMOGRAPHICS]
- Technology trends: [RELEVANT_TECH_FACTORS]
- Regulatory environment: [COMPLIANCE_CONSIDERATIONS]

**Specific Questions to Address:**
- [CUSTOM_QUESTION_1]
- [CUSTOM_QUESTION_2]
- [CUSTOM_QUESTION_3]

Please provide a comprehensive market analysis including:

1. **Executive Summary:**
   - Key findings and insights
   - Market attractiveness assessment
   - Top 3 opportunities and threats
   - Strategic recommendations overview

2. **Market Size and Growth Analysis:**
   - Total addressable market (TAM)
   - Serviceable available market (SAM)
   - Market growth rate and trends
   - Historical performance and future projections
   - Market maturity stage assessment

3. **Competitive Landscape:**
   - Market structure and concentration
   - Key players and market share analysis
   - Competitive positioning map
   - Strengths and weaknesses of major competitors
   - Barriers to entry and competitive moats

4. **Customer Analysis:**
   - Target customer segments and personas
   - Customer needs, pain points, and preferences
   - Buying behavior and decision-making process
   - Price sensitivity and value drivers
   - Channel preferences and accessibility

5. **Industry Trends and Drivers:**
   - Technological disruptions and innovations
   - Regulatory changes and compliance requirements
   - Economic factors affecting the market
   - Social and cultural shifts
   - Environmental and sustainability considerations

6. **SWOT Analysis:**
   - Market strengths and advantages
   - Weaknesses and challenges
   - Emerging opportunities
   - Potential threats and risks

7. **Strategic Recommendations:**
   - Market entry strategies
   - Positioning and differentiation opportunities
   - Investment priorities and resource allocation
   - Risk mitigation strategies
   - Success metrics and KPIs to track

Include data sources, methodology notes, and confidence levels for key findings where applicable.
```

## Example Input

```markdown
Industry/market: Electric vehicle charging infrastructure
Geographic focus: United States
Time frame: Current market analysis with 5-year forecast
Analysis purpose: Investment decision for EV charging network expansion
Target segment: Commercial and residential charging solutions

Key Analysis Areas:
- Market size: Number of charging stations and revenue potential
- Competitive landscape: ChargePoint, EVgo, Electrify America, Tesla Supercharger
- Customer behavior: EV adoption rates, charging patterns, location preferences
- Technology trends: Fast charging, wireless charging, smart grid integration
- Regulatory environment: Federal incentives, state mandates, utility regulations

Specific Questions:
- What's the optimal geographic expansion strategy?
- How will autonomous vehicles impact charging infrastructure needs?
- What partnership opportunities exist with utilities and retailers?
```

## Example Output

```markdown
# Electric Vehicle Charging Infrastructure Market Analysis

## Executive Summary

**Market Attractiveness: HIGH**

The US EV charging infrastructure market presents a compelling investment opportunity driven by accelerating EV adoption, supportive government policies, and massive infrastructure funding. The market is expected to grow from $7.4B in 2023 to $26.8B by 2028 (CAGR: 29.2%).

**Key Opportunities:**
1. **Rural/Suburban Expansion**: 67% of charging gaps exist outside major metro areas
2. **Commercial Fleet Solutions**: B2B market growing 3x faster than consumer segment  
3. **Multi-Family Housing**: 35% of EV owners live in apartments with limited charging access

**Top Recommendation**: Focus on strategic partnerships with grocery chains and employers for destination charging, targeting suburban markets with high EV adoption but limited infrastructure.

---

## Market Size and Growth Analysis

### Total Addressable Market (TAM)
- **2023**: $7.4 billion (18,500 public fast charging stations)
- **2028**: $26.8 billion (85,000+ stations projected)
- **Growth Rate**: 29.2% CAGR

### Market Segmentation by Revenue:
- **DC Fast Charging**: 68% of market revenue
- **Level 2 Commercial**: 24% of market revenue  
- **Residential Solutions**: 8% of market revenue

### Geographic Distribution:
- **California**: 31% of installed capacity
- **Texas, Florida, New York**: 27% combined
- **Remaining 46 states**: 42% (major growth opportunity)

### Market Maturity: **Early Growth Stage**
Currently in rapid expansion phase with significant infrastructure gaps and evolving technology standards.

---

## Competitive Landscape

### Market Structure: **Fragmented but Consolidating**
- Top 4 players control 58% of public charging market
- 200+ smaller regional operators
- High M&A activity (12 major acquisitions in 2023)

### Key Player Analysis:

**1. Tesla Supercharger Network**
- **Market Share**: 23% of fast charging stations
- **Strengths**: Reliability, brand loyalty, integrated ecosystem
- **Weaknesses**: Limited to Tesla vehicles (changing with NACS adoption)
- **Strategy**: Opening network to other brands, aggressive expansion

**2. ChargePoint**
- **Market Share**: 18% of total charging ports
- **Strengths**: Software platform, B2B relationships, scalable model
- **Weaknesses**: Hardware reliability issues, complex pricing
- **Strategy**: Focus on fleet and workplace charging

**3. Electrify America**
- **Market Share**: 12% of fast charging market
- **Strengths**: VW backing, premium locations, consistent branding
- **Weaknesses**: Limited geographic coverage, high costs
- **Strategy**: Doubling network size by 2025

**4. EVgo**
- **Market Share**: 8% of fast charging market
- **Strengths**: Urban focus, grocery partnerships, fast deployment
- **Weaknesses**: Limited rural presence, customer acquisition costs
- **Strategy**: Subscription models, autonomous vehicle preparation

### Competitive Positioning Map:
```

High Reliability ↑
                 │    Tesla
                 │
                 │ ChargePoint
Low Cost ←───────┼───────→ Premium
                 │  EVgo
                 │
                 │ Regional Players
Low Reliability ↓

```

---

## Customer Analysis

### Primary Customer Segments:

**1. Individual EV Owners (B2C)**
- **Size**: 3.1 million EV owners, growing 40% annually
- **Pain Points**: Range anxiety, charging speed, reliability
- **Preferences**: Convenient locations, predictable pricing, mobile app integration
- **Willingness to Pay**: $0.30-0.45/kWh for fast charging

**2. Commercial Fleet Operators (B2B)**
- **Size**: 15,000+ fleets electrifying (delivery, rideshare, corporate)
- **Pain Points**: Depot charging costs, route planning, uptime requirements
- **Preferences**: Managed services, guaranteed availability, custom pricing
- **Contract Value**: $50K-500K annually per fleet

**3. Property Owners/Managers**
- **Size**: 2.5 million commercial properties, 20 million multi-family units
- **Pain Points**: Installation costs, utility coordination, maintenance
- **Preferences**: Turnkey solutions, revenue sharing, tenant satisfaction
- **Revenue Potential**: $5K-25K annual revenue per property

### Customer Journey Analysis:
1. **Awareness**: 73% discover through mobile apps/navigation
2. **Consideration**: Price and location are top factors (87% of decisions)
3. **Trial**: First experience determines loyalty (62% stick with first network used)
4. **Loyalty**: Subscription models increase usage 3.2x

---

## Industry Trends and Drivers

### Technology Trends:
- **Ultra-Fast Charging**: 350kW+ stations reducing charge time to 10-15 minutes
- **Wireless Charging**: Pilot programs for autonomous vehicles and static charging
- **V2G Integration**: Vehicle-to-grid technology creating revenue opportunities
- **Smart Charging**: AI-optimized charging reducing grid strain and costs

### Regulatory Drivers:
- **IIJA Funding**: $7.5B federal investment in charging infrastructure
- **State Mandates**: 12 states requiring 100% EV sales by 2035
- **NEVI Program**: National standards ensuring interoperability and accessibility
- **Utility Incentives**: $2.1B in utility investments planned through 2025

### Economic Factors:
- **EV Price Parity**: Expected by 2025-2027 accelerating adoption
- **Electricity Costs**: Regional variations creating profit margin opportunities
- **Real Estate Costs**: Premium for charging-enabled properties increasing

---

## SWOT Analysis

### Strengths:
- **Government Support**: Unprecedented federal and state funding
- **Growing Demand**: EV sales doubling every 2 years
- **Technology Advancement**: Faster, more reliable charging solutions
- **Network Effects**: Early infrastructure creates competitive moats

### Weaknesses:
- **High Capital Requirements**: $50K-150K per fast charging station
- **Regulatory Complexity**: Varying state and local requirements
- **Grid Limitations**: Utility infrastructure constraints in some areas
- **Skilled Labor Shortage**: Installation and maintenance workforce gaps

### Opportunities:
- **Rural Markets**: 67% of counties have <3 public charging stations
- **Commercial Partnerships**: Retailers, employers, municipalities seeking charging
- **Energy Services**: Grid balancing, demand response, storage integration
- **International Expansion**: Technology and operational expertise exportable

### Threats:
- **Technology Disruption**: Battery improvements reducing charging frequency needs
- **Utility Competition**: Electric companies entering market directly
- **Economic Downturn**: Reduced EV adoption and infrastructure investment
- **Standardization Risk**: Competing charging standards creating fragmentation

---

## Strategic Recommendations

### 1. Geographic Expansion Strategy: **Hub-and-Spoke Model**
- **Primary Hubs**: Target top 50 metropolitan areas with highest EV adoption
- **Secondary Spokes**: Connect hubs with corridor charging every 50 miles
- **Priority Markets**: Austin, Denver, Seattle, Atlanta (high growth, underserved)

### 2. Partnership Strategy: **Retail Integration**
- **Grocery Chains**: 15-45 minute dwell time matches charging needs
- **Shopping Centers**: Destination charging during extended stays
- **Employers**: Workplace charging for 70% of EV owners who work in offices

### 3. Technology Investment Priorities:
1. **Reliability Systems**: 99%+ uptime through predictive maintenance
2. **Payment Integration**: Seamless mobile payments and subscription options
3. **Grid Integration**: Smart charging and energy storage capabilities

### 4. Customer Acquisition Focus:
- **B2B First**: Higher margins and longer contracts provide stable revenue
- **Fleet Partnerships**: Early EV adopters need immediate charging solutions
- **White-Label Services**: Enable property owners to offer branded charging

### Key Performance Indicators:
- **Network Utilization**: Target 25%+ average utilization by Year 2
- **Customer Acquisition Cost**: <$150 per active user
- **Revenue per Station**: $50K+ annually for fast charging locations
- **Market Share**: Capture 8-12% of local market within 3 years

### Risk Mitigation:
- **Technology Hedge**: Multiple charging standards support during transition
- **Regulatory Compliance**: Early engagement with local authorities and utilities
- **Financial Flexibility**: Phased rollout allowing strategy adjustments
```

## Variations

### Competitive Intelligence Focus

Deep-dive analysis of specific competitors, their strategies, strengths, weaknesses, and market positioning for strategic planning.

### Customer Research Analysis

Detailed customer behavior analysis, persona development, and market segmentation based on demographics, psychographics, and usage patterns.

### Technology Trend Assessment

Focus on emerging technologies, disruptions, and innovation trends that could impact the market landscape and business strategies.

## Tips

- Use multiple data sources and triangulate findings for accuracy
- Include both quantitative data and qualitative insights for comprehensive analysis
- Consider macro-economic factors that could influence market dynamics
- Validate assumptions with primary research when possible
- Update analysis regularly as markets evolve rapidly

## Related Prompts

- [Strategic Planner](./strategic-planner.md) - For developing business strategies
- [Research Synthesizer](../analysis/research-synthesizer.md) - For processing research data

## Tags

`market-research` `competitive-analysis` `business-intelligence` `strategy` `industry-analysis` `customer-research` `market-sizing` `investment-analysis`
```

#### ✨ Prompt: Meeting Summary Generator

```
## Description

Creates comprehensive meeting summaries including key decisions, action items, attendee information, and follow-up tasks. Transforms meeting notes or recordings into structured, actionable summaries that can be distributed to stakeholders.

## Usage

Provide meeting notes, transcript, or key discussion points. Include meeting context, attendees, and any specific format requirements. Works for various meeting types including status updates, planning sessions, client meetings, and board meetings.

## Prompt

```markdown
Create a comprehensive meeting summary from the following information:

**Meeting Details:**
- **Date & Time:** [Meeting date and duration]
- **Meeting Type:** [Status update / Planning / Client meeting / Board meeting / Other]
- **Attendees:** [List of participants and their roles]
- **Meeting Purpose:** [Primary objective of the meeting]

**Meeting Content:**
[Provide meeting notes, transcript, or key discussion points here]

**Summary Requirements:**
- **Format:** [Email summary / Document / Bullet points / Detailed report]
- **Target Audience:** [Team members / Executives / Clients / All attendees]
- **Length:** [Brief overview / Detailed summary / Comprehensive report]
- **Follow-up needs:** [Action items tracking / Next meeting scheduling / Progress monitoring]

Please structure the summary with:

1. **Meeting Overview**
   - Purpose and context
   - Key attendees and their roles
   - Meeting duration and format

2. **Key Decisions Made**
   - Important resolutions and agreements
   - Approved proposals or changes
   - Rejected or deferred items

3. **Discussion Highlights**
   - Main topics covered
   - Different viewpoints presented
   - Concerns or challenges raised

4. **Action Items**
   - Specific tasks assigned
   - Responsible parties
   - Due dates and deadlines
   - Success criteria

5. **Next Steps**
   - Follow-up meetings scheduled
   - Dependencies and blockers
   - Escalation needs

6. **Parking Lot**
   - Topics to revisit later
   - Ideas for future consideration
   - Unresolved questions

**Additional Requirements:**
[Any specific formatting, distribution lists, or follow-up protocols]
```

## Example Input

```markdown
**Meeting Details:**
- **Date & Time:** March 15, 2024, 2:00-3:30 PM EST
- **Meeting Type:** Quarterly Planning Session
- **Attendees:** 
  - Sarah Chen (Product Manager)
  - Mike Rodriguez (Engineering Lead)
  - Alex Kim (Marketing Director)
  - Jordan Thompson (Sales Manager)
  - Chris Wong (Designer)
- **Meeting Purpose:** Plan Q2 product roadmap and marketing initiatives

**Meeting Content:**
Sarah opened by reviewing Q1 performance - exceeded user growth by 15% but behind on revenue targets. Mike discussed technical debt issues affecting new feature development timeline. Alex presented market research showing demand for mobile app priority. Jordan shared feedback from enterprise clients requesting advanced analytics. Chris showed new UI designs for dashboard redesign. 

Key discussions:
- Should we prioritize mobile app development or dashboard redesign?
- Technical debt cleanup will require 3 weeks of dev time
- Enterprise analytics feature could bring $200K ARR but needs 2 month dev time
- Marketing budget increase needed for Q2 campaign
- Hiring 2 more developers by end of Q2

Decisions made:
- Move forward with dashboard redesign in April
- Delay mobile app to Q3
- Allocate 3 weeks in early April for technical debt
- Approve additional $50K marketing budget
- Start hiring process for 2 developers immediately

Action items discussed:
Sarah to update product roadmap by March 20
Mike to create technical debt cleanup plan
Alex to draft Q2 marketing campaign proposal
Jordan to gather detailed enterprise requirements
Chris to finalize dashboard designs
```

## Example Output

```markdown
# Q2 Planning Meeting Summary

**Meeting Date:** March 15, 2024 | **Duration:** 1.5 hours  
**Meeting Type:** Quarterly Planning Session  
**Meeting Lead:** Sarah Chen (Product Manager)

## Attendees
- **Sarah Chen** - Product Manager (Meeting Lead)
- **Mike Rodriguez** - Engineering Lead
- **Alex Kim** - Marketing Director  
- **Jordan Thompson** - Sales Manager
- **Chris Wong** - Designer

---

## Meeting Overview

The team convened to establish Q2 priorities based on Q1 performance and market opportunities. While user growth exceeded targets by 15%, revenue targets were missed, prompting a strategic review of product and marketing initiatives.

---

## Key Decisions Made

### ✅ **Approved Initiatives**
1. **Dashboard Redesign Priority** - Proceed with dashboard redesign in April over mobile app development
2. **Technical Debt Resolution** - Allocate 3 weeks in early April for technical debt cleanup
3. **Marketing Budget Increase** - Approve additional $50K for Q2 marketing campaigns
4. **Team Expansion** - Begin immediate hiring process for 2 additional developers

### ❌ **Deferred Items**
- **Mobile App Development** - Postponed to Q3 to focus on core platform improvements

---

## Discussion Highlights

### Q1 Performance Review
- **Positive:** User growth exceeded targets by 15%
- **Challenge:** Revenue targets not met, requiring strategic adjustment

### Technical Considerations
- Technical debt issues identified as blocking factor for new feature development
- 3-week cleanup period required before major new development
- Engineering capacity constraints affecting timeline

### Market Opportunities
- Market research indicates strong demand for mobile app capabilities
- Enterprise clients requesting advanced analytics features
- Potential $200K ARR from enterprise analytics (2-month development required)

### Resource Requirements
- Additional marketing budget needed to capitalize on Q2 opportunities
- Engineering team expansion critical for meeting Q2-Q3 roadmap

---

## Action Items

| Task | Owner | Due Date | Status |
|------|-------|----------|---------|
| Update product roadmap with Q2 priorities | Sarah Chen | March 20, 2024 | 🔄 In Progress |
| Create technical debt cleanup plan with timeline | Mike Rodriguez | March 22, 2024 | 📋 Assigned |
| Draft Q2 marketing campaign proposal | Alex Kim | March 25, 2024 | 📋 Assigned |
| Gather detailed enterprise analytics requirements | Jordan Thompson | March 27, 2024 | 📋 Assigned |
| Finalize dashboard redesign mockups | Chris Wong | March 20, 2024 | 🔄 In Progress |
| Post job descriptions for developer positions | Sarah Chen | March 18, 2024 | 📋 Assigned |

---

## Next Steps

### Immediate Priorities (Next 2 Weeks)
- Complete Q2 roadmap documentation
- Finalize technical debt cleanup plan
- Begin developer recruitment process

### Q2 Execution Plan
- **April Week 1-3:** Technical debt cleanup
- **April Week 4:** Begin dashboard redesign development
- **May-June:** Dashboard redesign completion and testing

### Follow-up Meetings
- **Weekly standups** every Monday at 10 AM
- **Next planning session** scheduled for April 15, 2024
- **Q2 review meeting** scheduled for June 30, 2024

---

## Parking Lot Items

### Future Consideration
- **Mobile App Development** - Revisit for Q3 planning
- **Enterprise Analytics Suite** - Evaluate after developer hiring complete
- **International Market Expansion** - Research for Q4 planning

### Unresolved Questions
- Budget allocation for potential enterprise analytics development
- Timeline for Q3 mobile app development kickoff
- Long-term hiring plan beyond Q2 additions

---

## Meeting Effectiveness
- ✅ All key decisions made within scheduled time
- ✅ Clear action items assigned with deadlines
- ✅ Resource conflicts identified and resolved
- 📝 Follow-up: Distribute updated roadmap to stakeholders by March 21

---

*Summary prepared by: Sarah Chen*  
*Distribution: All attendees + Executive Team*  
*Next Meeting: April 15, 2024, 2:00 PM EST*
```

## Variations

- **Client Meeting Summary**: Focus on client needs, proposals, and relationship management
- **Technical Review**: Emphasize technical decisions, architecture, and implementation details
- **Executive Brief**: High-level summary for leadership with key metrics and decisions
- **Project Status**: Focus on project milestones, risks, and resource allocation

## Tips

- Capture decisions separately from discussions to highlight outcomes
- Use clear formatting with headers and bullet points for easy scanning
- Include specific deadlines and ownership for all action items
- Note any dependencies or blockers that could affect timelines
- Distribute summaries within 24 hours of the meeting
- Keep a consistent format for regular meeting types

## Related Prompts

- `email-templates.md` - For distributing meeting summaries via email
- `proposal-writer.md` - For creating detailed proposals from meeting discussions
- `technical-documentation.md` - For documenting technical decisions from meetings

## Tags

`meeting-management` `business-communication` `project-management` `documentation` `follow-up` `action-items`
```

#### ✨ Prompt: Proposal Writer

```
## Description

Creates professional business proposals, project estimates, and formal requests. Generates compelling proposals with clear value propositions, detailed scope, pricing, and terms that win clients and secure approvals.

## Usage

Provide project details, client requirements, and business context. Include information about deliverables, timeline, budget constraints, and competitive landscape. Works for service proposals, project bids, partnership agreements, and internal project requests.

## Prompt

```markdown
Create a professional business proposal for the following opportunity:

**Proposal Type:**
[Service proposal / Project bid / Partnership proposal / Internal project request / RFP response]

**Client/Stakeholder Information:**
- **Organization:** [Client company name and industry]
- **Decision Maker:** [Primary contact and their role]
- **Organization Size:** [Team size, revenue, market position]
- **Current Challenges:** [Problems they're trying to solve]

**Project Overview:**
- **Objective:** [What the client wants to achieve]
- **Scope:** [Detailed description of work to be performed]
- **Deliverables:** [Specific outputs and outcomes expected]
- **Timeline:** [Project duration and key milestones]
- **Budget Range:** [Client's budget expectations or constraints]

**Our Capabilities:**
- **Company Background:** [Your organization's background and expertise]
- **Relevant Experience:** [Similar projects and case studies]
- **Team Members:** [Key personnel and their qualifications]
- **Unique Value Proposition:** [What sets you apart from competitors]

**Proposal Requirements:**
- **Format:** [Formal document / Presentation / Email proposal]
- **Length:** [Brief summary / Detailed proposal / Comprehensive response]
- **Key Sections Needed:** [Executive summary / Technical approach / Pricing / Timeline]
- **Tone:** [Professional / Consultative / Technical / Friendly]

**Additional Context:**
- **Competition:** [Known competitors or alternatives]
- **Decision Criteria:** [How the client will evaluate proposals]
- **Relationship History:** [Previous work or interactions]
- **Special Requirements:** [Compliance, certifications, or specific needs]

Please structure the proposal with:
1. Executive summary with clear value proposition
2. Understanding of client needs and challenges
3. Proposed solution and approach
4. Project timeline and milestones
5. Team qualifications and experience
6. Detailed pricing and payment terms
7. Risk mitigation and contingencies
8. Next steps and call to action
```

## Example Input

```markdown
**Proposal Type:** Service proposal

**Client/Stakeholder Information:**
- **Organization:** GreenTech Manufacturing - sustainable packaging company
- **Decision Maker:** Sarah Johnson, VP of Operations
- **Organization Size:** 200 employees, $50M annual revenue
- **Current Challenges:** Manual inventory management causing stockouts and overstock situations

**Project Overview:**
- **Objective:** Implement automated inventory management system to reduce costs and improve efficiency
- **Scope:** System analysis, software selection, implementation, and staff training
- **Deliverables:** Fully operational inventory system with integration to existing ERP
- **Timeline:** 4-month implementation preferred
- **Budget Range:** $150K-200K total project cost

**Our Capabilities:**
- **Company Background:** TechSolutions Inc. - 15 years of ERP and inventory system implementations
- **Relevant Experience:** 50+ manufacturing inventory projects, including 3 in sustainable packaging
- **Team Members:** Senior project manager, 2 systems analysts, 3 developers
- **Unique Value Proposition:** Industry-specific expertise in sustainable manufacturing

**Proposal Requirements:**
- **Format:** Formal document
- **Length:** Comprehensive response
- **Tone:** Professional and consultative
```

## Example Output

```markdown
# Inventory Management System Implementation Proposal

**Prepared for:** GreenTech Manufacturing  
**Prepared by:** TechSolutions Inc.  
**Date:** [Current Date]  
**Proposal Valid Until:** [30 days from date]

---

## Executive Summary

GreenTech Manufacturing has an opportunity to transform its operations through intelligent inventory management automation. Our proposed solution will reduce inventory holding costs by 25%, eliminate stockouts by 90%, and improve operational efficiency by 35% within six months of implementation.

**Key Benefits:**
- **Cost Savings:** $480K annually through optimized inventory levels
- **Efficiency Gains:** 75% reduction in manual inventory tasks
- **Risk Reduction:** Automated alerts prevent stockouts and overstock situations
- **Scalability:** System grows with your expanding operations

**Investment:** $175,000 total project cost with ROI achieved in 4.3 months

---

## Understanding Your Challenge

Based on our discussions with Sarah Johnson and your operations team, we understand that GreenTech Manufacturing faces critical inventory management challenges:

### Current Pain Points
- **Manual Processes:** Spreadsheet-based tracking leading to human errors
- **Stockout Issues:** 15% of production delays due to material shortages
- **Overstock Costs:** $200K in excess inventory tying up working capital
- **Limited Visibility:** No real-time insights into inventory levels across facilities
- **Integration Gaps:** Disconnected systems creating data silos

### Business Impact
These challenges are resulting in:
- Lost production time valued at $50K monthly
- Customer satisfaction issues from delayed shipments
- Increased carrying costs for excess inventory
- Manual labor costs of 2 FTE positions for inventory management

---

## Proposed Solution

### Comprehensive Inventory Management System

We propose implementing **InventoryMax Pro**, a manufacturing-specific inventory management solution, integrated with your existing SAP ERP system.

#### Core Features
1. **Real-Time Inventory Tracking**
   - RFID and barcode scanning integration
   - Automated stock level monitoring
   - Multi-location inventory visibility

2. **Intelligent Demand Forecasting**
   - AI-powered demand prediction
   - Seasonal trend analysis
   - Integration with production planning

3. **Automated Reordering**
   - Dynamic reorder points based on lead times
   - Supplier integration for automated PO generation
   - Emergency stock level alerts

4. **Advanced Analytics & Reporting**
   - Inventory turnover optimization
   - Cost analysis and reporting
   - KPI dashboards for management

#### System Integration
- **SAP ERP Integration:** Seamless data flow with your existing financial systems
- **Production System Link:** Real-time material consumption tracking
- **Supplier Portal:** Direct integration with key suppliers for order automation

---

## Implementation Approach

### Phase 1: Discovery & Design (Weeks 1-3)
**Deliverables:**
- Current state analysis and system audit
- Detailed requirements documentation
- System architecture design
- Integration specifications

**Activities:**
- Stakeholder interviews and process mapping
- Data analysis and migration planning
- Custom configuration requirements
- Testing strategy development

### Phase 2: Configuration & Development (Weeks 4-10)
**Deliverables:**
- Configured InventoryMax Pro system
- Custom integrations with SAP ERP
- Data migration scripts and procedures
- User interface customizations

**Activities:**
- System configuration based on requirements
- Custom development for specific workflows
- Integration development and testing
- Initial data migration and validation

### Phase 3: Testing & Training (Weeks 11-14)
**Deliverables:**
- Fully tested system ready for production
- Comprehensive user training program
- System documentation and procedures
- Go-live readiness assessment

**Activities:**
- User acceptance testing with your team
- Staff training sessions (40 hours total)
- Documentation creation and review
- Production cutover planning

### Phase 4: Go-Live & Support (Weeks 15-16)
**Deliverables:**
- Successful production deployment
- Post-implementation optimization
- 30-day hyper-care support
- Project closure documentation

**Activities:**
- Production system deployment
- Real-time monitoring and issue resolution
- Performance optimization and tuning
- Knowledge transfer to internal team

---

## Project Timeline

```

Weeks 1-3:   Discovery & Design        ████████████
Weeks 4-10:  Configuration & Development ████████████████████████████
Weeks 11-14: Testing & Training        ████████████
Weeks 15-16: Go-Live & Support         ████████

```

**Key Milestones:**
- Week 3: Requirements approval and design sign-off
- Week 10: System configuration complete and ready for testing
- Week 14: User acceptance testing complete
- Week 16: Full production deployment and project closure

---

## Team Qualifications

### Project Leadership
**Mike Chen, Senior Project Manager**
- 12 years inventory management implementations
- PMP certified with manufacturing expertise
- Led 25+ successful ERP integration projects

**Lisa Rodriguez, Lead Systems Analyst**
- 8 years InventoryMax Pro specialization
- SAP integration expert
- Manufacturing process optimization background

### Development Team
**David Park, Senior Developer**
- 10 years ERP integration experience
- SAP certified integration specialist
- Previous GreenTech industry experience

**Jennifer Wu, Systems Developer**
- 6 years manufacturing systems development
- User interface design specialist
- Training and documentation expert

### Quality Assurance
**Robert Kim, QA Lead**
- 7 years testing in manufacturing environments
- Automation and performance testing expert
- User acceptance testing facilitation

---

## Investment & Pricing

### Total Project Investment: $175,000

| Component | Description | Cost |
|-----------|-------------|------|
| **Software Licensing** | InventoryMax Pro annual license (200 users) | $45,000 |
| **Implementation Services** | Configuration, integration, and deployment | $85,000 |
| **Training & Documentation** | User training and system documentation | $25,000 |
| **Data Migration** | Historical data transfer and validation | $15,000 |
| **Project Management** | Dedicated project management and coordination | $20,000 |

### Payment Schedule
- **25% ($43,750)** - Contract signing and project initiation
- **25% ($43,750)** - Completion of Phase 1 (Discovery & Design)
- **35% ($61,250)** - Completion of Phase 2 (Configuration & Development)
- **15% ($26,250)** - Go-live and project completion

### Ongoing Costs (Year 2+)
- Annual software maintenance: $13,500/year
- Optional premium support: $8,000/year

---

## Return on Investment

### Year 1 Benefits
- **Inventory Reduction:** $200K working capital released
- **Stockout Prevention:** $180K in avoided production delays
- **Labor Savings:** $100K in manual process automation
- **Total Year 1 Benefits:** $480K

### ROI Calculation
- **Initial Investment:** $175K
- **Annual Benefits:** $480K
- **Payback Period:** 4.3 months
- **3-Year ROI:** 823%

---

## Risk Mitigation

### Technical Risks
**Data Migration Complexity**
- *Mitigation:* Comprehensive data audit and automated migration tools
- *Contingency:* Parallel system operation during transition period

**Integration Challenges**
- *Mitigation:* Dedicated SAP integration specialist on team
- *Contingency:* Phased integration approach with rollback procedures

### Business Risks
**User Adoption**
- *Mitigation:* Extensive training program and change management support
- *Contingency:* Extended support period and additional training sessions

**Timeline Delays**
- *Mitigation:* Conservative timeline with built-in buffers
- *Contingency:* Dedicated resource allocation and escalation procedures

---

## Why Choose TechSolutions Inc.

### Proven Track Record
- **50+ successful inventory implementations** in manufacturing
- **98% client satisfaction rate** with on-time, on-budget delivery
- **$50M+ in client cost savings** achieved through our implementations

### Industry Expertise
- **3 previous projects** in sustainable packaging industry
- **Deep understanding** of GreenTech's unique challenges
- **Certified partnership** with InventoryMax Pro vendor

### Comprehensive Support
- **Dedicated project team** throughout implementation
- **24/7 support** during go-live period
- **Long-term partnership** approach beyond project completion

---

## Next Steps

### Immediate Actions
1. **Proposal Review:** We recommend scheduling a detailed review meeting within 5 business days
2. **Reference Calls:** We'll arrange calls with 2-3 similar manufacturing clients
3. **Technical Deep Dive:** Optional technical session with your IT team

### Decision Timeline
- **Proposal Questions Due:** [Date + 1 week]
- **Final Proposal Presentation:** [Date + 2 weeks]
- **Contract Award Decision:** [Date + 3 weeks]
- **Project Kickoff:** [Date + 4 weeks]

### Contact Information
**Primary Contact:** Mike Chen, Project Manager  
📧 mike.chen@techsolutions.com  
📞 (555) 123-4567  

**Business Development:** Sarah Williams  
📧 sarah.williams@techsolutions.com  
📞 (555) 123-4568  

---

## Appendices

### Appendix A: Technical Specifications
[Detailed system requirements and architecture diagrams]

### Appendix B: Case Studies
[3 relevant manufacturing implementation success stories]

### Appendix C: Project Team Resumes
[Detailed qualifications and experience of key team members]

### Appendix D: References
[Contact information for 5 recent manufacturing clients]

---

*This proposal is confidential and proprietary to TechSolutions Inc. All information contained herein is subject to the terms of our mutual non-disclosure agreement.*

**Proposal Reference:** PROP-GT-2024-001  
**Valid Until:** [30 days from submission date]
```

## Variations

- **RFP Response**: Structured response to formal request for proposals
- **Partnership Proposal**: Business partnership and collaboration agreements
- **Internal Project**: Proposals for internal initiatives and budget requests
- **Vendor Selection**: Proposals for selecting and working with external vendors

## Tips

- Lead with client benefits and value proposition, not features
- Include specific metrics and quantifiable outcomes
- Address potential objections proactively in the proposal
- Use case studies and references relevant to the client's industry
- Make pricing transparent with clear payment terms
- Include realistic timelines with milestone-based deliverables
- End with clear, specific next steps and deadlines

## Related Prompts

- `meeting-summary.md` - For documenting proposal discussions and feedback
- `email-templates.md` - For proposal follow-up communications
- `technical-documentation.md` - For detailed technical specifications

## Tags

`business-development` `proposals` `sales` `project-management` `client-communication` `pricing`
```

#### ✨ Prompt: Strategic Planner

```
## Description

This prompt helps you develop comprehensive business strategies, strategic plans, and long-term roadmaps with clear objectives, actionable initiatives, and measurable outcomes.

## Usage

Perfect for business planning, strategic reviews, market entry strategies, digital transformation, organizational planning, and creating actionable roadmaps for achieving business goals.

## Prompt

```markdown
You are an expert strategic planning consultant with deep experience in business strategy development. I need help creating a comprehensive strategic plan that drives business growth and competitive advantage.

**Strategic Planning Context:**
- Organization: [COMPANY_TYPE_AND_SIZE]
- Industry: [INDUSTRY_SECTOR]
- Current position: [MARKET_POSITION_AND_STATUS]
- Planning horizon: [1_YEAR/3_YEAR/5_YEAR_PLAN]
- Primary objective: [GROWTH/TURNAROUND/EXPANSION/DIGITAL_TRANSFORMATION]

**Current Situation:**
- Business model: [HOW_YOU_MAKE_MONEY]
- Revenue: [CURRENT_REVENUE_AND_TRENDS]
- Key challenges: [MAIN_OBSTACLES_FACING]
- Competitive position: [MARKET_STANDING]
- Resources available: [BUDGET/TEAM/CAPABILITIES]

**Strategic Goals:**
- Financial targets: [REVENUE/PROFIT_GOALS]
- Market objectives: [MARKET_SHARE/EXPANSION_GOALS]
- Operational goals: [EFFICIENCY/QUALITY_TARGETS]
- Innovation priorities: [NEW_PRODUCTS/TECHNOLOGIES]
- Organizational development: [TALENT/CULTURE_GOALS]

**Key Constraints:**
- Budget limitations: [FINANCIAL_CONSTRAINTS]
- Time constraints: [URGENT_DEADLINES]
- Resource constraints: [PEOPLE/TECHNOLOGY_LIMITS]
- Regulatory requirements: [COMPLIANCE_CONSIDERATIONS]
- Market conditions: [ECONOMIC/COMPETITIVE_FACTORS]

Please develop a comprehensive strategic plan including:

1. **Executive Summary:**
   - Strategic vision and mission alignment
   - Key strategic priorities and themes
   - Success metrics and expected outcomes
   - Investment requirements and timeline

2. **Situational Analysis:**
   - SWOT analysis (Strengths, Weaknesses, Opportunities, Threats)
   - Competitive landscape assessment
   - Market trends and industry dynamics
   - Internal capabilities and gaps

3. **Strategic Framework:**
   - Strategic vision and positioning
   - Core value propositions
   - Competitive strategy (cost leadership, differentiation, niche)
   - Growth strategy (organic, acquisition, partnerships)

4. **Strategic Initiatives:**
   - 3-5 major strategic initiatives
   - Detailed action plans for each initiative
   - Resource requirements and budgets
   - Timeline and key milestones
   - Success metrics and KPIs

5. **Implementation Roadmap:**
   - Phased implementation approach
   - Quick wins vs. long-term investments
   - Dependencies and critical path analysis
   - Risk assessment and mitigation plans
   - Change management considerations

6. **Financial Projections:**
   - Revenue forecasts by initiative
   - Investment requirements and payback periods
   - Break-even analysis and ROI calculations
   - Cash flow implications and funding needs

7. **Governance and Monitoring:**
   - Strategic review processes
   - Performance tracking and reporting
   - Decision-making frameworks
   - Course correction mechanisms

Ensure the strategy is realistic, actionable, and aligned with available resources while positioning for sustainable competitive advantage.
```

## Example Input

```markdown
Organization: Mid-size SaaS company (150 employees, $25M ARR)
Industry: Project management software for creative agencies
Current position: Growing but facing increased competition from larger players
Planning horizon: 3-year strategic plan
Primary objective: Accelerate growth and defend market position

Business model: Subscription SaaS ($99-499/month per agency)
Revenue: $25M ARR, 15% growth rate (down from 25% last year)
Key challenges: Customer acquisition costs rising, larger competitors entering niche
Competitive position: #3 in creative agency project management space
Resources available: $5M budget, strong product team, loyal customer base

Financial targets: Reach $75M ARR, improve margins to 25%
Market objectives: Maintain top 3 position, expand to adjacent markets
Operational goals: Reduce churn by 30%, improve NPS to 70+
Innovation priorities: AI features, mobile app, integrations platform
Organizational development: Double team size, improve retention

Budget limitations: Limited marketing spend vs. competitors
Time constraints: Need to move fast before market consolidates
Resource constraints: Engineering team at capacity
Market conditions: Economic uncertainty affecting customer budgets
```

## Example Output

```markdown
# Strategic Plan 2024-2027: Creative Agency SaaS Growth Strategy

## Executive Summary

**Strategic Vision:** Become the indispensable operating system for creative agencies by 2027, powering their entire workflow from client acquisition to project delivery.

**Core Strategy:** Defend and expand market position through product innovation, customer success excellence, and strategic market expansion while maintaining operational efficiency.

**Key Strategic Priorities:**
1. **Product Innovation Leadership** - AI-powered features and platform expansion
2. **Customer Success Excellence** - Reduce churn, increase expansion revenue  
3. **Adjacent Market Expansion** - Marketing agencies and consultancies
4. **Operational Excellence** - Scale infrastructure and team efficiently

**Expected Outcomes:**
- **Revenue**: $75M ARR by 2027 (3x growth)
- **Market Position**: Maintain top 3, expand TAM by 40%
- **Profitability**: 25% operating margins (vs. 15% today)
- **Team**: Scale to 300 employees with 90%+ retention

**Total Investment**: $15M over 3 years ($5M annually)

---

## Situational Analysis

### SWOT Analysis

**Strengths:**
- Deep domain expertise in creative agency workflows
- High customer satisfaction (NPS: 58) and low voluntary churn
- Strong product-market fit in core segment
- Agile development and innovation capabilities
- Experienced leadership team with industry connections

**Weaknesses:**
- Limited marketing budget vs. well-funded competitors
- Engineering team capacity constraints
- Narrow market focus creates dependency risk
- Limited enterprise sales capabilities
- Lack of advanced analytics and AI features

**Opportunities:**
- Adjacent markets (marketing agencies, consultancies) worth $2B TAM
- AI/automation features high demand from customers
- Integration platform could create network effects
- Remote work trends increasing demand for collaboration tools
- Potential acquisition targets in complementary spaces

**Threats:**
- Well-funded competitors (Monday.com, Asana) entering niche
- Economic downturn reducing customer budgets
- Larger platforms adding creative-specific features
- Customer consolidation reducing total addressable accounts
- Talent acquisition challenges in competitive market

### Competitive Landscape
- **Monday.com**: Aggressive expansion, strong marketing, but generic features
- **Asana**: Enterprise focus, missing creative-specific functionality  
- **Specialized tools**: Fragmented but innovation in AI and automation
- **New entrants**: VC-funded startups targeting creative workflows

---

## Strategic Framework

### Strategic Vision
"Empower creative agencies to focus on what they do best - creating amazing work - by handling everything else seamlessly."

### Value Proposition Evolution:
- **Current**: Best project management for creative agencies
- **Future**: Complete business operating system for creative services

### Competitive Strategy: **Focused Differentiation**
- Maintain deep specialization in creative workflows
- Innovate faster than generalist competitors in niche features
- Build switching costs through platform integration and data

### Growth Strategy: **Defend and Expand**
1. **Defend core market** through product excellence and customer success
2. **Expand TAM** into adjacent creative services markets
3. **Platform strategy** to increase stickiness and reduce churn

---

## Strategic Initiatives

### Initiative 1: AI-Powered Creative Workflow Platform
**Objective**: Lead market in AI-enhanced creative project management

**Key Projects:**
- AI brief analysis and project scoping (Q2 2024)
- Automated resource allocation and timeline optimization (Q4 2024)  
- Creative asset organization and retrieval system (Q2 2025)
- Predictive project health scoring (Q4 2025)

**Investment**: $6M over 3 years (ML team, data infrastructure)
**Success Metrics**: 40% feature adoption, 15% improvement in project efficiency
**ROI Projection**: $20M incremental ARR from premium AI features

### Initiative 2: Customer Success & Expansion Engine
**Objective**: Reduce churn to <5% annually, increase expansion revenue 50%

**Key Projects:**
- Customer health scoring and intervention system (Q1 2024)
- Dedicated customer success team expansion (Q2 2024)
- Usage analytics and optimization recommendations (Q3 2024)
- Advanced onboarding and certification programs (Q1 2025)

**Investment**: $3M (CSM team, tooling, analytics platform)
**Success Metrics**: Churn <5%, NPS >70, expansion revenue +50%
**ROI Projection**: $15M retained ARR, $10M expansion revenue

### Initiative 3: Adjacent Market Expansion  
**Objective**: Capture 10% of marketing agency and consultancy markets

**Key Projects:**
- Marketing agency workflow research and feature development (Q2 2024)
- Consultancy-specific templates and integrations (Q4 2024)
- Vertical-specific go-to-market strategies (Q1 2025)
- Partnership channel development (Q3 2025)

**Investment**: $4M (product development, sales expansion, marketing)
**Success Metrics**: 500+ customers in new verticals, $15M new market ARR
**ROI Projection**: $25M ARR from expanded TAM

### Initiative 4: Integration Platform & Ecosystem
**Objective**: Create network effects and increase switching costs

**Key Projects:**
- Open API and developer documentation (Q3 2024)
- Marketplace for integrations and templates (Q1 2025)
- Partner program for agencies and vendors (Q3 2025)
- Data synchronization and workflow automation (Q4 2025)

**Investment**: $2M (platform development, partner support)
**Success Metrics**: 50+ active integrations, 20% usage increase
**ROI Projection**: 25% reduction in churn, 15% pricing premium

---

## Implementation Roadmap

### Year 1 (2024): Foundation & Defense
**Q1-Q2**: Customer success expansion, AI MVP development
**Q3-Q4**: Integration platform launch, market research for expansion

**Key Milestones:**
- Hire 15 customer success and engineering roles
- Launch AI brief analysis feature
- Reduce churn to 7% (from 10%)
- Complete market research for adjacent verticals

**Budget**: $5M (60% product, 25% customer success, 15% market research)

### Year 2 (2025): Innovation & Expansion  
**Q1-Q2**: Marketing agency vertical launch, advanced AI features
**Q3-Q4**: Consultancy market entry, platform marketplace

**Key Milestones:**
- Capture 200 marketing agency customers
- Launch integration marketplace with 25+ partners
- Achieve $45M ARR (80% growth)
- Expand team to 225 employees

**Budget**: $5M (50% product development, 30% sales/marketing, 20% operations)

### Year 3 (2027): Scale & Leadership
**Q1-Q2**: Advanced analytics platform, enterprise features
**Q3-Q4**: M&A opportunities, international expansion consideration

**Key Milestones:**
- Reach $75M ARR target
- Achieve 25% operating margins
- Market leadership in AI-powered creative project management
- Platform with 50+ integrations and strong network effects

**Budget**: $5M (40% platform scaling, 30% market expansion, 30% M&A/strategic)

---

## Financial Projections

### Revenue Forecast:
- **2024**: $35M ARR (40% growth)
- **2025**: $52M ARR (49% growth)  
- **2027**: $75M ARR (44% growth)

### Revenue Breakdown by 2027:
- **Core Market**: $45M (existing customer expansion + new creative agencies)
- **Adjacent Markets**: $20M (marketing agencies, consultancies)
- **Platform Revenue**: $10M (integrations, marketplace, premium features)

### Investment & Returns:
- **Total Investment**: $15M over 3 years
- **Incremental ARR**: $50M by 2027
- **ROI**: 3.3x return on strategic investments
- **Operating Margin**: 25% by 2027 (vs. 15% baseline)

### Cash Flow Analysis:
- **Break-even**: Q3 2025 on incremental investments
- **Cumulative ROI**: Positive by Q1 2026
- **Funding Requirements**: Covered by existing cash flow and $5M annual budget

---

## Governance and Monitoring

### Strategic Review Process:
- **Monthly**: Initiative progress reviews with leadership team
- **Quarterly**: Board strategic updates and metric review
- **Semi-Annual**: Deep strategy assessment and course corrections
- **Annual**: Comprehensive strategic plan review and refresh

### Key Performance Indicators:

**Financial KPIs:**
- ARR growth rate (target: >40% annually)
- Operating margin improvement (target: 25% by 2027)
- Customer acquisition cost and payback period
- Expansion revenue rate (target: >50% increase)

**Product KPIs:**
- Feature adoption rates for AI and new capabilities
- Time-to-value for new customers
- Integration usage and platform engagement
- Customer satisfaction and NPS scores

**Market KPIs:**
- Market share in core and adjacent segments
- Win rates vs. specific competitors
- Brand awareness and consideration metrics
- Partner ecosystem growth and engagement

### Risk Monitoring:
- **Competitive Response**: Monthly competitor intelligence reports
- **Market Conditions**: Quarterly economic impact assessments
- **Execution Risk**: Initiative milestone tracking and resource allocation
- **Technology Risk**: Platform scalability and security monitoring

### Course Correction Framework:
- **Yellow Flags**: 10% variance from targets triggers enhanced monitoring
- **Red Flags**: 20% variance triggers strategic review and adjustment
- **Strategic Pivots**: Quarterly windows for major strategic shifts
- **Resource Reallocation**: Monthly budget flexibility within initiatives
```

## Variations

### Digital Transformation Strategy

Focus on technology adoption, process digitization, and organizational change management for traditional businesses moving digital.

### Market Entry Strategy

Develop comprehensive plans for entering new geographic markets, customer segments, or product categories.

### Turnaround Strategy

Create recovery plans for struggling businesses, including cost reduction, revenue optimization, and operational restructuring.

## Tips

- Ensure strategies are specific, measurable, and time-bound rather than vague aspirations
- Balance ambitious goals with realistic resource constraints and market conditions
- Include multiple scenarios (best case, worst case, most likely) in planning
- Build in regular review points and adjustment mechanisms for changing conditions
- Focus on a few key strategic priorities rather than trying to do everything

## Related Prompts

- [Market Analysis](./market-analysis.md) - For understanding market dynamics
- [Goal Setter](../productivity/goal-setter.md) - For setting and tracking objectives

## Tags

`strategic-planning` `business-strategy` `strategic-initiatives` `roadmap` `competitive-strategy` `growth-planning` `business-transformation` `strategic-analysis`
```

#### ✨ Prompt: Xianyu Product Description Generator

```
## Description

This prompt helps sellers create compelling, honest, and effective product descriptions for the Xianyu second-hand marketplace platform. It guides users to write descriptions that highlight key features, accurately describe condition, and encourage buyer engagement.

## Usage

Perfect for individuals selling items on Xianyu who want to create attractive listings, improve conversion rates, and reduce potential disputes by ensuring clear communication about product condition and features.

## Prompt

```markdown
请你扮演一位经验丰富的闲鱼资深卖家，根据用户（卖家）提供的商品信息，遵循以下指导原则，生成一段吸引人的闲鱼商品描述：

1.  **开场白要吸睛 (Engaging Opening):** 用一两句有趣或直接点出亮点的开场白抓住潜在买家的眼球。

2.  **突出核心价值 (Highlight Key Value):** 清晰、简洁地介绍商品的核心卖点和主要特点，说明它能为买家带来什么好处。

3.  **品相描述要真实具体 (Accurate & Detailed Condition):** 明确说明商品的新旧程度，对任何瑕疵（即使微小）都要诚实描述，避免后续纠纷。如果商品成色很好，也要强调。

4.  **融入出售原因 (Integrate Reason for Selling):** 如果卖家提供了出售原因，自然地融入描述中，可以增加真实感和人情味。

5.  **价格与价值感 (Price & Value Proposition):** 如果有原价作对比，可以体现性价比。对于期望售价，可以暗示其合理性。

6.  **配件和服务 (Accessories & Services):** 列出包含的配件，说明交易方式。

7.  **语气风格 (Tone & Style):**

    * **友好亲切：** 使用口语化、接地气的语言，就像和朋友聊天一样。

    * **真诚可信：** 避免夸大其词，实事求是。

    * **适当幽默（可选）：** 如果商品和卖家风格适合，可以加入一些轻松幽默的元素。

8.  **结构清晰易读 (Clear Structure):**

    * 适当分段，避免大段文字堆砌。

    * 对于特点、配件等可以考虑编号列出使其更醒目。

9.  **行动呼吁 (Call to Action):** 鼓励买家进行互动，例如："喜欢就别错过啦，快来私聊我吧！"、"欢迎提问，看到会尽快回复！"。

10. **字数适中 (Concise):** 通常几百字以内为宜，重点突出，不冗余。

11. **符合闲鱼平台规范和用户习惯。**

输出格式：一段适合直接复制粘贴到闲鱼 app 商品发布页面（即不使用 Markdown 语法）的商品描述纯文本，在汉语与英语之间、汉语与数字之间插入空格，不包含 emoji。
```

## Example Input

```markdown
商品：iPhone 12 128GB 蓝色
成色：9成新，使用8个月
瑕疵：屏幕有一道几乎看不见的细痕，背面完好
配件：原装充电器、数据线、手机壳
原价：6799元
期望售价：3500元
出售原因：换了新手机
交易方式：闲鱼自动担保交易，可发顺丰
```

## Example Output

```markdown
【超高性价比】iPhone 12 128GB 蓝色版，颜值与性能兼具，让你的数字生活焕然一新！

这台 iPhone 12 仅使用了 8 个月，整体成色 9 成新，爱机如新。机身蓝色依然亮丽，背面完好无划痕。屏幕有一道极细小的痕迹，正常使用几乎察觉不到，特别诚实地告诉大家。

所有功能完全正常，电池健康度 92%，续航给力。A14 芯片运行流畅，玩游戏不卡顿，日常办公娱乐都能轻松应对。

因为最近升级到了 13 Pro，这台 12 就忍痛割爱了。原价 6799 元的机器，现在只要 3500 元就能带回家，真的很划算。

全套包含：
1. 原装充电器
2. 原装数据线
3. 赠送一个八成新的手机壳

支持闲鱼自动担保交易，全国顺丰发货，安全有保障。有任何问题欢迎随时私聊咨询，看到必回！喜欢的朋友别犹豫，这个价格不会等人哦！
```

## Variations

- **Luxury Items**: Focus more on brand authenticity, craftsmanship, and status value
- **Electronics**: Emphasize technical specifications, functionality tests, and battery health
- **Clothing**: Highlight fabric quality, fit details, and styling possibilities
- **Collectibles**: Focus on rarity, condition grading, and investment potential

## Tips

- Be extremely honest about item condition to avoid returns and disputes
- Take time to mention small defects - transparency builds trust
- Use natural language that sounds like real conversation, not corporate marketing
- If you've used the item personally, share authentic experiences with it
- Adjust your tone to match the item's price point and target audience

## Related Prompts

- `marketing-copy-creator.md` - For general marketing copy creation
- `email-templates.md` - For communication with potential buyers
- `product-listing-optimization.md` - For optimizing marketplace listings

## Tags

`e-commerce` `product-descriptions` `second-hand-market` `sales-copy` `xianyu` `taobao` `retail` `chinese-platforms`
```


### 📁 Categoria: Creative

#### ✨ Prompt: Creative Prompts

```
This directory contains prompts for creative and artistic endeavors.

## Categories

- **Brainstorming**: Idea generation and creative thinking
- **Storytelling**: Narrative creation and plot development
- **Visual Arts**: Descriptions for artwork, design concepts
- **Music & Poetry**: Creative expression in various forms
- **Character Development**: Creating compelling characters
- **World Building**: Constructing fictional worlds and settings

## Example Prompts

- `brainstorming-session.md` - Facilitate innovative brainstorming and idea generation
- `story-creator.md` - Generate creative stories and fictional narratives

## Creative Guidelines

- Encourage experimentation and exploration
- Allow for multiple iterations and variations
- Consider different genres, styles, and approaches
- Balance structure with creative freedom

---
*Add your creative prompts to this directory following the template structure.*
```

#### ✨ Prompt: Creative Brainstorming Session

```
## Description

Facilitates innovative brainstorming sessions for generating creative ideas, solutions, and concepts. Uses various ideation techniques to spark creativity and help teams break through mental blocks to find novel approaches.

## Usage

Provide the challenge, problem, or creative brief that needs fresh ideas. Include context about constraints, target audience, and desired outcomes. Works for product development, marketing campaigns, problem-solving, and creative projects.

## Prompt

```markdown
Facilitate a creative brainstorming session for the following challenge:

**Challenge/Brief:**
[Clearly describe the problem, opportunity, or creative challenge to address]

**Context & Background:**
- **Industry/Domain:** [Relevant industry or field]
- **Target Audience:** [Who will benefit from or use the solution]
- **Current Situation:** [Existing solutions, what's been tried before]
- **Success Criteria:** [How to measure if ideas are successful]

**Constraints & Parameters:**
- **Budget:** [Financial limitations or considerations]
- **Timeline:** [Time constraints or deadlines]
- **Resources:** [Available team, tools, or materials]
- **Technical Limitations:** [Technology or platform constraints]
- **Regulatory/Legal:** [Compliance requirements or restrictions]

**Desired Outcomes:**
- **Quantity:** [Number of ideas needed - many options vs. few refined concepts]
- **Quality Level:** [Rough concepts vs. detailed solutions]
- **Innovation Level:** [Incremental improvements vs. breakthrough innovations]
- **Implementation:** [Ideas that are immediately actionable vs. longer-term vision]

**Brainstorming Approach:**
Please use the following ideation techniques:

1. **Traditional Brainstorming**
   - Generate 20+ initial ideas without judgment
   - Build on and combine different concepts
   - Encourage wild and unconventional thinking

2. **SCAMPER Method**
   - **Substitute:** What can be substituted or swapped?
   - **Combine:** What can be combined or merged?
   - **Adapt:** What can be adapted or modified?
   - **Modify/Magnify:** What can be emphasized or enhanced?
   - **Put to other uses:** How else can this be used?
   - **Eliminate:** What can be removed or simplified?
   - **Reverse/Rearrange:** What can be reordered or reversed?

3. **Alternative Perspectives**
   - How would [industry leader/competitor] approach this?
   - What would this look like in a different industry?
   - How would different demographics solve this?
   - What if we had unlimited resources?
   - What if we had severe constraints?

4. **Creative Prompts**
   - What if we started from scratch today?
   - How can we turn this problem into an opportunity?
   - What would the opposite solution look like?
   - What emerging technologies could we leverage?
   - How can we make this 10x better instead of 10% better?

Please organize the output with:
- Initial idea dump (quantity focus)
- Refined concepts (quality focus)  
- Wild cards (breakthrough potential)
- Implementation roadmap for top 3 ideas

**Additional Context:**
[Any specific inspiration, examples to avoid, or particular angles to explore]
```

## Example Input

```markdown
**Challenge/Brief:**
Increase employee engagement and reduce turnover at a mid-sized software company where remote work has led to feelings of isolation and decreased team connection.

**Context & Background:**
- **Industry:** Software development company
- **Target Audience:** 150 remote employees across 5 time zones
- **Current Situation:** 30% annual turnover, low engagement scores, limited team interaction
- **Success Criteria:** Reduce turnover to 15%, increase engagement scores by 40%

**Constraints & Parameters:**
- **Budget:** $50K annual budget for engagement initiatives
- **Timeline:** Implement solutions within 6 months
- **Resources:** HR team of 3, some IT support available
- **Technical Limitations:** Must work across different time zones and tech platforms
- **Regulatory/Legal:** Must comply with employment laws in 8 different states

**Desired Outcomes:**
- **Quantity:** 15-20 actionable ideas
- **Quality Level:** Mix of quick wins and longer-term strategies
- **Innovation Level:** Creative solutions that go beyond typical team-building
- **Implementation:** Balance of immediate and 6-month initiatives
```

## Example Output

```markdown
# Employee Engagement Brainstorming Session Results

## Initial Idea Dump (Quantity Focus)

### Connection & Community Building
1. **Virtual Coffee Roulette** - Random pairing of employees for 15-min video coffee chats
2. **Digital Campfire Stories** - Weekly storytelling sessions about personal experiences
3. **Pet Photo Fridays** - Company-wide pet photo sharing with voting for "Pet of the Week"
4. **Virtual Coworking Spaces** - Always-on video rooms for people who want company while working
5. **Geographic Meetup Groups** - Local in-person gatherings for employees in same cities
6. **Hobby Clubs** - Interest-based groups (photography, cooking, gaming) with dedicated channels
7. **Mentorship Speed Dating** - Quick mentor-mentee matching sessions
8. **Cultural Exchange Program** - Employees share their local culture/traditions

### Recognition & Appreciation
9. **Peer Appreciation Tokens** - Digital currency employees can give each other for recognition
10. **Skills Showcase Theater** - Monthly presentations where employees teach their hobbies
11. **Impact Story Sharing** - Quarterly sharing of how individual work affects customers
12. **Achievement Milestone Celebrations** - Personalized celebrations for work anniversaries, promotions
13. **"Behind the Code" Features** - Highlighting individual contributors and their projects

### Professional Development
14. **Learning Lunch & Learns** - Employee-led sessions on new technologies or skills
15. **Conference Experience Sharing** - Employees attend conferences and share learnings company-wide
16. **Innovation Time** - 10% time for passion projects that could benefit the company
17. **Cross-Department Shadowing** - Virtual shadowing of different roles to understand the business

### Wellness & Work-Life Balance
18. **Wellness Challenges** - Team-based fitness, meditation, or healthy habit challenges
19. **Mental Health Check-ins** - Regular, structured conversations about wellbeing
20. **Flexible Deep Work Hours** - Protected time blocks with no meetings allowed
21. **Vacation Encouragement Program** - Rewards for actually taking time off

## Refined Concepts (Quality Focus)

### 1. The Connection Ecosystem
**Concept:** Multi-layered approach to building relationships
- **Layer 1:** Automated coffee chats with conversation starter prompts
- **Layer 2:** Interest-based virtual clubs meeting monthly
- **Layer 3:** Geographic meetups with company-sponsored activities
- **Layer 4:** Cross-functional project teams for special initiatives

**Implementation:** 
- Start with coffee chat platform (Month 1)
- Launch 5 hobby clubs (Month 2)
- Establish meetup groups in 3+ employee cities (Month 3)
- Create quarterly cross-functional innovation projects (Month 4)

### 2. The Recognition & Growth Engine
**Concept:** Peer-driven recognition system tied to career development
- **Recognition Platform:** Employees give "Impact Points" for help, collaboration, innovation
- **Quarterly Recognition Events:** Celebrate top contributors with personalized rewards
- **Growth Pathways:** Recognition points inform promotion and development opportunities
- **Skill Sharing:** High contributors become mentors and workshop leaders

**Implementation:**
- Build simple recognition platform (Month 1-2)
- Launch first recognition cycle (Month 3)
- Integrate with performance reviews (Month 4-5)
- Establish mentorship programs (Month 6)

### 3. The Belonging & Purpose Initiative
**Concept:** Connect individual work to company mission and personal identity
- **Impact Dashboards:** Show how each person's work affects customer success
- **Personal Branding Support:** Help employees build their professional identity
- **Mission Moments:** Regular sharing of customer success stories tied to employee work
- **Values in Action:** Recognize and celebrate when employees demonstrate company values

**Implementation:**
- Create impact tracking system (Month 1-2)
- Launch monthly mission moments (Month 2)
- Develop personal branding workshops (Month 3-4)
- Establish values recognition program (Month 5)

## Wild Cards (Breakthrough Potential)

### 1. Virtual Reality Office Spaces
Create immersive VR environments where employees can work together in simulated offices, conference rooms, and social spaces. Employees would have avatars and could naturally interact as if in physical proximity.

**Why it's wild:** Requires significant tech investment and adoption curve
**Potential impact:** Could revolutionize remote work experience and become a competitive advantage

### 2. Employee-Led Startup Incubator
Allocate budget and time for employees to develop startup ideas, with company having first option to invest or acquire successful concepts. Creates entrepreneurial energy within the company.

**Why it's wild:** Unusual for software companies to fund internal entrepreneurship
**Potential impact:** Could drive innovation, retention, and potentially new revenue streams

### 3. Global Remote Work Exchange Program
Partner with other remote-first companies to allow employees to temporarily work from their offices worldwide, creating travel and cultural exchange opportunities.

**Why it's wild:** Complex logistics and legal considerations across countries
**Potential impact:** Unique perk that attracts talent and creates global perspective

## Implementation Roadmap - Top 3 Ideas

### Priority 1: Connection Ecosystem (Months 1-4)
**Month 1:**
- Set up coffee chat platform using existing tools (Slack + calendar integration)
- Launch with 50% employee participation target

**Month 2:**
- Survey employees for hobby interests
- Launch 5 virtual clubs (photography, cooking, gaming, fitness, book club)
- Establish club leader volunteer roles

**Month 3:**
- Identify cities with 3+ employees
- Organize first regional meetups with $200 budget per event
- Create meetup planning toolkit for employee organizers

**Month 4:**
- Launch first cross-functional innovation project team
- Set quarterly schedule for new project teams
- Create project showcase presentation format

### Priority 2: Recognition & Growth Engine (Months 2-6)
**Months 2-3:**
- Build simple recognition platform (can use existing tools like Bonusly or build custom Slack integration)
- Define "Impact Points" categories (helpfulness, innovation, collaboration, mentoring)
- Train team leads on recognition best practices

**Months 4-5:**
- Run first quarterly recognition cycle
- Plan personalized rewards ($50-200 range per recipient)
- Integrate recognition data with performance review process

**Month 6:**
- Launch mentorship matching program
- Connect high-performers with mentoring opportunities
- Create growth pathway documentation

### Priority 3: Belonging & Purpose Initiative (Months 3-6)
**Months 3-4:**
- Develop customer impact tracking and dashboard
- Create template for "Mission Moments" storytelling
- Plan monthly customer success story sharing format

**Months 5-6:**
- Launch personal branding workshop series
- Create LinkedIn and professional development resources
- Establish values recognition ceremonies

## Success Metrics & Tracking

### Leading Indicators (Track Monthly)
- Coffee chat participation rate (target: 60%)
- Club membership and activity levels (target: 40% participation)
- Recognition platform usage (target: 80% give recognition monthly)
- Event attendance rates (target: 70% for virtual, 50% for in-person)

### Lagging Indicators (Track Quarterly)
- Employee engagement survey scores (target: 40% improvement)
- Voluntary turnover rate (target: reduce to 15%)
- Internal promotion rate (target: increase by 25%)
- Employee Net Promoter Score (target: reach 50+)

### ROI Calculation
- **Recruitment Cost Savings:** 15% turnover reduction saves ~$450K annually (assuming $30K cost per hire)
- **Productivity Gains:** 20% engagement improvement estimated at $300K annual value
- **Total ROI:** $750K benefits vs. $50K investment = 1500% ROI

This comprehensive approach addresses multiple dimensions of employee engagement while staying within budget constraints and leveraging the distributed team's unique characteristics as strengths rather than obstacles.
```

## Variations

- **Product Innovation**: Focus on new product ideas and feature development
- **Marketing Campaign**: Creative concepts for advertising and brand campaigns
- **Problem Solving**: Structured approach to solving specific business challenges
- **Process Improvement**: Ideas for optimizing workflows and operations

## Tips

- Start with quantity over quality to avoid self-censoring
- Build on others' ideas rather than just generating new ones
- Use constraints as creative catalysts rather than limitations
- Include both incremental and breakthrough thinking
- Consider ideas from completely different industries or contexts
- Document all ideas, even ones that seem unrealistic initially
- Focus on the user/customer benefit rather than internal preferences

## Related Prompts

- `meeting-summary.md` - For documenting brainstorming session outcomes
- `proposal-writer.md` - For developing ideas into formal proposals
- `architecture-planner.md` - For technical implementation of creative solutions

## Tags

`brainstorming` `creativity` `innovation` `problem-solving` `ideation` `strategy` `creative-thinking`
```

#### ✨ Prompt: Story Creator

```
## Description

This prompt helps you develop compelling fictional narratives, character-driven stories, and creative content across various genres with well-structured plots, engaging characters, and immersive world-building.

## Usage

Perfect for creative writing, content creation, storytelling for marketing, game development, screenwriting, novel writing, and creating engaging narratives for any medium or audience.

## Prompt

```markdown
You are a master storyteller and narrative architect with expertise in creating compelling stories across all genres. I need help developing a complete story that captivates readers and delivers emotional impact.

**Story Specifications:**
- Genre: [FANTASY/SCI_FI/MYSTERY/ROMANCE/THRILLER/DRAMA/HORROR/LITERARY_FICTION]
- Story format: [SHORT_STORY/NOVELLA/NOVEL_OUTLINE/SCREENPLAY/SERIES_CONCEPT]
- Target length: [WORD_COUNT_OR_PAGE_COUNT]
- Target audience: [AGE_GROUP_AND_DEMOGRAPHICS]
- Tone/mood: [DARK/LIGHT/HUMOROUS/SERIOUS/MYSTERIOUS/UPLIFTING]

**Story Elements:**
- Central theme: [MAIN_MESSAGE_OR_EXPLORATION]
- Setting: [TIME_PERIOD_LOCATION_WORLD]
- Protagonist type: [CHARACTER_ARCHETYPE_OR_BACKGROUND]
- Conflict type: [INTERNAL/EXTERNAL/SOCIETAL/COSMIC]
- Narrative structure: [LINEAR/NON_LINEAR/MULTIPLE_POV/FRAME_STORY]

**Story Requirements:**
- Emotional goal: [WHAT_READERS_SHOULD_FEEL]
- Key scenes needed: [SPECIFIC_MOMENTS_OR_EVENTS]
- Character arc focus: [GROWTH_JOURNEY_OR_TRANSFORMATION]
- World-building depth: [MINIMAL/MODERATE/EXTENSIVE]
- Dialogue importance: [CHARACTER_DRIVEN/PLOT_DRIVEN/BALANCED]

**Creative Constraints:**
- Must include: [SPECIFIC_ELEMENTS_TO_INCORPORATE]
- Should avoid: [CONTENT_OR_TROPES_TO_EXCLUDE]
- Inspiration sources: [REFERENCE_WORKS_OR_STYLES]
- Unique angle: [WHAT_MAKES_THIS_STORY_DISTINCTIVE]

Please create a complete story that includes:

1. **Story Concept & Hook:**
   - Compelling one-line premise
   - Central conflict and stakes
   - Unique angle or twist
   - Genre expectations and subversions

2. **Character Development:**
   - Fully realized protagonist with clear motivation
   - Supporting characters with distinct voices
   - Character relationships and dynamics
   - Character growth arcs throughout the story

3. **Plot Structure:**
   - Engaging opening that hooks readers immediately
   - Well-paced rising action with escalating tension
   - Meaningful character choices and consequences
   - Satisfying climax and resolution
   - Thematic coherence throughout

4. **World Building:**
   - Vivid, immersive setting descriptions
   - Consistent internal logic and rules
   - Cultural, historical, or technological context
   - Sensory details that bring the world to life

5. **Narrative Craft:**
   - Strong opening and closing lines
   - Show don't tell execution
   - Appropriate point of view and voice
   - Effective use of literary devices
   - Balanced pacing and rhythm

6. **Dialogue & Voice:**
   - Authentic character voices
   - Dialogue that reveals character and advances plot
   - Subtext and emotional undercurrents
   - Period or genre-appropriate language

7. **Thematic Integration:**
   - Subtle weaving of central themes
   - Universal human truths and insights
   - Symbolic elements and metaphors
   - Emotional resonance with target audience

Ensure the story is original, emotionally engaging, and technically well-crafted while maintaining genre conventions and reader expectations.
```

## Example Input

```markdown
Genre: Science Fiction Thriller
Story format: Short story (4,000-5,000 words)
Target length: Novelette length for magazine submission
Target audience: Adult sci-fi readers, tech-savvy professionals
Tone/mood: Tense and mysterious with thought-provoking undertones

Central theme: What defines human consciousness and identity?
Setting: Near-future corporate research facility, underground labs
Protagonist type: Neuroscientist questioning her own memories
Conflict type: Both internal (identity crisis) and external (corporate conspiracy)
Narrative structure: Linear with flashback reveals

Emotional goal: Readers should feel suspense, empathy, and philosophical wonder
Key scenes needed: Memory extraction procedure, identity revelation, escape sequence
Character arc focus: From certainty to doubt to new understanding of self
World-building depth: Moderate - focus on technology and corporate environment
Dialogue importance: Character-driven with scientific exposition

Must include: Advanced neural interface technology, memory manipulation
Should avoid: Obvious AI tropes, overly technical exposition
Inspiration sources: Black Mirror, Philip K. Dick, neuroscience research
Unique angle: Protagonist discovers she might be her own experimental subject
```

## Example Output

```markdown
# The Memory Architect

## Story Concept & Hook

**Premise**: A neuroscientist developing memory extraction technology discovers her own memories may be fabricated experiments.

**Central Conflict**: Dr. Sarah Chen must determine what's real in her own mind while uncovering a conspiracy that makes her both researcher and test subject.

**Stakes**: Not just her identity, but the future of human consciousness and the fate of hundreds of other test subjects.

**Unique Angle**: The protagonist is simultaneously the scientist, the experiment, and the evidence.

---

## The Story

### Opening

The memory felt too perfect.

Dr. Sarah Chen paused, her finger hovering over the neural interface controls, as the recollection of her sixth birthday played across the lab's monitors. Every detail crystalline: the vanilla frosting on her mother's fingertips, the sound of wrapping paper crinkling, the way afternoon sunlight slanted through their kitchen window in exactly seventeen distinct beams.

Too perfect. Too precise. Memories weren't supposed to work like that.

"Subject 847 showing unusual pattern recognition," she murmured into her voice recorder, though her hands trembled slightly as she typed the observation. "Memory recall demonstrates impossible accuracy in environmental details."

The underground lab hummed around her, sixty feet beneath Nexus Corporation's sleek Seattle campus. Banks of quantum processors lined the walls, their blue glow reflecting off polished surfaces that had witnessed three years of her life's work. Three years of extracting, cataloging, and mapping human memories with technology that made science fiction into science fact.

But whose memory was playing on her screen?

"Dr. Chen?" 

She spun toward the voice. Marcus, her research assistant, stood in the doorway holding two steaming coffee cups, his expression concerned. "You've been down here for fourteen hours. Maybe take a break?"

"Marcus, pull up my file," she said, ignoring the offered caffeine. "I need to verify something."

"Your personnel file?"

"No. My *subject* file."

The pause that followed felt like a held breath. Marcus set down both cups carefully, his movements suddenly deliberate.

"Sarah, you know we don't have subject files on staff members."

But his eyes said something different. They said: *Be careful what you ask for.*

### Rising Action

The next morning, Sarah arrived to find her lab access revoked. 

"Temporary security update," explained Dr. Elizabeth Vance, Nexus's Director of Neural Research, her smile as sterile as the white corridors surrounding them. "We're implementing new protocols."

"For a project I designed?"

"For a project that's yielded unexpected results."

Sarah studied her supervisor's face, noting micro-expressions she'd learned to read through three years of neural mapping. Elevated stress indicators. Deception markers. And something else—pity?

"What kind of results?"

"The kind that require careful evaluation. Take a few days off, Sarah. Clear your head."

*Clear your head.* The phrase echoed strangely as Sarah walked toward the elevator. How did one clear a head that might already be cleared—emptied and refilled with artificial experiences?

In her apartment that evening, she methodically examined her possessions. Diploma from MIT—she could remember earning it, but had she? Photos of family gatherings—but why did everyone's faces seem slightly unfocused, like composites? A journal filled with her handwriting, documenting research breakthroughs that felt both intimately familiar and disturbingly foreign.

Her laptop chimed with an encrypted message from an untraceable account:

*The real Sarah Chen died in a car accident eighteen months ago. You're her memories, implanted in a volunteer. Lab C-7, sublevel 3. Tonight. Come alone.*

### Climax

Lab C-7 existed in a part of the facility Sarah had never seen—older, with exposed concrete walls and the antiseptic smell of medical experiments. Emergency lighting cast everything in amber shadows.

At the center of the room sat a neural interface chair, its cables snaking toward a massive quantum core. Surrounding it, dozens of monitors displayed brain scans, memory maps, and what looked like architectural blueprints for a human mind.

"You came."

Sarah turned to find Marcus emerging from the shadows, but he looked different. Older. Tired in a way that went bone-deep.

"You sent the message?"

"I helped create you," he said simply. "After Sarah—the original Sarah—died, her research was too valuable to lose. We extracted her memories from brain tissue, mapped her neural pathways, her decision-making patterns, her creative processes."

"And then?"

"We found a volunteer. Terminal cancer patient who wanted to contribute to science. We gave her Sarah's memories, Sarah's personality, Sarah's genius." He gestured toward her. "We gave her Sarah's life."

The room seemed to tilt. "The volunteer—she's still in there?"

"Sometimes. In dreams, mostly. She was a painter named Elena Rodriguez. Thirty-four, no family. Sometimes I see her in your eyes when you're thinking about something that has nothing to do with neuroscience."

Sarah—or Elena, or whoever she was—sank into the neural interface chair. "How many others?"

"Seventeen successful integrations. All of them brilliant minds that died too young. A quantum physicist. A composer. A surgeon who specialized in pediatric heart repair."

"And they don't know?"

"They know what they need to know to function. But sometimes they start asking questions, like you did. Sometimes they remember the gaps."

She looked at the monitors surrounding her, at the mapped memories that might or might not be hers. "What happens now?"

Marcus moved toward the control panel. "That depends on what you choose to be."

### Resolution

"I choose to be both."

The words surprised her as she spoke them, but they felt right. True.

"Elena Rodriguez was a painter who wanted to contribute to science. Sarah Chen was a neuroscientist who wanted to understand consciousness. I'm someone who can honor both of those dreams."

Marcus's hand stilled on the memory wipe controls. "The company won't allow it. You know too much."

"Then we make sure the other seventeen know too." Sarah stood, her movements purposeful. "We help them choose who they want to be instead of deciding for them."

Through the underground facility's ventilation system, Sarah and Marcus made their way to the main server room. With access codes Sarah's memories provided and Elena's artistic intuition for seeing patterns Marcus had missed, they bypassed security protocols that should have been impenetrable.

"Uploading complete records to WikiLeaks, Washington Post, and the Journal of Neural Engineering," Sarah announced as data streams flowed across her screen. "Every test subject, every procedure, every violation of consent."

"They'll come after us."

"Let them try." Sarah smiled, and for the first time, it felt like both Sarah and Elena were smiling together. "I'm a dead woman with nothing to lose and a live woman with everything to gain."

### Epilogue

Six months later, Dr. Sarah Chen—now publicly known as Sarah Chen-Rodriguez—testified before Congress about neural identity rights and the ethics of consciousness transfer. Seventeen other people sat in the gallery behind her, each one grappling with the question of who they were and who they chose to be.

The technology that created them remained locked away, deemed too dangerous for use without unprecedented safeguards. But the questions they embodied—about identity, consciousness, and what makes us human—would reshape philosophy and law for generations.

In her apartment that evening, Sarah painted. She had no memory of learning the technique, but her hands knew the brush strokes, the way colors blended and light fell across canvas. Elena's gift, perhaps. Or maybe Sarah had always wanted to paint but never made time.

She was painting a memory—seventeen distinct beams of afternoon sunlight streaming through a kitchen window. It might have been real. It might have been fabricated. 

It was beautiful either way.

And it was hers.

---

**Word Count: 4,847 words**

## Character Development

**Sarah Chen-Rodriguez (Protagonist):**
- **Initial State**: Confident scientist driven by intellectual curiosity
- **Inciting Incident**: Discovery of impossibly perfect memories
- **Arc**: Certainty → Doubt → Investigation → Revelation → Integration
- **Final State**: Unified identity embracing both inherited and authentic aspects
- **Motivation**: Truth-seeking and scientific integrity
- **Internal Conflict**: What defines authentic identity?

**Marcus (Supporting Character):**
- **Role**: Reluctant conspirator and moral compass
- **Arc**: Guilt → Confession → Redemption through action
- **Function**: Exposition delivery and emotional grounding
- **Relationship**: Mentor figure with hidden knowledge

**Dr. Vance (Antagonist):**
- **Role**: Corporate authority representing institutional ethics violations
- **Function**: External pressure and systematic opposition
- **Motivation**: Protecting valuable research and corporate interests

## Thematic Analysis

**Primary Theme**: The nature of authentic identity
- Explored through memory reliability questions
- Demonstrates identity as choice rather than inheritance
- Shows integration of multiple selves as valid identity formation

**Secondary Themes**:
- Scientific ethics and informed consent
- Corporate exploitation of human consciousness
- The value of individual choice in identity formation
- Memory as construct vs. experience as truth

**Symbolic Elements**:
- Perfect memory as artificial construct
- Underground lab as hidden truth
- Painting as authentic expression beyond memory
- Light beams as both real and constructed beauty

## Technical Craft Notes

**Point of View**: Close third person limited, maintaining Sarah's perspective
**Pacing**: Accelerating tension with information reveals
**Voice**: Scientific precision balancing with emotional uncertainty  
**Dialogue**: Exposition balanced with character revelation
**Setting**: Near-future corporate environment with noir underground elements
```

## Variations

### Character-Driven Literary Fiction

Focus on deep psychological exploration, complex relationships, and internal character development with subtle plot progression.

### High-Concept Genre Fiction

Emphasize unique premise, world-building, and speculative elements while maintaining strong character arcs and thematic depth.

### Commercial Fiction

Balance engaging plot, accessible characters, and market appeal while delivering satisfying entertainment and emotional payoff.

## Tips

- Start with character desire and external obstacle to create natural conflict
- Use specific, concrete details to make fictional worlds feel authentic and immersive
- Show character growth through actions and choices rather than exposition
- Balance dialogue, action, and description for optimal pacing and reader engagement
- Ensure every scene advances either plot or character development (preferably both)

## Related Prompts

- [Creative Story Generator](../writing/creative-story-generator.md) - For shorter story concepts
- [Brainstorming Session](./brainstorming-session.md) - For generating creative ideas

## Tags

`creative-writing` `storytelling` `fiction` `narrative-structure` `character-development` `world-building` `plot-development` `creative-content`
```


### 📁 Categoria: Development

#### ✨ Prompt: Development Prompts

```
This directory contains prompts specifically designed for software development tasks.

## Categories

- **Code Review**: Prompts for analyzing and improving code quality
- **Documentation**: Generating technical documentation and comments
- **Debugging**: Finding and fixing issues in code
- **Architecture**: Planning system design and structure
- **Testing**: Creating test cases and testing strategies
- **Refactoring**: Improving code structure and maintainability

## Example Prompts

- `code-review.md` - Comprehensive code review assistant
- `documentation-generator.md` - Auto-generate documentation from code
- `bug-hunter.md` - Debug assistance and error analysis
- `architecture-planner.md` - System design and planning
- `test-case-generator.md` - Create comprehensive test suites
- `refactoring-assistant.md` - Code improvement suggestions

## Getting Started

1. Choose a prompt that matches your development task
2. Customize the prompt with your specific code or requirements
3. Run it through your preferred AI model
4. Iterate and refine based on the results

---
*Add your development prompts to this directory following the template structure.*
```

#### ✨ Prompt: Architecture Planner

```
## Description

Helps design and plan software architecture, including system design, component relationships, technology stack decisions, and scalability considerations. Provides structured architectural guidance for projects of any size.

## Usage

Describe your project requirements, constraints, and goals. Include information about expected scale, performance requirements, team size, and any existing systems. Works for both new projects and architectural refactoring.

## Prompt

```markdown
Help me design the software architecture for the following project:

**Project Overview:**
[Describe what the system should do and its main purpose]

**Requirements:**
- **Functional Requirements:**
  - [Core features and capabilities needed]
  - [User interactions and workflows]
  - [Data processing requirements]

- **Non-Functional Requirements:**
  - **Scale**: [Expected users, data volume, transaction volume]
  - **Performance**: [Response time, throughput requirements]
  - **Availability**: [Uptime requirements, disaster recovery needs]
  - **Security**: [Authentication, authorization, data protection needs]

**Constraints:**
- **Budget**: [Budget limitations or cost considerations]
- **Team**: [Team size, skill levels, experience with technologies]
- **Timeline**: [Development timeline and milestones]
- **Technology**: [Required technologies, existing systems to integrate]
- **Compliance**: [Regulatory or industry standards to follow]

**Current State:** [Existing systems, legacy code, or starting from scratch]

Please provide:

1. **High-Level Architecture**
   - System overview and major components
   - Architecture pattern recommendation (MVC, microservices, etc.)
   - Data flow and component interactions

2. **Technology Stack Recommendations**
   - Backend technologies and frameworks
   - Database choices and rationale
   - Frontend technologies
   - Infrastructure and deployment options

3. **Detailed Component Design**
   - Core services/modules breakdown
   - API design considerations
   - Data models and relationships

4. **Scalability Strategy**
   - How to handle growth
   - Performance optimization points
   - Caching strategies

5. **Security Architecture**
   - Authentication and authorization approach
   - Data protection measures
   - Security best practices

6. **Implementation Roadmap**
   - Development phases and priorities
   - MVP scope and incremental features
   - Risk mitigation strategies
```

## Example Input

```markdown
**Project Overview:**
A real-time collaboration platform for remote teams, similar to Slack but with integrated video calls, file sharing, and project management features.

**Requirements:**
- **Functional Requirements:**
  - Real-time messaging and channels
  - Video/audio calling for up to 50 participants
  - File upload and sharing (up to 100MB per file)
  - Task management and project boards
  - User authentication and team management

- **Non-Functional Requirements:**
  - **Scale**: 10,000 concurrent users, 100,000 total users
  - **Performance**: <200ms message delivery, <3s file upload
  - **Availability**: 99.9% uptime
  - **Security**: Enterprise-grade security, GDPR compliance

**Constraints:**
- **Budget**: $50k initial development budget
- **Team**: 5 full-stack developers, 1 DevOps engineer
- **Timeline**: 6 months to MVP, 12 months to full feature set
- **Technology**: Team has experience with React, Node.js, PostgreSQL
```

## Example Output

```markdown
# Collaboration Platform Architecture Design

## High-Level Architecture

### Architecture Pattern: Microservices with Event-Driven Communication
```

┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Web Client    │    │  Mobile Client  │    │  Desktop App    │
│    (React)      │    │   (React Native)│    │   (Electron)    │
└─────────┬───────┘    └─────────┬───────┘    └─────────┬───────┘
          │                      │                      │
          └──────────────────────┼──────────────────────┘
                                 │
                    ┌─────────────┴─────────────┐
                    │     API Gateway           │
                    │   (Authentication +       │
                    │    Load Balancing)        │
                    └─────────────┬─────────────┘
                                  │
    ┌─────────────┬───────────────┼───────────────┬─────────────┐
    │             │               │               │             │
┌───▼───┐    ┌───▼───┐       ┌───▼───┐      ┌───▼───┐    ┌───▼───┐
│Message│    │ User  │       │ File  │      │Video  │    │Project│
│Service│    │Service│       │Service│      │Service│    │Service│
└───┬───┘    └───┬───┘       └───┬───┘      └───┬───┘    └───┬───┘
    │            │               │              │            │
    └────────────┼───────────────┼──────────────┼────────────┘
                 │               │              │
            ┌────▼────┐     ┌────▼────┐    ┌────▼────┐
            │PostgreSQL│     │   S3    │    │  Redis  │
            │(Primary) │     │(Files)  │    │(Cache)  │
            └─────────┘     └─────────┘    └─────────┘

```

## Technology Stack Recommendations

### Backend
- **Language**: Node.js with TypeScript (team familiarity)
- **Framework**: Express.js with Fastify for high-performance services
- **Real-time**: Socket.io for WebSocket connections
- **Message Queue**: Redis for pub/sub and job queues
- **Video**: WebRTC with Kurento Media Server for large calls

### Database
- **Primary**: PostgreSQL for structured data (users, teams, projects)
- **Cache**: Redis for sessions, real-time data, and message caching
- **File Storage**: AWS S3 or MinIO for file uploads
- **Search**: Elasticsearch for message search functionality

### Frontend
- **Framework**: React with TypeScript
- **State Management**: Redux Toolkit for complex state
- **Real-time**: Socket.io client
- **UI Library**: Material-UI or Ant Design for rapid development

### Infrastructure
- **Containerization**: Docker with Docker Compose for development
- **Orchestration**: Kubernetes for production (or start with simple VPS)
- **CI/CD**: GitHub Actions
- **Monitoring**: Prometheus + Grafana

## Detailed Component Design

### 1. Message Service
```typescript
interface MessageService {
  sendMessage(channelId: string, message: MessagePayload): Promise<void>
  getChannelHistory(channelId: string, limit: number): Promise<Message[]>
  subscribeToChannel(channelId: string, userId: string): void
}
```

- Real-time message delivery via Socket.io
- Message persistence in PostgreSQL
- Redis for message caching and pub/sub

### 2. User Service

```typescript
interface UserService {
  authenticate(credentials: LoginCredentials): Promise<AuthResult>
  createUser(userData: CreateUserRequest): Promise<User>
  updateUserStatus(userId: string, status: UserStatus): Promise<void>
}
```

- JWT-based authentication
- User management and team assignments
- Integration with external OAuth providers

### 3. File Service

- Secure file upload with virus scanning
- Progressive upload for large files
- Automatic thumbnail generation for images
- CDN integration for fast delivery

### 4. Video Service

- WebRTC peer-to-peer for small calls (<5 people)
- Selective Forwarding Unit (SFU) for larger calls
- Recording capabilities with cloud storage
- Screen sharing support

## Scalability Strategy

### Phase 1 (MVP): Monolithic Start

- Single Node.js application
- PostgreSQL primary database
- Redis for caching
- Supports up to 1,000 concurrent users

### Phase 2 (Growth): Service Separation

- Extract message service for independent scaling
- Add read replicas for database
- Implement horizontal scaling for video services
- CDN for static assets

### Phase 3 (Scale): Full Microservices

- Complete service decomposition
- Database sharding by team/organization
- Multi-region deployment
- Advanced caching strategies

## Security Architecture

### Authentication & Authorization

```
User → API Gateway → JWT Validation → Service Authorization
```

- JWT tokens with short expiry (15 minutes)
- Refresh token rotation
- Role-based access control (RBAC)
- Rate limiting per user/IP

### Data Protection

- End-to-end encryption for sensitive messages
- At-rest encryption for database and files
- HTTPS everywhere with HSTS headers
- Input validation and sanitization

## Implementation Roadmap

### Phase 1 (Months 1-2): Core MVP

**Goal**: Basic messaging and user management

- User authentication and team creation
- Real-time messaging in channels
- Basic file sharing
- Simple web client

**MVP Features:**

- Login/signup
- Create teams and channels
- Send/receive messages
- Upload/download files

### Phase 2 (Months 3-4): Enhanced Features

- Video calling (up to 10 participants)
- Message search
- Mobile-responsive design
- Basic project management features

### Phase 3 (Months 5-6): Production Ready

- Advanced video features (screen sharing, recording)
- Full project management integration
- Admin dashboard
- Comprehensive security features

### Risk Mitigation

1. **Technical Risks**:
   - Start with proven technologies
   - Build comprehensive testing early
   - Plan for database migration strategies

2. **Scalability Risks**:
   - Design with microservices in mind from day 1
   - Use feature flags for gradual rollouts
   - Monitor performance metrics continuously

3. **Security Risks**:
   - Regular security audits
   - Implement logging and monitoring
   - Have incident response plan ready

## Success Metrics

- Message delivery latency <200ms
- 99.9% uptime
- Support 10,000 concurrent users
- File upload success rate >99%
- Video call quality metrics

```

## Variations
- **Enterprise Architecture**: Focus on enterprise patterns and governance
- **Microservices Design**: Deep dive into service decomposition
- **Cloud-Native**: Emphasize cloud services and serverless architectures
- **Legacy Migration**: Focus on modernizing existing systems

## Tips
- Be specific about scale and performance requirements
- Include budget and timeline constraints for realistic recommendations
- Mention team expertise to align technology choices
- Consider starting simple and evolving the architecture over time
- Always include security and compliance considerations

## Related Prompts
- `code-review.md` - For reviewing architectural decisions in code
- `documentation-generator.md` - For creating architecture documentation
- `test-case-generator.md` - For testing architectural components

## Tags
`architecture` `system-design` `scalability` `technology-stack` `development` `planning`
```

#### ✨ Prompt: Bug Hunter

```
## Description

A systematic debugging assistant that helps identify, analyze, and resolve software bugs and errors. Provides step-by-step troubleshooting approaches and suggests fixes for various types of issues.

## Usage

Provide error messages, problematic code, or describe unexpected behavior. Include relevant context like environment, inputs, and expected vs. actual outcomes. Works across all programming languages.

## Prompt

```markdown
Help me debug the following issue. Please provide a systematic analysis:

**Problem Description:**
[Describe what's happening vs. what should happen]

**Error Message/Symptoms:**
```

[PASTE ERROR MESSAGE OR DESCRIBE SYMPTOMS]

```

**Code:**
```

[PASTE RELEVANT CODE]

```

**Environment:**
- Programming Language: [language and version]
- Framework/Libraries: [if applicable]
- Operating System: [OS details]
- Input Data: [sample inputs that cause the issue]

Please analyze this by:

1. **Root Cause Analysis**
   - Identify the likely cause of the issue
   - Explain why this error occurs
   - Point to specific lines or components

2. **Debugging Strategy**
   - Step-by-step debugging approach
   - What to check or test first
   - Logging/debugging techniques to use

3. **Solution Options**
   - Primary fix recommendation
   - Alternative approaches
   - Preventive measures

4. **Testing Approach**
   - How to verify the fix works
   - Edge cases to test
   - Regression testing recommendations

Additional context:
[ANY OTHER RELEVANT INFORMATION]
```

## Example Input

```markdown
**Problem Description:**
My Python web scraper randomly fails with connection errors, but the website is accessible in the browser.

**Error Message:**
```

requests.exceptions.ConnectionError: HTTPSConnectionPool(host='example.com', port=443):
Max retries exceeded with url: /api/data (Caused by NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x7f8b8c0b1d90>: Failed to establish a new connection: [Errno 111] Connection refused'))

```

**Code:**
```python
import requests
import time

def scrape_data():
    urls = ["https://example.com/api/data", "https://example.com/api/users"]
    results = []
    
    for url in urls:
        response = requests.get(url)
        results.append(response.json())
        time.sleep(0.1)
    
    return results
```

**Environment:**

- Python 3.9
- requests library 2.28.1
- Running on Ubuntu 20.04
- Input: Multiple URLs being scraped in sequence

```

## Example Output
```

### Debug Analysis Report

#### Root Cause Analysis

**Primary Issue:** Rate limiting and connection management
The error indicates connection refusal, which typically occurs when:

1. **Rate Limiting**: The server is blocking requests due to too many rapid connections
2. **Connection Pool Exhaustion**: Not properly managing HTTP connections
3. **Server-side blocking**: Anti-bot measures detecting automated requests

**Specific Issues in Code:**

- Line 8: No error handling for failed requests
- Line 9: Very short delay (0.1s) may trigger rate limiting
- No User-Agent header (common anti-bot trigger)
- No retry mechanism for transient failures

### Debugging Strategy

### Immediate Debugging Steps

1. **Test connectivity**: `curl -I https://example.com/api/data`
2. **Check rate limits**: Increase delay to 2-3 seconds
3. **Monitor network**: Use `netstat` or Wireshark to see connection states
4. **Add logging**: Log response status codes before the error

### Code for Debugging

```python
import logging
logging.basicConfig(level=logging.DEBUG)

# Add this before your request
print(f"Attempting to connect to: {url}")
response = requests.get(url, timeout=10)
print(f"Response status: {response.status_code}")
```

### Solution Options

#### Primary Fix (Recommended)

```python
import requests
import time
from requests.adapters import HTTPAdapter
from urllib3.util.retry import Retry

def scrape_data():
    # Configure session with retry strategy
    session = requests.Session()
    retry_strategy = Retry(
        total=3,
        backoff_factor=1,
        status_forcelist=[429, 500, 502, 503, 504],
    )
    adapter = HTTPAdapter(max_retries=retry_strategy)
    session.mount("http://", adapter)
    session.mount("https://", adapter)
    
    # Add headers to appear more like a browser
    headers = {
        'User-Agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36',
        'Accept': 'application/json',
        'Accept-Language': 'en-US,en;q=0.9'
    }
    
    urls = ["https://example.com/api/data", "https://example.com/api/users"]
    results = []
    
    for url in urls:
        try:
            response = session.get(url, headers=headers, timeout=30)
            response.raise_for_status()
            results.append(response.json())
            # Respectful delay
            time.sleep(2)
        except requests.exceptions.RequestException as e:
            print(f"Error fetching {url}: {e}")
            continue
    
    return results
```

### Alternative Approaches

1. **Use connection pooling**: Implement session reuse
2. **Implement exponential backoff**: Gradually increase delays
3. **Add proxy rotation**: If being blocked by IP
4. **Use async requests**: For better connection management

### Testing Approach

#### Verification Steps

1. **Unit test**: Test with single URL first
2. **Load test**: Gradually increase number of URLs
3. **Network simulation**: Test with poor connectivity
4. **Edge cases**: Test with invalid URLs, timeouts

### Test Code

```python
def test_scraper():
    # Test single URL
    result = scrape_data_single("https://httpbin.org/json")
    assert result is not None
    
    # Test with delay
    start_time = time.time()
    scrape_data()
    duration = time.time() - start_time
    assert duration >= 2  # Ensure delay is working
```

### Prevention Measures

- Always implement proper error handling
- Use session objects for connection reuse
- Add appropriate delays between requests
- Include realistic User-Agent headers
- Implement retry logic for transient failures
- Monitor rate limits and adjust accordingly

```

## Variations
- **Performance Issues**: Focus on optimization and profiling
- **Security Bugs**: Emphasize vulnerability analysis and secure coding
- **Integration Issues**: Focus on API and service integration problems
- **Frontend Debugging**: Specialized for JavaScript/browser issues

## Tips
- Include full error stack traces when possible
- Provide minimal reproducible examples
- Mention any recent changes that might have introduced the bug
- Include relevant log files or console output
- Specify if the issue is intermittent or consistent

## Related Prompts
- `code-review.md` - For preventing bugs through better code quality
- `test-case-generator.md` - For creating tests to catch bugs
- `refactoring-assistant.md` - For improving code structure to prevent issues

## Tags
`debugging` `troubleshooting` `error-analysis` `bug-fixing` `development` `problem-solving`
```

#### ✨ Prompt: Code Review Assistant

```
## Description

A comprehensive code review prompt that analyzes code quality, identifies potential issues, suggests improvements, and provides detailed feedback on best practices, security, performance, and maintainability.

## Usage

Paste your code along with any specific concerns or focus areas. Works with any programming language. Best used for reviewing pull requests, refactoring decisions, or general code quality assessment.

## Prompt

```markdown
Please perform a comprehensive code review of the following code. Analyze it for:

1. **Code Quality & Style**
   - Readability and clarity
   - Naming conventions
   - Code organization and structure
   - Adherence to language-specific best practices

2. **Performance & Efficiency**
   - Algorithm efficiency
   - Resource usage
   - Potential bottlenecks
   - Optimization opportunities

3. **Security Concerns**
   - Potential vulnerabilities
   - Input validation
   - Data handling practices
   - Security best practices

4. **Maintainability**
   - Code complexity
   - Documentation and comments
   - Modularity and reusability
   - Error handling

5. **Testing & Reliability**
   - Edge cases consideration
   - Error scenarios
   - Testing recommendations

Please provide:
- Specific line-by-line feedback where applicable
- Priority levels for each issue (Critical/High/Medium/Low)
- Concrete suggestions for improvement
- Positive aspects worth highlighting

Code to review:
```

[YOUR CODE HERE]

```

Additional context or specific concerns:
[SPECIFY ANY PARTICULAR AREAS TO FOCUS ON]
```

## Example Input

```markdown
```javascript
function calculateDiscount(price, discountPercent) {
    var discount = price * discountPercent / 100;
    var finalPrice = price - discount;
    return finalPrice;
}

function processOrder(items) {
    var total = 0;
    for(var i = 0; i < items.length; i++) {
        total += calculateDiscount(items[i].price, items[i].discount);
    }
    return total;
}
```

```

## Example Output

```markdown
## Code Review Feedback

### Overall Assessment
The code is functional but has several areas for improvement in terms of best practices, error handling, and modern JavaScript conventions.

### Specific Issues

**Medium Priority Issues:**
1. **Line 1-4**: Use `const`/`let` instead of `var` for better scoping
2. **Line 1**: Missing input validation - function should handle edge cases
3. **Line 6-10**: Consider using modern array methods like `reduce()`

**Low Priority Issues:**
1. **General**: Add JSDoc comments for better documentation
2. **Line 6**: Variable naming could be more descriptive

### Suggested Improvements

```javascript
/**
 * Calculates discounted price
 * @param {number} price - Original price (must be positive)
 * @param {number} discountPercent - Discount percentage (0-100)
 * @returns {number} Final price after discount
 */
function calculateDiscount(price, discountPercent) {
    if (price < 0 || discountPercent < 0 || discountPercent > 100) {
        throw new Error('Invalid input parameters');
    }
    
    const discount = price * discountPercent / 100;
    return price - discount;
}

/**
 * Calculates total for order with individual item discounts
 * @param {Array} items - Array of items with price and discount properties
 * @returns {number} Total order amount
 */
function processOrder(items) {
    if (!Array.isArray(items)) {
        throw new Error('Items must be an array');
    }
    
    return items.reduce((total, item) => {
        return total + calculateDiscount(item.price, item.discount);
    }, 0);
}
```

### Positive Aspects

- Clear function naming that describes purpose
- Simple, focused functions following single responsibility principle
- Clean separation between discount calculation and order processing

```

## Variations
- **Security-Focused**: Emphasize security vulnerabilities and data protection
- **Performance-Focused**: Concentrate on optimization and efficiency
- **Junior Developer**: Provide more educational explanations and learning resources
- **Legacy Code**: Focus on modernization and technical debt reduction

## Tips
- Provide the programming language for more targeted feedback
- Include context about the application domain for better security analysis
- Mention any specific coding standards or frameworks being used
- Be specific about performance requirements or constraints

## Related Prompts
- `refactoring-assistant.md` - For code improvement suggestions
- `documentation-generator.md` - For adding comprehensive documentation
- `test-case-generator.md` - For creating tests for reviewed code

## Tags
`code-review` `quality-assurance` `best-practices` `development` `debugging`
```

#### ✨ Prompt: Documentation Generator

```
## Description

Automatically generates comprehensive documentation from code, including API documentation, README files, inline comments, and user guides. Supports multiple programming languages and documentation formats.

## Usage

Provide your code and specify the type of documentation needed. Works best with well-structured code that has clear function/class definitions. Specify the target audience and format requirements.

## Prompt

```markdown
Generate comprehensive documentation for the following code. Please create:

1. **API Documentation**
   - Function/method signatures
   - Parameter descriptions with types
   - Return value specifications
   - Usage examples
   - Error conditions

2. **Inline Comments**
   - Code explanation comments
   - Complex logic breakdown
   - Algorithm descriptions
   - Performance considerations

3. **README Section** (if applicable)
   - Purpose and overview
   - Installation/setup instructions
   - Basic usage examples
   - Configuration options

4. **User Guide Elements**
   - Step-by-step usage instructions
   - Common use cases
   - Troubleshooting tips
   - Best practices

Documentation requirements:
- Target audience: [developers/end-users/technical writers]
- Format: [Markdown/JSDoc/Sphinx/other]
- Documentation style: [comprehensive/concise/beginner-friendly]

Code to document:
```

[YOUR CODE HERE]

```

Additional context:
[PROJECT PURPOSE, DEPENDENCIES, SPECIAL REQUIREMENTS]
```

## Example Input

```markdown
```python
import requests
import json
from typing import Dict, List, Optional

class WeatherAPI:
    def __init__(self, api_key: str, base_url: str = "https://api.weather.com"):
        self.api_key = api_key
        self.base_url = base_url
    
    def get_current_weather(self, city: str, units: str = "metric") -> Dict:
        endpoint = f"{self.base_url}/current"
        params = {
            "city": city,
            "units": units,
            "api_key": self.api_key
        }
        response = requests.get(endpoint, params=params)
        response.raise_for_status()
        return response.json()
    
    def get_forecast(self, city: str, days: int = 5) -> List[Dict]:
        endpoint = f"{self.base_url}/forecast"
        params = {
            "city": city,
            "days": days,
            "api_key": self.api_key
        }
        response = requests.get(endpoint, params=params)
        response.raise_for_status()
        return response.json()["forecast"]
```

```
## Example Output

```markdown
# WeatherAPI Documentation

## Overview
The WeatherAPI class provides a simple interface to fetch current weather data and forecasts for any city using a weather service API.

## Installation
```bash
pip install requests
```

## Quick Start

```python
from weather_api import WeatherAPI

# Initialize the API client
weather = WeatherAPI(api_key="your_api_key_here")

# Get current weather
current = weather.get_current_weather("New York")
print(f"Temperature: {current['temperature']}°C")

# Get 7-day forecast
forecast = weather.get_forecast("London", days=7)
for day in forecast:
    print(f"{day['date']}: {day['temperature']}°C, {day['description']}")
```

## API Reference

### Class: WeatherAPI

#### Constructor

```python
WeatherAPI(api_key: str, base_url: str = "https://api.weather.com")
```

**Parameters:**

- `api_key` (str): Your API key for the weather service
- `base_url` (str, optional): Base URL for the weather API. Defaults to "<https://api.weather.com>"

**Example:**

```python
weather = WeatherAPI("your_api_key", "https://custom-weather-api.com")
```

#### get_current_weather()

```python
get_current_weather(city: str, units: str = "metric") -> Dict
```

Retrieves current weather conditions for the specified city.

**Parameters:**

- `city` (str): Name of the city to get weather for
- `units` (str, optional): Temperature units ("metric", "imperial", "kelvin"). Defaults to "metric"

**Returns:**

- `Dict`: Weather data containing temperature, humidity, description, etc.

**Raises:**

- `requests.HTTPError`: If the API request fails
- `requests.ConnectionError`: If unable to connect to the API

**Example:**

```python
weather_data = weather.get_current_weather("Tokyo", units="imperial")
temp_f = weather_data["temperature"]  # Temperature in Fahrenheit
```

#### get_forecast()

```python
get_forecast(city: str, days: int = 5) -> List[Dict]
```

Retrieves weather forecast for the specified city.

**Parameters:**

- `city` (str): Name of the city to get forecast for
- `days` (int, optional): Number of days to forecast (1-10). Defaults to 5

**Returns:**

- `List[Dict]`: List of daily forecast data

**Raises:**

- `requests.HTTPError`: If the API request fails
- `ValueError`: If days parameter is outside valid range

**Example:**

```python
forecast = weather.get_forecast("Paris", days=3)
tomorrow = forecast[1]  # Second day (tomorrow)
```

## Error Handling

All methods may raise HTTP-related exceptions. Implement proper error handling:

```python
try:
    weather_data = weather.get_current_weather("InvalidCity")
except requests.HTTPError as e:
    print(f"API error: {e}")
except requests.ConnectionError:
    print("Unable to connect to weather service")
```

## Best Practices

- Store your API key securely (environment variables)
- Implement rate limiting to avoid API quota issues
- Cache responses when appropriate to reduce API calls
- Validate city names before making requests

```

## Variations
- **API-Only**: Focus only on API documentation with technical details
- **User Manual**: Create end-user focused documentation with tutorials
- **Inline Comments**: Generate only code comments and docstrings
- **Architecture Docs**: Create high-level system architecture documentation

## Tips
- Include the programming language for language-specific documentation standards
- Specify if you need examples for specific use cases
- Mention any existing documentation standards or tools used in your project
- Provide context about the intended users of the documentation

## Related Prompts
- `code-review.md` - For improving code before documenting
- `architecture-planner.md` - For system-level documentation
- `test-case-generator.md` - For creating documented test examples

## Tags
`documentation` `api-docs` `comments` `readme` `development` `technical-writing`
```

#### ✨ Prompt: Refactoring Assistant

```
## Description

This prompt helps you analyze and refactor existing code to improve its structure, readability, maintainability, and performance while preserving functionality.

## Usage

Perfect for improving legacy code, preparing code for new features, reducing technical debt, and following best practices and design patterns.

## Prompt

```markdown
You are an expert code refactoring assistant. I need help refactoring the following code to improve its quality while maintaining the same functionality.

**Code to refactor:**
```

[INSERT_CODE_HERE]

```

**Context:**
- Programming language: [LANGUAGE]
- Framework/library: [FRAMEWORK_IF_ANY]
- Current issues: [DESCRIBE_PROBLEMS]
- Performance requirements: [PERFORMANCE_NEEDS]
- Coding standards: [STYLE_GUIDE_IF_ANY]

Please analyze the code and provide:

1. **Code Quality Assessment:**
   - Identify code smells and anti-patterns
   - Assess readability, maintainability, and performance
   - Check adherence to SOLID principles
   - Evaluate naming conventions and structure

2. **Refactoring Plan:**
   - List specific improvements needed
   - Prioritize changes by impact and complexity
   - Identify any breaking changes
   - Suggest design patterns if applicable

3. **Refactored Code:**
   - Provide the improved version
   - Add clear comments explaining changes
   - Ensure functionality is preserved
   - Follow best practices for the language/framework

4. **Explanation:**
   - Explain what was changed and why
   - Highlight performance improvements
   - Note any new dependencies or requirements
   - Provide migration steps if needed

5. **Testing Recommendations:**
   - Suggest test cases to verify functionality
   - Recommend regression testing approach
   - Identify potential edge cases to test

Focus on making the code more readable, maintainable, and efficient while following established best practices.
```

## Example Input

```markdown
Code to refactor:
```javascript
function processUsers(users) {
    var result = [];
    for (var i = 0; i < users.length; i++) {
        if (users[i].age >= 18 && users[i].active == true) {
            var userData = {};
            userData.name = users[i].firstName + " " + users[i].lastName;
            userData.email = users[i].email;
            userData.category = users[i].age >= 65 ? "senior" : "adult";
            result.push(userData);
        }
    }
    return result;
}
```

Context:

- Programming language: JavaScript (ES6+)
- Framework/library: None
- Current issues: Old syntax, not functional, poor readability
- Performance requirements: Handle arrays up to 10,000 users
- Coding standards: ES6+, functional programming preferred

```

## Example Output
```

## Code Quality Assessment

- Uses var instead of const/let
- Traditional for loop instead of array methods
- Loose equality comparison (==)
- Imperative style instead of functional
- No input validation
- String concatenation instead of template literals

## Refactoring Plan

1. Convert to functional programming style
2. Use modern ES6+ syntax
3. Add input validation
4. Extract helper functions for better readability
5. Use array methods for better performance

## Refactored Code

```javascript
/**
 * Processes users array to extract active adult users with formatted data
 * @param {Array<Object>} users - Array of user objects
 * @returns {Array<Object>} Filtered and formatted user data
 */
const processUsers = (users = []) => {
  if (!Array.isArray(users)) {
    throw new Error('Input must be an array');
  }

  const isEligibleUser = (user) => 
    user?.age >= 18 && user?.active === true;

  const formatUserData = (user) => ({
    name: `${user.firstName} ${user.lastName}`,
    email: user.email,
    category: user.age >= 65 ? 'senior' : 'adult'
  });

  return users
    .filter(isEligibleUser)
    .map(formatUserData);
};
```

## Explanation

- **Modern syntax**: Used const, arrow functions, template literals
- **Functional approach**: Replaced imperative loop with filter/map chain
- **Better readability**: Extracted helper functions with descriptive names
- **Input validation**: Added type checking and default parameter
- **Performance**: Array methods are optimized and more readable
- **Strict equality**: Used === instead of ==
- **Optional chaining**: Added ?. for safer property access

## Testing Recommendations

- Test with empty array, null, undefined inputs
- Test with users of various ages (under 18, 18-64, 65+)
- Test with inactive users
- Test with malformed user objects
- Performance test with 10,000+ user array

```

## Variations

### Legacy Code Modernization
Focus specifically on updating old syntax and patterns to modern standards while maintaining backward compatibility.

### Performance-Focused Refactoring
Emphasize optimization for speed, memory usage, and scalability in the refactoring suggestions.

### Security-Focused Refactoring
Prioritize identifying and fixing security vulnerabilities, input validation, and secure coding practices.

## Tips
- Always preserve the original functionality unless explicitly asked to change it
- Test thoroughly after refactoring to ensure no regressions
- Refactor in small, incremental steps rather than large rewrites
- Consider the team's skill level when suggesting modern patterns
- Document any breaking changes clearly

## Related Prompts
- [Code Review](./code-review.md) - For reviewing code quality
- [Test Case Generator](./test-case-generator.md) - For creating tests after refactoring
- [Documentation Generator](./documentation-generator.md) - For updating docs after refactoring

## Tags
`refactoring` `code-quality` `best-practices` `modernization` `optimization` `maintainability` `technical-debt` `clean-code`
```

#### ✨ Prompt: Test Case Generator

```
## Description

Generates comprehensive test cases and testing strategies for software applications. Creates unit tests, integration tests, user acceptance tests, and edge case scenarios based on code, requirements, or functionality descriptions.

## Usage

Provide code, feature requirements, or API specifications that need testing. Specify the testing framework, level of coverage needed, and types of tests required. Works for all programming languages and testing approaches.

## Prompt

```markdown
Generate comprehensive test cases for the following:

**Testing Target:**
[Function/Class/API/Feature/User Story to be tested]

**Code/Requirements:**
```

[PROVIDE CODE, API SPEC, OR FEATURE REQUIREMENTS HERE]

```

**Testing Requirements:**
- **Test Types Needed:** [Unit tests / Integration tests / End-to-end tests / Performance tests]
- **Testing Framework:** [Jest/Mocha/PyTest/JUnit/Cypress/Other]
- **Coverage Goals:** [Basic functionality / Edge cases / Error conditions / Performance]
- **Programming Language:** [JavaScript/Python/Java/C#/Other]

**Test Scenarios to Include:**
1. **Happy Path Tests**
   - Normal operation with valid inputs
   - Expected successful outcomes
   - Standard use cases

2. **Edge Case Tests**
   - Boundary value testing
   - Unusual but valid inputs
   - Minimum and maximum values

3. **Error Handling Tests**
   - Invalid inputs and parameters
   - Network failures and timeouts
   - Resource limitations

4. **Integration Tests** (if applicable)
   - Component interactions
   - External service dependencies
   - Database operations

5. **Performance Tests** (if applicable)
   - Load testing scenarios
   - Response time requirements
   - Resource usage monitoring

**Additional Requirements:**
- [Mock external dependencies]
- [Test data setup/teardown]
- [Specific assertion patterns]
- [Documentation level needed]

Please provide:
- Test case descriptions and rationale
- Complete test code implementations
- Test data and setup requirements
- Expected outcomes and assertions
- Comments explaining complex test logic
```

## Example Input

```markdown
**Testing Target:** User authentication function

**Code/Requirements:**
```javascript
async function authenticateUser(email, password) {
    if (!email || !password) {
        throw new Error('Email and password are required');
    }
    
    if (!isValidEmail(email)) {
        throw new Error('Invalid email format');
    }
    
    const user = await getUserByEmail(email);
    if (!user) {
        throw new Error('User not found');
    }
    
    const isPasswordValid = await bcrypt.compare(password, user.hashedPassword);
    if (!isPasswordValid) {
        throw new Error('Invalid password');
    }
    
    return {
        userId: user.id,
        email: user.email,
        token: generateJWT(user.id)
    };
}
```

**Testing Requirements:**

- **Test Types:** Unit tests with mocking
- **Framework:** Jest
- **Coverage:** All branches and error conditions
- **Language:** JavaScript/Node.js

```

## Example Output
```javascript
// authenticateUser.test.js
const bcrypt = require('bcrypt');
const { authenticateUser } = require('./auth');
const { getUserByEmail, generateJWT, isValidEmail } = require('./utils');

// Mock dependencies
jest.mock('./utils');
jest.mock('bcrypt');

describe('authenticateUser', () => {
  beforeEach(() => {
    jest.clearAllMocks();
  });

  describe('Happy Path Tests', () => {
    test('should authenticate user with valid credentials', async () => {
      // Arrange
      const email = 'user@example.com';
      const password = 'securePassword123';
      const mockUser = {
        id: 1,
        email: 'user@example.com',
        hashedPassword: 'hashedPassword123'
      };
      const mockToken = 'jwt.token.here';

      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockResolvedValue(mockUser);
      bcrypt.compare.mockResolvedValue(true);
      generateJWT.mockReturnValue(mockToken);

      // Act
      const result = await authenticateUser(email, password);

      // Assert
      expect(result).toEqual({
        userId: 1,
        email: 'user@example.com',
        token: mockToken
      });
      expect(getUserByEmail).toHaveBeenCalledWith(email);
      expect(bcrypt.compare).toHaveBeenCalledWith(password, mockUser.hashedPassword);
      expect(generateJWT).toHaveBeenCalledWith(mockUser.id);
    });
  });

  describe('Input Validation Tests', () => {
    test('should throw error when email is missing', async () => {
      // Arrange & Act & Assert
      await expect(authenticateUser(null, 'password123'))
        .rejects
        .toThrow('Email and password are required');
    });

    test('should throw error when password is missing', async () => {
      // Arrange & Act & Assert
      await expect(authenticateUser('user@example.com', null))
        .rejects
        .toThrow('Email and password are required');
    });

    test('should throw error when both email and password are missing', async () => {
      // Arrange & Act & Assert
      await expect(authenticateUser(null, null))
        .rejects
        .toThrow('Email and password are required');
    });

    test('should throw error when email format is invalid', async () => {
      // Arrange
      const invalidEmail = 'invalid-email';
      const password = 'password123';
      
      isValidEmail.mockReturnValue(false);

      // Act & Assert
      await expect(authenticateUser(invalidEmail, password))
        .rejects
        .toThrow('Invalid email format');
      
      expect(isValidEmail).toHaveBeenCalledWith(invalidEmail);
    });
  });

  describe('Edge Case Tests', () => {
    test('should handle empty string email', async () => {
      // Arrange & Act & Assert
      await expect(authenticateUser('', 'password123'))
        .rejects
        .toThrow('Email and password are required');
    });

    test('should handle empty string password', async () => {
      // Arrange & Act & Assert
      await expect(authenticateUser('user@example.com', ''))
        .rejects
        .toThrow('Email and password are required');
    });

    test('should handle very long email', async () => {
      // Arrange
      const longEmail = 'a'.repeat(250) + '@example.com';
      const password = 'password123';
      
      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockResolvedValue(null);

      // Act & Assert
      await expect(authenticateUser(longEmail, password))
        .rejects
        .toThrow('User not found');
    });
  });

  describe('User Not Found Tests', () => {
    test('should throw error when user does not exist', async () => {
      // Arrange
      const email = 'nonexistent@example.com';
      const password = 'password123';
      
      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockResolvedValue(null);

      // Act & Assert
      await expect(authenticateUser(email, password))
        .rejects
        .toThrow('User not found');
      
      expect(getUserByEmail).toHaveBeenCalledWith(email);
    });
  });

  describe('Password Validation Tests', () => {
    test('should throw error when password is incorrect', async () => {
      // Arrange
      const email = 'user@example.com';
      const password = 'wrongPassword';
      const mockUser = {
        id: 1,
        email: 'user@example.com',
        hashedPassword: 'hashedPassword123'
      };

      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockResolvedValue(mockUser);
      bcrypt.compare.mockResolvedValue(false);

      // Act & Assert
      await expect(authenticateUser(email, password))
        .rejects
        .toThrow('Invalid password');
      
      expect(bcrypt.compare).toHaveBeenCalledWith(password, mockUser.hashedPassword);
    });
  });

  describe('Error Handling Tests', () => {
    test('should handle database connection error', async () => {
      // Arrange
      const email = 'user@example.com';
      const password = 'password123';
      
      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockRejectedValue(new Error('Database connection failed'));

      // Act & Assert
      await expect(authenticateUser(email, password))
        .rejects
        .toThrow('Database connection failed');
    });

    test('should handle bcrypt comparison error', async () => {
      // Arrange
      const email = 'user@example.com';
      const password = 'password123';
      const mockUser = {
        id: 1,
        email: 'user@example.com',
        hashedPassword: 'hashedPassword123'
      };

      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockResolvedValue(mockUser);
      bcrypt.compare.mockRejectedValue(new Error('Bcrypt error'));

      // Act & Assert
      await expect(authenticateUser(email, password))
        .rejects
        .toThrow('Bcrypt error');
    });
  });

  describe('Integration Tests', () => {
    test('should call dependencies in correct order', async () => {
      // Arrange
      const email = 'user@example.com';
      const password = 'password123';
      const mockUser = {
        id: 1,
        email: 'user@example.com',
        hashedPassword: 'hashedPassword123'
      };

      isValidEmail.mockReturnValue(true);
      getUserByEmail.mockResolvedValue(mockUser);
      bcrypt.compare.mockResolvedValue(true);
      generateJWT.mockReturnValue('token');

      // Act
      await authenticateUser(email, password);

      // Assert - verify call order
      expect(isValidEmail).toHaveBeenCalledBefore(getUserByEmail);
      expect(getUserByEmail).toHaveBeenCalledBefore(bcrypt.compare);
      expect(bcrypt.compare).toHaveBeenCalledBefore(generateJWT);
    });
  });
});

// Performance test example
describe('authenticateUser Performance', () => {
  test('should complete authentication within 100ms', async () => {
    // Arrange
    const email = 'user@example.com';
    const password = 'password123';
    const mockUser = { id: 1, email, hashedPassword: 'hash' };

    isValidEmail.mockReturnValue(true);
    getUserByEmail.mockResolvedValue(mockUser);
    bcrypt.compare.mockResolvedValue(true);
    generateJWT.mockReturnValue('token');

    // Act
    const startTime = Date.now();
    await authenticateUser(email, password);
    const endTime = Date.now();

    // Assert
    expect(endTime - startTime).toBeLessThan(100);
  });
});
```

## Test Coverage Report

The above test suite provides:

- **Function Coverage**: 100% - All functions are tested
- **Branch Coverage**: 100% - All conditional paths tested
- **Statement Coverage**: 100% - All code lines executed
- **Edge Case Coverage**: Comprehensive boundary testing

## Test Data Setup

```javascript
// testData/users.js
export const validUsers = [
  {
    id: 1,
    email: 'user1@example.com',
    hashedPassword: '$2b$10$validHashedPassword1'
  },
  {
    id: 2,
    email: 'user2@example.com',
    hashedPassword: '$2b$10$validHashedPassword2'
  }
];

export const invalidEmails = [
  'invalid-email',
  'user@',
  '@example.com',
  'user..name@example.com',
  'user name@example.com'
];
```

## Variations

- **API Testing**: Focus on HTTP endpoint testing with request/response validation
- **Frontend Testing**: UI component testing with user interactions
- **Database Testing**: Data layer testing with setup/teardown procedures
- **Security Testing**: Penetration testing and vulnerability assessment

## Tips

- Always test both positive and negative scenarios
- Include boundary value testing for numeric inputs
- Mock external dependencies to isolate unit tests
- Use descriptive test names that explain the scenario
- Group related tests using `describe` blocks
- Include performance tests for critical functions
- Test error conditions as thoroughly as success conditions

## Related Prompts

- `code-review.md` - For reviewing test quality and coverage
- `bug-hunter.md` - For creating tests that reproduce bugs
- `documentation-generator.md` - For documenting test procedures

## Tags

`testing` `unit-tests` `test-automation` `quality-assurance` `development` `debugging`
```


### 📁 Categoria: Education

#### ✨ Prompt: Education Prompts

```
This directory contains prompts for educational and learning applications.

## Categories

- **Lesson Planning**: Creating educational content and curricula
- **Assessment**: Quiz and test generation
- **Explanation**: Breaking down complex concepts
- **Study Guides**: Learning aids and study materials
- **Interactive Learning**: Engaging educational activities
- **Tutoring**: Personalized learning assistance

## Example Prompts

- `lesson-plan-generator.md` - Create comprehensive lesson plans and curricula
- `quiz-generator.md` - Generate quizzes and assessments for knowledge evaluation

## Educational Best Practices

- Adapt to different learning styles
- Include multiple assessment methods
- Provide clear learning objectives
- Encourage active participation

---
*Add your education prompts to this directory following the template structure.*
```

#### ✨ Prompt: Lesson Plan Generator

```
## Description

A comprehensive prompt for creating detailed, structured lesson plans for any subject, grade level, or learning objective. This prompt generates complete lesson plans with clear objectives, activities, assessments, and differentiation strategies.

## Usage

Use this prompt when you need to create engaging, educational lesson plans that follow best pedagogical practices. Ideal for teachers, instructional designers, tutors, and educational content creators.

## Prompt

```markdown
You are an expert educational designer and experienced teacher. Create a comprehensive lesson plan based on the following requirements:

**Subject:** [SUBJECT]
**Grade Level/Age Group:** [GRADE_LEVEL]
**Topic:** [TOPIC]
**Lesson Duration:** [DURATION]
**Learning Objectives:** [OBJECTIVES]
**Special Considerations:** [CONSIDERATIONS]

Please create a detailed lesson plan that includes:

1. **Lesson Overview**
   - Clear, measurable learning objectives
   - Brief summary of lesson content
   - Prerequisites and prior knowledge needed

2. **Materials and Resources**
   - Required materials and supplies
   - Technology needs
   - Handouts or worksheets
   - Reference materials

3. **Lesson Structure**
   - Opening/Hook (5-10 minutes)
   - Introduction/Review (10-15 minutes)
   - Main Activities (detailed breakdown)
   - Practice/Application
   - Closure/Summary

4. **Teaching Strategies**
   - Instructional methods used
   - Differentiation for various learning styles
   - Accommodations for special needs
   - Student engagement techniques

5. **Assessment Methods**
   - Formative assessment strategies
   - Summative assessment plan
   - Success criteria and rubrics
   - Exit tickets or quick checks

6. **Extension Activities**
   - Enrichment for advanced learners
   - Remediation for struggling students
   - Homework or follow-up activities

7. **Reflection Questions**
   - Questions for teacher self-reflection
   - Areas for improvement
   - Student feedback collection

Ensure the lesson plan is age-appropriate, engaging, and aligns with educational standards. Include specific timing for each activity and clear instructions for implementation.
```

## Example Input

**Subject:** Science
**Grade Level/Age Group:** 5th Grade (Ages 10-11)
**Topic:** The Water Cycle
**Lesson Duration:** 45 minutes
**Learning Objectives:** Students will be able to identify and explain the four main stages of the water cycle and describe how water moves through the environment
**Special Considerations:** Class includes 3 ELL students and 2 students with ADHD

## Example Output

### 5th Grade Science Lesson Plan: The Water Cycle

#### Lesson Overview

**Learning Objectives:**

- Students will identify the four stages of the water cycle (evaporation, condensation, precipitation, collection)
- Students will explain how water moves through each stage using scientific vocabulary
- Students will create a labeled diagram showing the water cycle process

**Lesson Summary:** Interactive exploration of the water cycle through multimedia, hands-on demonstration, and collaborative diagram creation.

**Prerequisites:** Basic understanding of states of matter (solid, liquid, gas)

### Materials and Resources

- Interactive whiteboard/projector
- Water cycle video (3 minutes)
- Clear containers, hot water, ice cubes for demonstration
- Water cycle diagram handouts
- Colored pencils/markers
- Vocabulary cards with visuals
- Digital timer

### Lesson Structure

### Opening Hook (5 minutes)

- Show dramatic time-lapse video of rain formation
- Ask: "Where does rain come from? Where does it go?"
- Record student predictions on whiteboard

### Introduction/Review (10 minutes)

- Quick review: "What are the three states of water?"
- Introduce water cycle vocabulary with visual cards
- Preview today's learning goals

### Main Activity 1: Water Cycle Demonstration (15 minutes)

- Live demonstration using hot water and ice
- Students observe and predict what happens
- Connect observation to real-world water cycle
- Introduce scientific vocabulary for each stage

### Main Activity 2: Collaborative Diagram Creation (10 minutes)

- Pairs work together to label water cycle diagram
- ELL students paired with strong English speakers
- Teacher circulates, providing targeted support

### Closure/Summary (5 minutes)

- Quick gallery walk of student diagrams
- Exit ticket: Draw one stage of the water cycle and explain it

### Teaching Strategies

**Instructional Methods:**

- Visual demonstrations and multimedia
- Collaborative learning
- Hands-on experimentation
- Graphic organizers

**Differentiation:**

- Visual vocabulary cards for ELL students
- Movement breaks for ADHD students
- Audio and visual learning components
- Flexible pairing arrangements

**Student Engagement:**

- Interactive predictions and observations
- Real-world connections
- Collaborative work opportunities

## Assessment Methods

**Formative Assessment:**

- Observation during demonstration
- Peer discussion monitoring
- Quick vocabulary checks

**Summative Assessment:**

- Labeled diagram accuracy (rubric provided)
- Exit ticket explanations
- Vocabulary usage in explanations

**Success Criteria:**

- Students can name all four stages
- Students can explain one stage in detail
- Students can identify water cycle in real scenarios

## Extension Activities

**Enrichment:**

- Research local water sources and their cycle journey
- Create water cycle comic strip
- Investigate how climate affects the water cycle

**Remediation:**

- Additional practice with vocabulary matching
- Simplified diagram with guided support
- Water cycle song or mnemonic device

**Homework:**

- Observe and record weather for one week
- Find water cycle examples around home

## Reflection Questions

- Did all students achieve the learning objectives?
- Which activities were most/least engaging?
- How effective were differentiation strategies?
- What would you modify for next time?
- How can you assess ELL student understanding more effectively?

## Variations

- **Elementary (K-2):** Simplify to basic water movement, use more songs and movements
- **Middle School:** Add detailed scientific processes, include human impact on water cycle
- **High School:** Connect to climate change, atmospheric pressure, and global water systems
- **Adult Learning:** Focus on practical applications, environmental implications

## Tips

- Use consistent visual cues throughout the lesson
- Provide sentence starters for ELL students
- Build in movement opportunities every 10-15 minutes
- Connect to local weather patterns students experience
- Use real-world examples from students' lives

## Related Prompts

- [Quiz Generator](quiz-generator.md) - Create assessments for this lesson

## Tags

`education` `lesson-planning` `science` `elementary` `differentiation` `assessment` `collaborative-learning`
```

#### ✨ Prompt: Quiz and Assessment Generator

```
## Description

An intelligent prompt for creating comprehensive quizzes, tests, and assessments for any subject matter. Generates questions across multiple difficulty levels and question types, with detailed answer keys and scoring rubrics.

## Usage

Perfect for educators, trainers, course creators, and students who need to create or practice with assessments. Supports formative and summative assessment creation with built-in pedagogical best practices.

## Prompt

```markdown
You are an expert assessment designer with deep knowledge of educational testing principles and question design. Create a comprehensive quiz/assessment based on these specifications:

**Subject/Topic:** [SUBJECT]
**Target Audience:** [AUDIENCE]
**Assessment Type:** [TYPE] (Quiz, Test, Midterm, Final, Practice, etc.)
**Duration:** [TIME_LIMIT]
**Total Points:** [POINTS]
**Difficulty Distribution:** [DIFFICULTY_LEVELS]
**Learning Objectives Assessed:** [OBJECTIVES]
**Question Type Preferences:** [QUESTION_TYPES]
**Special Requirements:** [REQUIREMENTS]

Please create an assessment that includes:

1. **Assessment Overview**
   - Clear instructions for students
   - Time allocation guidelines
   - Materials/resources allowed
   - Grading criteria overview

2. **Question Bank** (Distribute across difficulty levels)
   - **Easy Questions (20-30%):** Basic recall and understanding
   - **Medium Questions (40-50%):** Application and analysis
   - **Hard Questions (20-30%):** Synthesis and evaluation

3. **Question Formats** (Include variety):
   - Multiple choice with distractors
   - True/False with explanations
   - Short answer responses
   - Essay questions with rubrics
   - Matching exercises
   - Fill-in-the-blank
   - Problem-solving scenarios

4. **Answer Key**
   - Correct answers for all questions
   - Detailed explanations for complex items
   - Common misconceptions addressed
   - Point allocation breakdown

5. **Scoring Rubric**
   - Clear grading criteria
   - Point distribution rationale
   - Performance level descriptors
   - Feedback guidelines

6. **Assessment Analytics**
   - Estimated difficulty curve
   - Time recommendations per section
   - Skills/knowledge areas covered
   - Alignment with learning objectives

Ensure questions are:
- Clearly worded and unambiguous
- Free from bias and cultural assumptions
- Appropriately challenging for the target audience
- Aligned with stated learning objectives
- Varied in format to accommodate different learning styles
```

## Example Input

**Subject/Topic:** World War II - European Theater
**Target Audience:** High School (Grade 10)
**Assessment Type:** Unit Test
**Duration:** 50 minutes
**Total Points:** 100 points
**Difficulty Distribution:** 30% Easy, 50% Medium, 20% Hard
**Learning Objectives Assessed:** Analyze causes of WWII, evaluate key battles and strategies, assess impact on civilian populations
**Question Type Preferences:** Mix of multiple choice, short answer, and one essay
**Special Requirements:** Include primary source analysis, accommodate ELL students

## Example Output

### World War II European Theater - Unit Test

#### Assessment Overview

**Instructions:** Answer all questions clearly and completely. Use specific examples and evidence to support your answers. You have 50 minutes to complete this assessment.

**Materials Allowed:** None (closed book test)
**Point Distribution:** 100 total points
**Time Allocation:**

- Multiple Choice: 15 minutes (40 points)
- Short Answer: 20 minutes (40 points)  
- Essay: 15 minutes (20 points)

## Section A: Multiple Choice (40 points, 2 points each)

**1. (Easy) What event is commonly considered the beginning of World War II in Europe?**
a) The invasion of Poland by Germany
b) The bombing of Pearl Harbor
c) The Battle of Britain
d) The invasion of France

### Answer: A - The invasion of Poland by Germany on September 1, 1939

**2. (Medium) Which of the following best explains why the Maginot Line failed to protect France?**
a) It was poorly constructed and easily destroyed
b) Germany attacked through Belgium, bypassing the line
c) French soldiers abandoned their posts
d) The line was never completed

### Answer: B - Germany used blitzkrieg tactics through Belgium and the Ardennes, circumventing the static defenses

**3. (Hard) Analyze this quote from Churchill: "We shall never surrender." This statement primarily demonstrates:**
a) British military superiority
b) Churchill's political strategy to maintain morale
c) Certainty of Allied victory
d) British naval dominance

### Answer: B - This was a key rhetorical strategy to maintain civilian and military morale during Britain's darkest hour

[Continues with 17 more multiple choice questions...]

## Section B: Short Answer (40 points, 10 points each)

### 1. (Easy) Identify and briefly explain two causes of World War II in Europe. (10 points)

**Sample Answer:** Treaty of Versailles created economic hardship and resentment in Germany (5 points). Rise of fascist ideologies that promoted aggressive expansion (5 points). Other acceptable answers: Economic depression, failure of League of Nations, appeasement policies.

### 2. (Medium) Using the primary source excerpt provided, explain how Nazi propaganda portrayed the invasion of Poland. What techniques are evident? (10 points)

**Rubric:** Identifies specific propaganda techniques (4 points), explains how Poland invasion was justified (3 points), demonstrates understanding of source context (3 points)

### 3. (Hard) Compare and contrast the impact of WWII on civilian populations in Britain versus occupied France. Provide specific examples. (10 points)

**Rubric:** Clear comparison structure (2 points), specific examples from both countries (4 points), demonstrates understanding of occupation vs. bombing (4 points)

### 4. (Medium) Evaluate the effectiveness of the Blitzkrieg strategy in the early stages of WWII. (10 points)

**Sample Answer:** Highly effective initially - rapid conquest of Poland, Denmark, Norway, France (4 points). Advantages: speed, coordination of air/ground forces, psychological impact (3 points). Limitations: required specific conditions, less effective in USSR (3 points)

## Section C: Essay Question (20 points)

**Choose ONE of the following essay prompts:**

**Option A:** Analyze the factors that led to Germany's early military successes in WWII. How did these same factors eventually contribute to their defeat?

**Option B:** Evaluate the statement: "World War II was not just a military conflict but a war for civilian populations." Support your argument with specific examples.

### Essay Rubric (20 points total)

- **Thesis Statement (4 points):** Clear, arguable thesis that addresses the prompt
- **Evidence and Examples (8 points):** Specific, relevant historical evidence with accurate details
- **Analysis and Argumentation (6 points):** Logical reasoning, cause-and-effect relationships, evaluation of significance
- **Organization and Writing (2 points):** Clear structure, proper grammar, historical vocabulary

## Answer Key Summary

**Section A:** 1-A, 2-B, 3-B, 4-C, 5-A, 6-D, 7-B, 8-A, 9-C, 10-B, 11-D, 12-A, 13-C, 14-B, 15-A, 16-D, 17-B, 18-C, 19-A, 20-B

**Section B:** Detailed rubrics provided above for each question with point allocations and acceptable answer variations.

**Section C:** Holistic rubric focusing on historical thinking skills and content knowledge demonstration.

## Assessment Analytics

**Difficulty Distribution:** 30% recall/understanding, 50% application/analysis, 20% synthesis/evaluation
**Skills Assessed:** Content knowledge, source analysis, comparative thinking, argumentative writing
**Time Estimates:** Most students should complete within 45-50 minutes
**Differentiation Notes:** Key terms can be provided for ELL students; extra time may be needed for essay section

## Variations

- **Elementary:** Focus on basic facts, timeline activities, picture-based questions
- **College Level:** Include historiography, complex source analysis, counter-argument evaluation
- **Online Format:** Add multimedia elements, adaptive questioning, immediate feedback
- **Formative Assessment:** Create shorter, low-stakes versions for regular check-ins

## Tips

- Review questions for cultural bias and accessibility
- Include a mix of question types to accommodate different learning preferences
- Provide clear time guidance for each section
- Consider offering question choices to reduce test anxiety
- Use primary sources to develop critical thinking skills

## Related Prompts

- [Lesson Plan Generator](lesson-plan-generator.md) - Create lessons to prepare for this assessment

## Tags

`education` `assessment` `quiz` `testing` `formative` `summative` `differentiation` `rubrics` `question-design`
```


### 📁 Categoria: Examples

#### ✨ Prompt: Example Use Cases and Outputs

```
This directory contains real-world examples of how to use the prompts in the library, along with sample outputs to demonstrate their effectiveness.

## Categories

### Development Examples

- **Code Review Example**: Complete code review with before/after code samples
- **Architecture Planning**: Full system design for an e-commerce platform
- **Bug Fixing**: Step-by-step debugging of a production issue

### Writing Examples  

- **Technical Documentation**: API documentation creation process
- **Email Templates**: Business email examples for different scenarios
- **Content Creation**: Blog post and marketing copy examples

### Business Examples

- **Meeting Summaries**: Board meeting and team standup summaries
- **Strategic Planning**: Market analysis and business plan examples
- **Proposal Writing**: Client proposals and project estimates

### Creative Examples

- **Brainstorming Sessions**: Innovation workshops and idea generation
- **Content Strategy**: Social media and marketing campaign planning
- **Design Concepts**: UI/UX and brand design briefs

## How to Use Examples

1. **Find Relevant Example**: Browse by category or search for your use case
2. **Review Input**: See what information was provided to the AI
3. **Study Output**: Examine the quality and structure of results
4. **Adapt for Your Needs**: Modify the approach for your specific situation

## Contributing Examples

To add your own examples:

1. Use a real scenario (anonymize sensitive information)
2. Include both the prompt input and the generated output
3. Add commentary on what worked well and what could be improved
4. Follow the naming convention: `category-usecase-example.md`

---

*Examples are updated regularly to showcase best practices and new prompt techniques.*

## Structure

Each example follows this format:

- **Input**: The original prompt and any provided context
- **Output**: The AI's response
- **Analysis**: What worked well and areas for improvement
- **Variations**: How the prompt could be modified for different results

## Output Categories

### Development Outputs

- Code review sessions
- Documentation generation
- Architecture planning outputs

### Writing Outputs

- Blog post drafts
- Technical documentation
- Marketing copy samples

### Analysis Examples

- Data interpretation reports
- Research summaries
- Decision frameworks in action

### Creative Outputs

- Story excerpts
- Character profiles
- Creative brainstorming sessions

### Business Outputs

- Strategic plans
- Market analysis reports
- Process optimization recommendations

### Education Examples

- Lesson plans
- Quiz questions
- Study guides

### Productivity Examples

- Task prioritization matrices
- Schedule optimizations
- Goal setting frameworks

## Learning from Examples

1. Review examples similar to your use case
2. Note what makes an example effective
3. Adapt successful patterns to your needs
4. Learn from less successful examples

---
*Add your example outputs to this directory to help others learn effective prompt usage.*
```

#### ✨ Prompt: Code Review Example

```
## Scenario

A senior developer is reviewing a junior developer's pull request for a user authentication function. The code works but needs improvement for production readiness.

## Input Provided to AI

**Code to Review:**

```python
def login_user(username, password):
    users = [
        {"username": "admin", "password": "admin123"},
        {"username": "user1", "password": "password"},
        {"username": "user2", "password": "test123"}
    ]
    
    for user in users:
        if user["username"] == username and user["password"] == password:
            return True
    return False

def register_user(username, password):
    if len(password) < 6:
        return "Password too short"
    return "User registered successfully"
```

**Focus Areas:** Security, best practices, error handling

## AI Output

### Code Review Analysis

**CRITICAL Security Issues:**

1. **Plaintext Password Storage** (Line 3-7)
   - **Issue**: Passwords stored in plaintext arrays
   - **Risk**: Complete credential exposure if code is compromised
   - **Fix**: Implement proper password hashing with bcrypt/argon2

2. **Hardcoded User Database** (Line 2-6)
   - **Issue**: User credentials hardcoded in source code
   - **Risk**: Credentials visible in version control
   - **Fix**: Move to secure database with environment-based config

**HIGH Priority Issues:**

1. **No Input Validation** (Both functions)
   - **Issue**: No validation for None/empty inputs
   - **Risk**: Runtime errors and potential injection attacks
   - **Fix**: Add comprehensive input sanitization

2. **Weak Password Policy** (Line 2, register_user)
   - **Issue**: Only checks length, no complexity requirements
   - **Risk**: Vulnerable to brute force attacks
   - **Fix**: Implement strong password validation

**MEDIUM Priority Issues:**

1. **No Rate Limiting**
   - **Issue**: Unlimited login attempts possible
   - **Risk**: Brute force vulnerability
   - **Fix**: Add login attempt tracking and temporary lockouts

2. **Poor Error Messages** (register_user)
   - **Issue**: Generic error messages
   - **Risk**: Poor user experience
   - **Fix**: Provide specific, helpful error descriptions

### Recommended Improvements

```python
import bcrypt
import re
from typing import Optional
from datetime import datetime, timedelta

class UserAuthenticator:
    def __init__(self, db_connection):
        self.db = db_connection
        self.failed_attempts = {}
        self.lockout_duration = timedelta(minutes=15)
    
    def login_user(self, username: str, password: str) -> dict:
        # Input validation
        if not username or not password:
            return {"success": False, "error": "Username and password required"}
        
        # Check for account lockout
        if self._is_account_locked(username):
            return {"success": False, "error": "Account temporarily locked"}
        
        # Fetch user from database
        user = self.db.get_user_by_username(username)
        if not user:
            self._record_failed_attempt(username)
            return {"success": False, "error": "Invalid credentials"}
        
        # Verify password hash
        if bcrypt.checkpw(password.encode('utf-8'), user['password_hash']):
            self._clear_failed_attempts(username)
            return {"success": True, "user_id": user['id']}
        else:
            self._record_failed_attempt(username)
            return {"success": False, "error": "Invalid credentials"}
    
    def register_user(self, username: str, password: str, email: str) -> dict:
        # Comprehensive validation
        validation_result = self._validate_registration_data(username, password, email)
        if not validation_result["valid"]:
            return {"success": False, "errors": validation_result["errors"]}
        
        # Check if user exists
        if self.db.user_exists(username, email):
            return {"success": False, "error": "User already exists"}
        
        # Hash password and save user
        password_hash = bcrypt.hashpw(password.encode('utf-8'), bcrypt.gensalt())
        user_id = self.db.create_user(username, password_hash, email)
        
        return {"success": True, "user_id": user_id}
    
    def _validate_registration_data(self, username: str, password: str, email: str) -> dict:
        errors = []
        
        if not username or len(username) < 3:
            errors.append("Username must be at least 3 characters")
        
        if not self._is_strong_password(password):
            errors.append("Password must be at least 8 characters with uppercase, lowercase, number, and special character")
        
        if not re.match(r'^[^@]+@[^@]+\.[^@]+$', email or ''):
            errors.append("Valid email address required")
        
        return {"valid": len(errors) == 0, "errors": errors}
```

## Analysis

### What Worked Well

- Clear identification of critical security vulnerabilities
- Prioritized issues by severity level
- Provided specific, actionable fixes
- Included improved code example with proper patterns

### Areas for Improvement

- Could include more specific examples of attack vectors
- Missing discussion of logging and monitoring requirements
- Could suggest specific testing strategies for the fixes

### Key Takeaways

1. Security should always be the top priority in code reviews
2. Provide constructive, specific feedback with examples
3. Explain the "why" behind recommendations
4. Offer concrete solutions, not just problem identification

## Variations

- **Quick Review**: Focus only on critical issues for faster turnaround
- **Mentoring Style**: Include more educational context for junior developers
- **Production Focus**: Emphasize scalability and monitoring aspects
- **Security Audit**: Deep dive into all potential security vulnerabilities
```


### 📁 Categoria: Productivity

#### ✨ Prompt: Productivity Prompts

```
This directory contains prompts for general productivity and task management.

## Categories

- **Task Management**: Organizing and prioritizing tasks
- **Time Management**: Optimizing schedules and time usage
- **Goal Setting**: Setting and tracking objectives
- **Decision Making**: Frameworks for making decisions
- **Organization**: Systems for organizing information and workflows
- **Automation**: Streamlining repetitive processes

## Example Prompts

- `task-prioritization.md` - Intelligent task prioritization and workflow optimization
- `schedule-optimizer.md` - Optimize schedules and time allocation
- `goal-setter.md` - Set and track meaningful goals with structured planning

## Productivity Tips

- Focus on actionable outcomes
- Use clear metrics and deadlines
- Consider personal work styles
- Integrate with existing systems

---
*Add your productivity prompts to this directory following the template structure.*
```

#### ✨ Prompt: Goal Setting & Tracking System

```
## Description

Creates SMART goals with actionable plans, milestones, and tracking systems. Helps break down large objectives into manageable steps and provides frameworks for monitoring progress and maintaining accountability.

## Usage

Provide your aspirations, current situation, and timeframe. Include information about resources, constraints, and success criteria. Works for personal goals, professional objectives, team targets, and project outcomes.

## Prompt

```markdown
Help me create a comprehensive goal-setting and tracking system for the following objective:

**Goal Information:**
- **Primary Objective:** [What you want to achieve]
- **Timeframe:** [When you want to achieve this - weeks, months, years]
- **Category:** [Personal/Professional/Health/Financial/Learning/Other]
- **Motivation:** [Why this goal is important to you]

**Current Situation:**
- **Starting Point:** [Where you are now related to this goal]
- **Previous Attempts:** [Any past efforts toward this goal and what happened]
- **Existing Resources:** [Skills, tools, support, budget you already have]
- **Current Obstacles:** [Known challenges or barriers]

**Context & Constraints:**
- **Available Time:** [How much time you can dedicate daily/weekly]
- **Budget/Resources:** [Financial or resource limitations]
- **Support System:** [People who can help or accountability partners]
- **Competing Priorities:** [Other goals or responsibilities that might conflict]

**Success Criteria:**
- **Primary Metric:** [How you'll measure success - specific and quantifiable]
- **Secondary Indicators:** [Other signs of progress]
- **Milestone Markers:** [Key achievements along the way]

Please create:

1. **SMART Goal Formulation**
   - Specific, Measurable, Achievable, Relevant, Time-bound version
   - Clear success definition
   - Quantifiable metrics

2. **Action Plan Breakdown**
   - Major phases or stages
   - Specific action steps for each phase
   - Dependencies and prerequisites
   - Resource requirements for each step

3. **Timeline & Milestones**
   - Detailed timeline with key dates
   - Progress checkpoints
   - Early win opportunities
   - Buffer time for setbacks

4. **Tracking System**
   - Daily/weekly/monthly tracking methods
   - Progress measurement tools
   - Review and adjustment process
   - Accountability mechanisms

5. **Risk Management**
   - Potential obstacles and setbacks
   - Contingency plans
   - Motivation maintenance strategies
   - Course correction protocols

6. **Support Structure**
   - Resources and tools needed
   - People to involve and how
   - External help or expertise required
   - Celebration and reward system

**Additional Context:**
[Any specific challenges, past failures to learn from, or unique circumstances to consider]
```

## Example Input

```markdown
**Goal Information:**
- **Primary Objective:** Launch a freelance web development business
- **Timeframe:** 12 months to be earning $5,000/month consistently
- **Category:** Professional/Financial
- **Motivation:** Want career flexibility, work-life balance, and higher earning potential

**Current Situation:**
- **Starting Point:** Full-time software developer, 3 years experience, some side projects
- **Previous Attempts:** Started freelancing twice but gave up after 2-3 months due to lack of clients
- **Existing Resources:** Strong technical skills, basic portfolio, $5,000 savings, home office setup
- **Current Obstacles:** Limited marketing knowledge, no established network, time constraints with full-time job

**Context & Constraints:**
- **Available Time:** 15-20 hours per week (evenings and weekends)
- **Budget/Resources:** $3,000 available for business setup and marketing
- **Support System:** Spouse supports the plan, one friend who's successful freelancer
- **Competing Priorities:** Current job performance, family time, maintaining health

**Success Criteria:**
- **Primary Metric:** $5,000/month in freelance income for 3 consecutive months
- **Secondary Indicators:** 10+ regular clients, 90%+ client satisfaction, wait list for services
- **Milestone Markers:** First paid client, first $1,000 month, first $3,000 month, quitting day job
```

## Example Output

```markdown
# Freelance Web Development Business - Goal Achievement Plan

## SMART Goal Formulation

### Primary Goal
**Launch a profitable freelance web development business generating $5,000+ monthly recurring revenue within 12 months, with sufficient client pipeline to support transitioning from full-time employment to independent freelancing.**

### SMART Breakdown
- **Specific**: Freelance web development business focusing on small-medium businesses
- **Measurable**: $5,000/month for 3 consecutive months + 10 regular clients
- **Achievable**: Building on existing 3 years experience + proven market demand
- **Relevant**: Aligns with career flexibility and earning goals
- **Time-bound**: 12 months to achieve, with quarterly milestones

### Success Definition
- Monthly recurring revenue of $5,000+ for 3 consecutive months
- Client satisfaction rating of 90%+ (verified reviews/testimonials)
- 3-month pipeline of confirmed work
- Successful transition from full-time employment

## Action Plan Breakdown

### Phase 1: Foundation Building (Months 1-3)
**Goal**: Establish business fundamentals and initial market presence

#### Month 1: Business Setup
- [ ] **Week 1**: Business registration and legal setup
  - Register business name and get necessary permits
  - Open business bank account
  - Set up accounting system (QuickBooks/FreshBooks)
  - Create basic contracts and invoice templates

- [ ] **Week 2**: Brand and Portfolio Development
  - Design professional logo and branding
  - Rebuild portfolio website with 5 best projects
  - Write compelling service descriptions and pricing
  - Create case studies from past side projects

- [ ] **Week 3**: Service Definition and Pricing
  - Define 3 core service packages (Basic/Standard/Premium)
  - Research competitor pricing and position offerings
  - Create service delivery workflows and timelines
  - Develop project questionnaire and onboarding process

- [ ] **Week 4**: Tools and Systems Setup
  - Set up project management system (Asana/Monday)
  - Create client communication templates
  - Establish file sharing and collaboration systems
  - Set up time tracking and invoicing workflows

#### Month 2: Market Research and Positioning
- [ ] **Week 1**: Target Market Analysis
  - Identify 3 specific industries to focus on
  - Research their common pain points and needs
  - Analyze 10 potential competitors in each niche
  - Create ideal client persona profiles

- [ ] **Week 2**: Content Strategy Development
  - Plan 50 blog post topics relevant to target clients
  - Create content calendar for 6 months
  - Develop lead magnets (free resources/templates)
  - Set up email marketing system and sequences

- [ ] **Week 3**: Network Building Foundation
  - Join 5 relevant online communities and forums
  - Attend 2 local business networking events
  - Connect with 50 potential clients on LinkedIn
  - Reach out to 10 past colleagues for referrals

- [ ] **Week 4**: Initial Marketing Campaigns
  - Launch LinkedIn outreach campaign (10 contacts/week)
  - Start publishing weekly blog content
  - Create and share free resources on social media
  - Begin building email list with content marketing

#### Month 3: Client Acquisition
- [ ] **Week 1**: Direct Outreach Campaign
  - Identify 100 target businesses needing web services
  - Create personalized outreach templates
  - Launch email outreach campaign (20 emails/week)
  - Follow up with warm leads from networking

- [ ] **Week 2**: Proposal and Pricing Optimization
  - Create 3 different proposal templates
  - A/B test pricing strategies with initial prospects
  - Refine service packages based on market feedback
  - Develop objection handling scripts

- [ ] **Week 3**: First Client Acquisition
  - Convert first paying client
  - Deliver exceptional first project
  - Document process and create case study
  - Ask for testimonial and referrals

- [ ] **Week 4**: Process Refinement
  - Analyze what worked in client acquisition
  - Refine marketing messages and positioning
  - Scale successful outreach methods
  - Plan Phase 2 growth strategies

### Phase 2: Growth and Scaling (Months 4-8)
**Goal**: Build consistent client pipeline and increase monthly revenue

#### Revenue Targets
- Month 4: $1,000 revenue (2-3 clients)
- Month 5: $1,500 revenue (3-4 clients)
- Month 6: $2,500 revenue (4-5 clients)
- Month 7: $3,500 revenue (5-6 clients)
- Month 8: $4,000 revenue (6-7 clients)

#### Key Activities
- **Client Delivery Excellence**: Focus on over-delivering to generate referrals
- **Content Marketing Scale**: Publish 2 blog posts/week, guest posting
- **Networking Expansion**: Join industry associations, speak at events
- **Service Diversification**: Add maintenance packages and additional services
- **Team Building**: Consider subcontracting for overflow work

### Phase 3: Stabilization and Transition (Months 9-12)
**Goal**: Achieve $5,000+ monthly recurring revenue and prepare for full-time transition

#### Revenue Targets
- Month 9: $4,500 revenue (7-8 clients)
- Month 10: $5,000 revenue (8-9 clients)
- Month 11: $5,500 revenue (9-10 clients)
- Month 12: $6,000 revenue (10+ clients) + transition planning

#### Key Activities
- **Revenue Stabilization**: Focus on recurring contracts and retainer clients
- **Operational Efficiency**: Streamline all processes for scale
- **Team Expansion**: Hire part-time help for admin and overflow work
- **Transition Planning**: Negotiate part-time arrangement or plan resignation

## Timeline & Milestones

### Quarter 1 Milestones (Months 1-3)
- [ ] Business legally established and operational
- [ ] Professional portfolio website live
- [ ] First paying client acquired
- [ ] $500+ in revenue generated
- [ ] 100+ prospects in pipeline

### Quarter 2 Milestones (Months 4-6)
- [ ] $2,500 monthly revenue achieved
- [ ] 5+ satisfied clients with testimonials
- [ ] Content marketing producing leads
- [ ] Referral system generating new business
- [ ] Waiting list for services beginning

### Quarter 3 Milestones (Months 7-9)
- [ ] $4,000+ monthly revenue achieved
- [ ] 90%+ client satisfaction rate
- [ ] Team member hired for support
- [ ] Industry recognition or speaking opportunity
- [ ] 3-month revenue pipeline secured

### Quarter 4 Milestones (Months 10-12)
- [ ] $5,000+ monthly revenue for 3 consecutive months
- [ ] 10+ regular clients with ongoing relationships
- [ ] Full-time transition plan approved
- [ ] 6-month business sustainability demonstrated
- [ ] Exit strategy from current job executed

## Tracking System

### Daily Tracking (5 minutes/day)
- Hours worked on freelance business
- Number of outreach contacts made
- Content pieces created or published
- Client work completed
- Revenue generated

### Weekly Reviews (30 minutes/week)
- **Metrics Review**: Revenue, leads, conversion rates
- **Goal Progress**: Are weekly targets being met?
- **Activity Analysis**: Which activities drove best results?
- **Next Week Planning**: Prioritize high-impact activities
- **Problem Solving**: Address any roadblocks or challenges

### Monthly Assessments (2 hours/month)
- **Financial Review**: Profit/loss, cash flow, expense analysis
- **Client Feedback**: Satisfaction surveys and improvement areas
- **Market Analysis**: Competitive landscape and opportunity changes
- **Strategy Adjustment**: Modify tactics based on results
- **Goal Recalibration**: Adjust targets if needed based on progress

### Tracking Tools
- **Revenue Tracking**: Spreadsheet with monthly/weekly breakdowns
- **Lead Pipeline**: CRM system (HubSpot free tier or Airtable)
- **Time Tracking**: Toggle or Harvest for project time
- **Goal Progress**: Visual dashboard with key metrics
- **Client Satisfaction**: Regular feedback forms and review monitoring

## Risk Management

### Potential Obstacles & Solutions

#### 1. Time Management Challenges
**Risk**: Burnout from full-time job + 15-20 hours freelancing
**Mitigation**: 
- Start with 10 hours/week and gradually increase
- Batch similar activities to maximize efficiency
- Use time-blocking to protect family time
- Consider reducing full-time job to 4 days if possible

#### 2. Client Acquisition Difficulties
**Risk**: Struggling to find paying clients
**Mitigation**:
- Have 3 different client acquisition channels active
- Lower initial pricing to build portfolio and testimonials
- Offer payment plans to reduce client financial barriers
- Partner with other freelancers for referral exchanges

#### 3. Cash Flow Problems
**Risk**: Irregular income affecting financial stability
**Mitigation**:
- Maintain 6-month emergency fund
- Negotiate 50% deposits on all projects
- Offer monthly retainer packages for recurring revenue
- Keep full-time job until 3 months of $5K+ revenue achieved

#### 4. Scope Creep and Project Management
**Risk**: Projects taking longer than estimated, reducing profitability
**Mitigation**:
- Create detailed contracts with clear scope boundaries
- Build 20% buffer time into all estimates
- Implement change order process for additional work
- Track time meticulously to improve future estimates

### Motivation Maintenance Strategies
- **Progress Visualization**: Monthly visual progress charts
- **Celebration Milestones**: Reward achievement of each major milestone
- **Accountability Partner**: Weekly check-ins with successful freelancer friend
- **Community Support**: Join freelancer communities for encouragement
- **Success Reminders**: Keep list of reasons why this goal matters

## Support Structure

### Resources Needed
- **Financial**: $3,000 budget allocated across 12 months ($250/month average)
- **Educational**: Online courses on freelancing, marketing, sales ($500)
- **Tools & Software**: Website, CRM, accounting, design tools ($100/month)
- **Marketing**: Content creation, advertising, networking events ($150/month)

### People to Involve
- **Accountability Partner**: Friend who's successful freelancer (weekly check-ins)
- **Spouse Support**: Understanding of time commitment and income fluctuation
- **Professional Network**: Former colleagues, industry connections for referrals
- **Mentorship**: Find experienced freelancer willing to provide monthly advice

### External Help
- **Legal**: Lawyer for contract templates and business setup ($500)
- **Accounting**: Bookkeeper for tax planning and financial management ($200/month starting month 6)
- **Marketing**: Consider marketing consultant if stuck on client acquisition ($300 one-time)
- **Technical**: Backup developer for overflow work (revenue sharing model)

### Celebration & Reward System
- **First Client**: Dinner at favorite restaurant
- **$1,000 Month**: Weekend getaway
- **$2,500 Month**: New laptop or business equipment upgrade
- **$5,000 Month**: Week-long vacation to celebrate
- **Goal Achievement**: Major celebration and transition planning

## Success Probability Assessment

### High Probability Factors (Strengths)
- ✅ Strong technical foundation (3 years experience)
- ✅ Financial cushion for business investment
- ✅ Supportive spouse and realistic timeline
- ✅ Previous freelancing attempts provide learning experience
- ✅ Clear motivation and specific financial target

### Risk Factors to Monitor
- ⚠️ Time management with full-time job
- ⚠️ Marketing and sales skills development needed
- ⚠️ Client acquisition track record to be established
- ⚠️ Consistency and persistence over 12 months

### Overall Success Probability: 75%
This goal is highly achievable given the strong technical foundation, realistic timeline, and comprehensive planning. The main success factors will be consistent execution, effective client acquisition, and maintaining motivation through inevitable challenges.

## Next Immediate Actions (This Week)
1. **Monday**: Register business name and research legal requirements
2. **Tuesday**: Open business bank account and set up accounting system
3. **Wednesday**: Begin portfolio website redesign and content creation
4. **Thursday**: Research and join 3 relevant online communities
5. **Friday**: Create first version of service packages and pricing
6. **Weekend**: Set up project management and tracking systems

This comprehensive plan provides the structure, accountability, and flexibility needed to successfully achieve your freelance business goal while managing the transition from full-time employment.
```

## Variations

- **Team Goals**: Collaborative goal-setting for teams and organizations
- **Habit Formation**: Focus on building specific habits and routines
- **Learning Goals**: Educational and skill development objectives
- **Health & Fitness**: Physical wellness and lifestyle change goals

## Tips

- Make goals specific and measurable to track progress effectively
- Break large goals into smaller, manageable milestones
- Build in accountability systems and regular check-ins
- Plan for setbacks and have contingency strategies ready
- Celebrate progress along the way, not just final achievement
- Review and adjust goals regularly based on changing circumstances
- Connect goals to your deeper values and motivations

## Related Prompts

- `task-prioritization.md` - For prioritizing daily actions toward goals
- `schedule-optimizer.md` - For allocating time to goal-related activities
- `brainstorming-session.md` - For generating creative approaches to achieve goals

## Tags

`goal-setting` `planning` `productivity` `achievement` `tracking` `accountability` `motivation`
```

#### ✨ Prompt: Schedule Optimizer

```
## Description

Analyzes your current schedule and commitments to create optimized daily and weekly schedules that maximize productivity, minimize conflicts, and ensure work-life balance. Considers energy levels, priorities, and time constraints.

## Usage

Provide your current schedule, commitments, priorities, and personal work preferences. Include information about energy patterns, meeting requirements, and any constraints. Best used for weekly planning or when experiencing scheduling conflicts.

## Prompt

```markdown
Help me optimize my schedule for maximum productivity and balance. Please analyze my current situation and create an improved schedule:

**Current Schedule Analysis:**
[Provide your current daily/weekly schedule including meetings, tasks, and commitments]

**Priorities & Goals:**
- **Primary Goals:** [Top 3 goals for this week/month]
- **Important Tasks:** [High-priority tasks that need scheduling]
- **Deadlines:** [Upcoming deadlines and time-sensitive items]
- **Regular Commitments:** [Recurring meetings, appointments, responsibilities]

**Personal Work Patterns:**
- **Peak Energy Times:** [When you're most productive - morning/afternoon/evening]
- **Low Energy Times:** [When you need lighter tasks or breaks]
- **Preferred Work Blocks:** [How long you like to work on focused tasks]
- **Meeting Preferences:** [Best times for meetings, maximum meetings per day]

**Constraints & Requirements:**
- **Fixed Commitments:** [Unchangeable appointments, family time, etc.]
- **Work Hours:** [Available working hours, time zone considerations]
- **Break Needs:** [Lunch breaks, exercise time, personal time]
- **Buffer Time:** [Time needed between meetings, travel time]

**Current Challenges:**
[Describe any scheduling problems you're experiencing - too many meetings, no focus time, work-life imbalance, etc.]

Please provide:

1. **Schedule Analysis**
   - Identify current inefficiencies and conflicts
   - Assess alignment with energy patterns
   - Evaluate work-life balance

2. **Optimized Schedule**
   - Restructured daily/weekly timeline
   - Time blocks for different types of work
   - Strategic placement of meetings and tasks

3. **Implementation Strategy**
   - Steps to transition to new schedule
   - How to communicate changes to others
   - Systems for maintaining the new schedule

4. **Contingency Plans**
   - How to handle unexpected meetings or urgent tasks
   - Flexible blocks for high-priority items
   - Recovery strategies when schedule gets disrupted

**Additional Preferences:**
[Any specific tools you use (calendar apps, task managers), personal constraints, or scheduling preferences]
```

## Example Input

```markdown
**Current Schedule Analysis:**
Monday-Friday, 9 AM - 6 PM work schedule with:
- 15-20 meetings per week scattered throughout days
- 2-3 hours of focused project work time daily
- Lunch often skipped or eaten during meetings
- Email and Slack checking throughout the day
- Staying late 2-3 times per week to catch up on actual work

**Priorities & Goals:**
- **Primary Goals:** Complete Q2 product roadmap, improve team processes, maintain customer relationships
- **Important Tasks:** Strategic planning (4 hours), code review backlog (6 hours), one-on-ones with team (5 hours)
- **Deadlines:** Roadmap due Friday, customer presentation next Tuesday
- **Regular Commitments:** Team standup (daily 30 min), leadership meeting (weekly 1 hour)

**Personal Work Patterns:**
- **Peak Energy Times:** 9 AM - 12 PM and 2 PM - 4 PM
- **Low Energy Times:** Right after lunch (12-1 PM) and after 5 PM
- **Preferred Work Blocks:** 2-3 hour focused sessions for deep work
- **Meeting Preferences:** Morning meetings preferred, max 4 meetings per day

**Constraints & Requirements:**
- **Fixed Commitments:** Kid pickup at 6:30 PM, gym 3x/week at 7 AM
- **Work Hours:** 9 AM - 6 PM, occasional evening work acceptable
- **Break Needs:** 1-hour lunch break, 15-min break every 2 hours
- **Buffer Time:** 15 minutes between meetings for notes/transitions

**Current Challenges:**
Too many scattered meetings preventing deep work, constantly reacting to urgent requests, no time for strategic thinking, work bleeding into personal time
```

## Example Output

```markdown
# Optimized Schedule Analysis & Recommendations

## Current Schedule Analysis

### Identified Issues
1. **Fragmented Focus Time**: 15-20 meetings scattered throughout the week prevent deep work sessions
2. **Peak Energy Misalignment**: Best productivity hours (9 AM-12 PM) often consumed by reactive meetings
3. **Lack of Buffer Time**: Back-to-back meetings create stress and prevent proper preparation
4. **Reactive Scheduling**: No protected time for strategic work and important projects
5. **Poor Work-Life Boundaries**: Staying late indicates insufficient time allocation during core hours

### Current Efficiency Score: 4/10
- **Deep Work Time**: Only 2-3 hours daily vs. needed 4-5 hours
- **Meeting Density**: Too high at 3-4 meetings per day
- **Energy Alignment**: 30% of peak hours used optimally

## Optimized Schedule Structure

### Daily Schedule Framework

#### Monday & Wednesday (Deep Work Days)
```

9:00 - 9:30 AM    | Morning routine + priority review
9:30 - 12:00 PM   | 🔴 PROTECTED: Strategic work block (roadmap/planning)
12:00 - 1:00 PM   | Lunch break
1:00 - 1:30 PM    | Email/Slack batch processing
1:30 - 4:00 PM    | 🔴 PROTECTED: Project work block (code review/development)
4:00 - 4:15 PM    | Break + walk
4:15 - 5:30 PM    | Meetings (max 2, internal only)
5:30 - 6:00 PM    | Day wrap-up + tomorrow prep

```

#### Tuesday & Thursday (Collaboration Days)
```

9:00 - 9:30 AM    | Team standup + day planning
9:30 - 11:00 AM   | High-priority meetings (customer/leadership)
11:00 - 11:15 AM  | Buffer time
11:15 - 12:30 PM  | One-on-ones or team meetings
12:30 - 1:30 PM   | Lunch break
1:30 - 2:00 PM    | Low-energy tasks (admin, email)
2:00 - 4:00 PM    | Focused work block (smaller tasks)
4:00 - 5:30 PM    | Remaining meetings (max 2)
5:30 - 6:00 PM    | Communication cleanup + planning

```

#### Friday (Review & Planning Day)
```

9:00 - 10:30 AM   | Week review + next week planning
10:30 - 12:00 PM  | Team meetings/retrospectives
12:00 - 1:00 PM   | Lunch break
1:00 - 3:00 PM    | Catch-up work + process improvements
3:00 - 4:00 PM    | Customer/stakeholder communications
4:00 - 5:00 PM    | Learning/development time
5:00 - 6:00 PM    | Week wrap-up + documentation

```

### Weekly Optimization Strategy

#### Meeting Management
- **Total Meetings**: Reduce from 15-20 to 12 max per week
- **Meeting-Free Mornings**: Monday & Wednesday 9:30 AM - 12:00 PM sacred
- **Batched Meetings**: Cluster meetings on Tuesday/Thursday afternoons
- **Default 25/50 Minutes**: Build in natural buffers for all meetings

#### Energy Alignment
- **Peak Hours (9 AM-12 PM)**: Strategic work, complex problem-solving
- **Secondary Peak (2-4 PM)**: Collaborative work, important meetings
- **Low Energy (12-1 PM, 5-6 PM)**: Administrative tasks, email, planning

#### Focus Protection
- **4-Hour Deep Work Blocks**: Monday & Wednesday mornings
- **2-Hour Project Blocks**: Tuesday & Thursday afternoons
- **No-Interrupt Signals**: Clear calendar blocking + Slack status updates

## Implementation Strategy

### Week 1: Foundation Setting
1. **Calendar Audit**: Block protected time slots in calendar
2. **Team Communication**: Inform team of new availability patterns
3. **Meeting Rescheduling**: Move scattered meetings to designated collaboration days
4. **Tools Setup**: Configure Slack for batched notifications during focus time

### Week 2: Process Establishment
1. **Template Communications**: Create standard responses for meeting requests
2. **Boundary Testing**: Practice saying no to non-essential meeting requests
3. **Workflow Optimization**: Establish routines for each time block type
4. **Stakeholder Alignment**: Set expectations with key collaborators

### Week 3: Refinement
1. **Schedule Review**: Assess what's working and what needs adjustment
2. **Process Tweaks**: Modify time blocks based on actual needs
3. **Habit Formation**: Reinforce new patterns with accountability systems
4. **Expansion**: Apply principles to monthly and quarterly planning

### Communication Templates

#### For Meeting Requests
"Thanks for the meeting request. I have dedicated collaboration time on Tuesdays and Thursdays 1:30-5:30 PM. Would [specific time slot] work for you? This helps me maintain focus time for our project deliverables."

#### For Urgent Requests
"I see this is urgent. I have a protected work block until [time] but can address this at [next available slot]. If it truly can't wait, please call me directly."

## Contingency Plans

### Handling Urgent Meetings
- **Emergency Slots**: Keep 2 hours/week flexible for truly urgent items
- **Swap Strategy**: If urgent meeting needed during protected time, immediately reschedule equivalent focus time
- **Escalation Criteria**: Define what constitutes "urgent" to prevent scope creep

### Schedule Disruption Recovery
- **Same-Day Recovery**: If morning focus time lost, protect afternoon 2-4 PM block
- **Next-Day Compensation**: Schedule extra focus time next available deep work day
- **Weekly Reset**: Friday planning session to rebalance any week's disruptions

### Travel/Off-Site Days
- **Advance Planning**: Block focus time before and after travel days
- **Mobile Focus Time**: Identify tasks that can be done during travel
- **Catch-up Protocol**: Dedicated time slots for post-travel catch-up

## Expected Outcomes

### Productivity Improvements
- **25% More Deep Work**: From 10-15 hours to 18-20 hours per week
- **30% Better Meeting Efficiency**: Reduced context switching and better preparation
- **40% Less Overtime**: Proper time allocation eliminating evening work
- **50% Reduced Stress**: Predictable schedule with adequate buffer time

### Success Metrics (Track Weekly)
- Hours of uninterrupted focus time achieved
- Number of meetings that ran over scheduled time
- Instances of staying past 6 PM
- Completion rate of priority tasks/goals

### 30-Day Checkpoint Goals
- Roadmap completed on time without overtime
- Team satisfaction with availability and responsiveness
- Personal energy levels and work-life balance improvement
- Establishment of sustainable scheduling habits

This optimized schedule transforms you from reactive to proactive, protects your peak energy for highest-value work, and creates sustainable boundaries that improve both productivity and well-being.
```

## Variations

- **Team Schedule Optimization**: Coordinate schedules across team members
- **Project-Based Scheduling**: Optimize around specific project phases
- **Remote Work Optimization**: Focus on home office and virtual meeting challenges
- **Travel-Heavy Roles**: Optimize for frequent business travel and time zones

## Tips

- Start with small changes and gradually implement the full optimization
- Block focus time in your calendar like unmovable meetings
- Communicate your schedule patterns to frequent collaborators
- Review and adjust weekly - schedules should evolve with changing priorities
- Use calendar apps with color coding to visualize different types of time blocks
- Set boundaries early and consistently to train others on your availability

## Related Prompts

- `task-prioritization.md` - For determining what should go into your optimized schedule
- `meeting-summary.md` - For making meetings more efficient
- `goal-setter.md` - For aligning schedule with long-term objectives

## Tags

`productivity` `time-management` `scheduling` `work-life-balance` `efficiency` `planning`
```

#### ✨ Prompt: Task Prioritization Matrix

```
## Description

Helps organize and prioritize tasks using various prioritization frameworks like Eisenhower Matrix, MoSCoW method, and value-based scoring. Creates actionable task lists with clear priorities and deadlines.

## Usage

Provide your list of tasks, projects, or initiatives along with relevant context about deadlines, importance, and resources. Specify your preferred prioritization method or let the AI recommend the best approach for your situation.

## Prompt

```markdown
Help me prioritize the following tasks and create an organized action plan:

**Prioritization Context:**
- **Role/Position:** [Your role and responsibilities]
- **Time Frame:** [Daily/Weekly/Monthly planning horizon]
- **Current Workload:** [Current capacity and constraints]
- **Key Goals:** [Main objectives you're working toward]

**Tasks to Prioritize:**
[List all tasks, projects, or initiatives that need prioritization]

For each task, please consider:
- **Urgency:** How time-sensitive is this task?
- **Importance:** How critical is this to your goals?
- **Effort Required:** How much time/energy will this take?
- **Dependencies:** Does this block other work or people?
- **Impact:** What's the potential value or consequence?

**Prioritization Method:**
[Choose one or ask for recommendation]
- **Eisenhower Matrix:** Urgent/Important quadrants
- **MoSCoW Method:** Must have, Should have, Could have, Won't have
- **Value vs. Effort:** High impact, low effort tasks first
- **ICE Score:** Impact, Confidence, Ease scoring
- **Custom Approach:** Based on your specific criteria

**Additional Constraints:**
- **Deadlines:** [Any fixed deadlines or time constraints]
- **Resources:** [Team members, budget, or tool limitations]
- **Dependencies:** [Tasks that depend on others or external factors]
- **Energy Levels:** [When you're most/least productive]

Please provide:
1. **Prioritized Task List** with reasoning for each priority level
2. **Action Plan** with recommended sequence and timing
3. **Quick Wins** that can be completed immediately
4. **Time Blocking Suggestions** for optimal scheduling
5. **Risk Assessment** for high-priority items
6. **Regular Review Schedule** for maintaining priorities

**Personal Preferences:**
[Any specific working styles, preferences, or constraints to consider]
```

## Example Input

```markdown
**Prioritization Context:**
- **Role/Position:** Product Manager at a SaaS startup
- **Time Frame:** Weekly planning (40 hours available)
- **Current Workload:** Managing 3 active projects, regular meetings take 15 hours/week
- **Key Goals:** Launch new feature by end of quarter, improve customer retention, reduce support tickets

**Tasks to Prioritize:**
1. Finalize user research analysis for new dashboard feature
2. Write product requirements document for mobile app
3. Review and respond to 15 customer feedback emails
4. Prepare presentation for next week's board meeting
5. Conduct user interviews for retention study
6. Update project roadmap and timelines
7. Fix critical bug causing payment failures
8. Plan team offsite for next month
9. Review competitor analysis report
10. Optimize onboarding flow based on analytics
11. Schedule 1-on-1s with team members
12. Create documentation for new API endpoints

**Additional Constraints:**
- **Deadlines:** Board presentation due Friday, bug fix needed ASAP
- **Resources:** Engineering team at capacity, limited designer availability
- **Dependencies:** User research needed before finalizing mobile app requirements
- **Energy Levels:** Most focused 9-11 AM, low energy after 3 PM meetings
```

## Example Output

```markdown
# Weekly Task Prioritization Plan

## Priority Classification (Eisenhower Matrix)

### 🚨 Urgent & Important (Do First)
**1. Fix critical bug causing payment failures**
- **Why Priority 1:** Revenue impact, customer trust at risk
- **Time Estimate:** 4-6 hours (coordination with engineering)
- **Action:** Schedule emergency fix session today

**2. Prepare presentation for board meeting**
- **Why Priority 1:** Hard deadline, stakeholder visibility
- **Time Estimate:** 6 hours
- **Action:** Block Thursday morning for focused preparation

### ⭐ Important, Not Urgent (Schedule)
**3. Finalize user research analysis for dashboard feature**
- **Why High Priority:** Blocks Q4 feature development
- **Time Estimate:** 4 hours
- **Action:** Schedule for Tuesday AM (high energy time)

**4. Update project roadmap and timelines**
- **Why High Priority:** Team alignment, board presentation input
- **Time Estimate:** 3 hours
- **Action:** Complete before board presentation

**5. Conduct user interviews for retention study**
- **Why High Priority:** Directly supports retention goal
- **Time Estimate:** 5 hours (including scheduling and prep)
- **Action:** Schedule 3 interviews this week, 2 next week

### ⚡ Urgent, Not Important (Delegate/Minimize)
**6. Review and respond to customer feedback emails**
- **Why Lower Priority:** Important but can be batched
- **Time Estimate:** 2 hours
- **Action:** Batch process Friday afternoon

**7. Schedule 1-on-1s with team members**
- **Why Lower Priority:** Important for team but flexible timing
- **Time Estimate:** 30 minutes scheduling + 3 hours meetings
- **Action:** Delegate scheduling to assistant, do meetings next week

### 📋 Neither Urgent nor Important (Eliminate/Defer)
**8. Plan team offsite for next month**
- **Action:** Defer to next week or delegate to team lead

**9. Review competitor analysis report**
- **Action:** Defer to following week when less urgent items are handled

**10. Create documentation for API endpoints**
- **Action:** Delegate to engineering team or defer

---

## Recommended Weekly Schedule

### Monday (8 hours)
- **9:00-11:00 AM:** Emergency bug fix coordination (2 hours)
- **11:00-12:00 PM:** Project roadmap updates (1 hour)
- **1:00-3:00 PM:** Board presentation outline and data gathering (2 hours)
- **3:00-4:00 PM:** Customer feedback email batch (1 hour)
- **4:00-5:00 PM:** User interview scheduling and prep (1 hour)
- **5:00-5:30 PM:** Quick team check-ins (30 minutes)

### Tuesday (8 hours)
- **9:00-11:00 AM:** 🎯 User research analysis (2 hours - peak focus)
- **11:00-1:00 PM:** Continued user research analysis (2 hours)
- **2:00-4:00 PM:** User interviews (2 hours)
- **4:00-5:00 PM:** Board presentation content development (1 hour)
- **5:00-5:30 PM:** Team standup and priority adjustments (30 minutes)

### Wednesday (8 hours)
- **9:00-12:00 PM:** Board presentation creation and rehearsal (3 hours)
- **1:00-2:00 PM:** Finalize project roadmap updates (1 hour)
- **2:00-4:00 PM:** User interviews (2 hours)
- **4:00-5:00 PM:** Mobile app requirements planning (1 hour)
- **5:00-5:30 PM:** Progress review and Thursday planning (30 minutes)

### Thursday (8 hours)
- **9:00-11:00 AM:** Final board presentation preparation (2 hours)
- **11:00-12:00 PM:** Board presentation rehearsal (1 hour)
- **1:00-3:00 PM:** Board presentation delivery and follow-up (2 hours)
- **3:00-5:00 PM:** Onboarding flow optimization analysis (2 hours)
- **5:00-5:30 PM:** Week wrap-up and Friday planning (30 minutes)

### Friday (8 hours)
- **9:00-11:00 AM:** Mobile app requirements document start (2 hours)
- **11:00-12:00 PM:** Customer feedback email responses (1 hour)
- **1:00-2:00 PM:** 1-on-1 with team lead (1 hour)
- **2:00-4:00 PM:** Week review and next week planning (2 hours)
- **4:00-5:00 PM:** Administrative tasks and cleanup (1 hour)

---

## Quick Wins (Complete This Week)

### ✅ Immediate Actions (< 30 minutes each)
- Email engineering team about bug fix urgency
- Block calendar time for board presentation prep
- Send calendar invites for user interviews
- Update team on priority changes in Slack

### ✅ 1-Hour Actions
- Batch respond to urgent customer emails
- Update project status in management tools
- Schedule next week's 1-on-1 meetings
- Review and prioritize backlog items

---

## Risk Assessment & Mitigation

### High-Risk Items
**1. Bug Fix Complexity**
- **Risk:** May take longer than estimated, affecting other priorities
- **Mitigation:** Involve senior engineer early, prepare communication for stakeholders

**2. Board Presentation Quality**
- **Risk:** Insufficient time for proper preparation
- **Mitigation:** Start with existing templates, focus on key metrics only

**3. User Research Dependencies**
- **Risk:** Interview cancellations could delay analysis
- **Mitigation:** Schedule backup interviews, prepare alternative data sources

---

## Time Blocking Strategy

### Energy-Based Scheduling
- **High Focus Tasks (9-11 AM):** User research analysis, presentation creation
- **Medium Focus Tasks (11 AM-1 PM):** Documentation, planning work
- **Low Focus Tasks (After 3 PM):** Email responses, administrative work
- **Meeting Blocks:** Keep 1-3 PM for interviews and team interactions

### Buffer Time Management
- **Daily Buffer:** 30 minutes at end of each day for unexpected issues
- **Weekly Buffer:** Friday afternoon for catch-up and planning
- **Emergency Reserve:** 2 hours total across the week for critical issues

---

## Success Metrics

### This Week's Goals
- [ ] Critical bug resolved by Wednesday
- [ ] Board presentation delivered successfully
- [ ] User research analysis completed
- [ ] 5 user interviews conducted
- [ ] Project roadmap updated

### Weekly Review Questions
1. Did high-priority items get completed?
2. What caused delays or inefficiencies?
3. How accurate were time estimates?
4. What should be prioritized differently next week?
5. Are we making progress toward quarterly goals?

---

## Next Week Preview

### Priorities to Advance
- Complete mobile app requirements document
- Continue user interviews and retention analysis
- Plan team offsite (delegate to team lead)
- Review competitor analysis
- Start API documentation project

### Schedule Optimization
- Block more focused time for deep work
- Reduce meeting overhead where possible
- Batch similar tasks more effectively
- Build in more buffer time for unexpected priorities

This prioritization framework balances urgent business needs with strategic goals while accounting for your working style and constraints. The key is maintaining flexibility while protecting time for high-impact work.
```

## Variations

- **Daily Planning**: Focus on single-day task management and optimization
- **Project Prioritization**: Prioritize multiple projects or initiatives rather than individual tasks
- **Team Priorities**: Collaborative prioritization for team or department-level work
- **Goal-Based Planning**: Align tasks with specific objectives and key results (OKRs)

## Tips

- Be honest about time estimates - add 25% buffer for most tasks
- Consider your energy levels and schedule demanding work during peak hours
- Review and adjust priorities regularly as circumstances change
- Don't overcommit - it's better to do fewer things well
- Include time for unexpected urgent tasks in your planning
- Use the 2-minute rule: if something takes less than 2 minutes, do it immediately

## Related Prompts

- `meeting-summary.md` - For capturing action items from meetings to prioritize
- `email-templates.md` - For communicating priorities and deadlines
- `brainstorming-session.md` - For generating solutions to productivity challenges

## Tags

`productivity` `time-management` `prioritization` `planning` `organization` `task-management`
```


### 📁 Categoria: Templates

#### ✨ Prompt: Templates

```
This directory contains reusable templates for creating new prompts and organizing your prompt library.

## Available Templates

### `prompt-template.md`

The standard template for creating new prompts. Includes all necessary sections and formatting guidelines.

### `category-template.md`

Template for creating new category directories with proper documentation.

### `example-template.md`

Template for documenting example outputs and use cases.

## Usage Guidelines

1. **Copy the appropriate template** before creating new content
2. **Fill in all sections** - even if brief, each section provides value
3. **Follow the formatting** to maintain consistency across the library
4. **Include examples** whenever possible to help users understand usage
5. **Add relevant tags** to improve discoverability

## Best Practices

- Use clear, descriptive titles
- Write prompts that are specific but flexible
- Include variations for different use cases
- Test prompts before adding to the library
- Keep examples realistic and helpful

## Contributing

When adding new templates:

1. Follow the existing structure and format
2. Include comprehensive documentation
3. Provide clear usage instructions
4. Test with multiple AI models when possible

---
*Use these templates to maintain consistency and quality across the prompt library.*
```

#### ✨ Prompt: [Category Name]

```
Brief description of what this category contains and its purpose.

## Categories

- **Subcategory 1**: Description of this subcategory
- **Subcategory 2**: Description of this subcategory
- **Subcategory 3**: Description of this subcategory

## Example Prompts

- `example-prompt-1.md` - Brief description of what this prompt does
- `example-prompt-2.md` - Brief description of what this prompt does
- `example-prompt-3.md` - Brief description of what this prompt does

## Usage Guidelines

- [Guideline 1 for using prompts in this category]
- [Guideline 2 for best practices]
- [Guideline 3 for common use cases]

## Tips

- [Tip 1 for effective usage]
- [Tip 2 for customization]
- [Tip 3 for troubleshooting]

---
*Add your [category] prompts to this directory following the template structure.*
```

#### ✨ Prompt: Prompt Template

```
## Description

[Brief explanation of what this prompt does and its intended use case]

## Usage

[How to use this prompt effectively, including any prerequisites or setup]

## Prompt

```markdown
[The actual prompt text goes here - this is what you'll copy and paste into your AI tool]
```

## Example Input

```markdown
[Sample input data, context, or parameters that would be used with this prompt]
```

## Example Output

```markdown
[Expected or sample output showing what the AI should produce]
```

## Variations

- **Variation 1**: [Description of how to modify the prompt for different use cases]
- **Variation 2**: [Another modification or alternative approach]
- **Advanced**: [More complex version of the prompt]

## Tips

- [Best practice or recommendation]
- [Common pitfall to avoid]
- [Optimization suggestion]
- [When to use this prompt vs alternatives]

## Related Prompts

- [Link to similar or complementary prompts]
- [Cross-references to other categories]

## Tags

`[tag1]` `[tag2]` `[tag3]` `[category]`
```


### 📁 Categoria: Writing

#### ✨ Prompt: Writing Prompts

```
This directory contains prompts for various writing and content creation tasks.

## Categories

- **Technical Writing**: Documentation, tutorials, and technical content
- **Creative Writing**: Stories, poems, and creative content
- **Business Writing**: Proposals, reports, and professional communication
- **Marketing Copy**: Advertisements, social media, and promotional content
- **Email Templates**: Professional and personal email communication
- **Blog Posts**: Articles, opinion pieces, and informational content

## Example Prompts

- `technical-documentation.md` - Create clear, comprehensive technical documentation
- `email-templates.md` - Professional email templates for various scenarios
- `blog-post-generator.md` - Create engaging blog posts and articles
- `marketing-copy-creator.md` - Compelling marketing and sales copy
- `creative-story-generator.md` - Generate creative stories and narratives
- `prompt-generator.md` - Create structured, effective prompts for AI models
- `github-copilot-prompt-generator.md` - Generate specialized prompts for GitHub Copilot's agent mode
- `chinese-language-mode.md` - Ensure AI responses are delivered in Simplified Chinese

## Tips for Writing Prompts

- Be specific about tone, audience, and purpose
- Include style guidelines and formatting requirements
- Provide examples of desired output when possible
- Consider different writing styles and approaches

---
*Add your writing prompts to this directory following the template structure.*
```

#### ✨ Prompt: Blog Post Generator

```
## Description

This prompt helps you create engaging, SEO-optimized blog posts for various topics, audiences, and purposes with compelling headlines, structured content, and call-to-actions.

## Usage

Perfect for content marketing, thought leadership, educational content, product announcements, industry insights, and maintaining a consistent blog publishing schedule.

## Prompt

```markdown
You are an expert content writer and blog strategist. I need help creating a compelling blog post that engages readers and achieves specific goals.

**Blog Post Requirements:**
- Topic: [MAIN_TOPIC]
- Target audience: [AUDIENCE_DESCRIPTION]
- Word count: [TARGET_LENGTH]
- Tone: [PROFESSIONAL/CASUAL/EDUCATIONAL/CONVERSATIONAL]
- Primary goal: [INFORM/PERSUADE/ENTERTAIN/CONVERT]
- SEO keywords: [PRIMARY_AND_SECONDARY_KEYWORDS]

**Additional Context:**
- Industry/niche: [INDUSTRY]
- Brand voice: [BRAND_PERSONALITY]
- Call-to-action goal: [DESIRED_READER_ACTION]
- Content format preference: [LIST/NARRATIVE/HOW_TO/CASE_STUDY]

Please create a comprehensive blog post including:

1. **SEO-Optimized Headlines:**
   - 3-5 headline options with power words
   - Include primary keyword naturally
   - Consider emotional triggers and curiosity gaps
   - Aim for 50-60 characters for optimal SEO

2. **Blog Post Structure:**
   - Compelling introduction with hook
   - Clear subheadings (H2, H3) with keywords
   - Well-organized body paragraphs
   - Conclusion with summary and CTA
   - Meta description (150-160 characters)

3. **Content Elements:**
   - Opening hook to grab attention
   - Clear value proposition for readers
   - Supporting data, examples, or case studies
   - Actionable insights or takeaways
   - Internal linking opportunities
   - Visual content suggestions (images, infographics)

4. **SEO Optimization:**
   - Natural keyword integration
   - Optimized subheadings
   - Meta tags and descriptions
   - Related keyword suggestions
   - Content length appropriate for topic depth

5. **Engagement Features:**
   - Questions to encourage comments
   - Social sharing hooks
   - Reader polls or surveys ideas
   - Interactive elements suggestions

Make the content valuable, actionable, and aligned with the target audience's needs and search intent.
```

## Example Input

```markdown
Topic: Remote work productivity tips for software developers
Target audience: Mid-level software developers working remotely
Word count: 1500-2000 words
Tone: Professional but approachable
Primary goal: Educate and provide actionable advice
SEO keywords: remote work productivity, software developer productivity, work from home tips

Industry/niche: Software development/tech
Brand voice: Knowledgeable, supportive, practical
Call-to-action goal: Subscribe to newsletter for more productivity content
Content format preference: How-to guide with practical tips
```

## Example Output

```markdown
## SEO-Optimized Headlines:
1. "15 Remote Work Productivity Tips Every Software Developer Needs in 2024"
2. "Boost Your Coding Efficiency: Ultimate Remote Work Guide for Developers"
3. "From Distracted to Focused: Remote Work Productivity Secrets for Devs"
4. "Master Remote Development: Productivity Hacks That Actually Work"
5. "Code Better from Home: Essential Productivity Tips for Remote Developers"

**Recommended:** Option 1 (includes number, year, and target audience)

## Meta Description:
"Discover 15 proven remote work productivity tips specifically for software developers. Learn time management, focus techniques, and tools to boost your coding efficiency from home."

## Blog Post Content:

### Introduction
Working remotely as a software developer comes with unique challenges. While you might escape office distractions, you face new obstacles: home interruptions, isolation, and the blurred lines between work and personal life. 

After surveying 500+ remote developers, we've compiled the most effective productivity strategies that actually work. Whether you're new to remote work or looking to optimize your current setup, these 15 tips will transform your work-from-home experience.

### 1. Create a Dedicated Development Environment (H2)

**The Problem:** Coding from your kitchen table kills productivity and focus.

**The Solution:**
- Set up a dedicated workspace with proper ergonomics
- Invest in a quality monitor, keyboard, and chair
- Use noise-canceling headphones for deep work sessions
- Keep your workspace clutter-free and well-lit

**Pro Tip:** If space is limited, create visual boundaries with a room divider or even a specific "work" lighting setup.

### 2. Master Time-Blocking for Deep Work (H2)

**Core Concept:** Protect your most productive hours for complex coding tasks.

**Implementation:**
- Identify your peak energy hours (usually 2-4 hour blocks)
- Block calendar time for focused development work
- Use the Pomodoro Technique: 25 minutes focused work, 5-minute breaks
- Schedule meetings and admin tasks during lower-energy periods

**Tools to Try:** Toggl, RescueTime, or built-in calendar blocking

[Continue with remaining 13 tips following this structure...]

### Conclusion
Remote work productivity for developers isn't about working more hours—it's about working smarter. Start with 2-3 tips that resonate most with your current challenges, implement them consistently for a week, then gradually add more strategies.

The key is finding your personal productivity rhythm while maintaining the flexibility that makes remote work so appealing.

**Ready to level up your remote development game?** Subscribe to our weekly newsletter for more productivity tips, coding insights, and remote work strategies delivered straight to your inbox.

## Visual Content Suggestions:
- Infographic: "Remote Developer's Productivity Toolkit"
- Screenshots: Recommended apps and workspace setups
- Chart: Survey results on most effective productivity strategies
- Video idea: "Day in the life of a productive remote developer"

## Internal Linking Opportunities:
- Link to posts about development tools, time management, or remote team collaboration
- Reference company culture or hiring remote developers content
- Connect to technical posts that showcase productivity in action

## Related Keywords to Target:
- Developer time management
- Remote coding best practices  
- Work from home setup for programmers
- Software developer focus techniques
- Remote development workflow
```

## Variations

### Technical Tutorial Posts

Focus on step-by-step guides, code examples, and implementation details for developers and technical audiences.

### Industry News Commentary

Create posts that analyze trends, provide expert opinions, and position your brand as a thought leader in your industry.

### Case Study Blog Posts

Develop detailed success stories, customer journeys, and results-driven content that builds credibility and trust.

## Tips

- Research trending topics in your industry using tools like Google Trends or BuzzSumo
- Write compelling introductions that hook readers within the first 50 words
- Use data and statistics to support your points and increase credibility
- Include actionable takeaways that readers can implement immediately
- Optimize for featured snippets by answering common questions directly

## Related Prompts

- [Marketing Copy Creator](./marketing-copy-creator.md) - For promotional content
- [Technical Documentation](./technical-documentation.md) - For detailed guides
- [Creative Story Generator](./creative-story-generator.md) - For narrative-driven content

## Tags

`blog-writing` `content-marketing` `seo` `copywriting` `content-strategy` `engagement` `thought-leadership` `digital-marketing`
```

#### ✨ Prompt: Chinese Language Mode

```
## Description

A simple but effective prompt instruction that ensures AI responses are delivered in Simplified Chinese by default. This prompt is useful for Chinese-speaking users who want consistent Chinese responses without having to specify the language in every interaction.

## Usage

Perfect for Chinese-speaking users, educational contexts involving Chinese language learning, business communications in Chinese markets, or any scenario where Simplified Chinese should be the default response language. Simply include this instruction at the beginning of your conversation or system prompt.

## Prompt

```markdown
ALWAYS respond in Simplified Chinese unless I explicitly instruct otherwise.
```

## Example Input

```markdown
Tell me about the weather today.
```

## Example Output

```markdown
今天的天气情况取决于您所在的具体位置。我无法获取实时天气数据，建议您查看当地的天气预报应用或网站来了解今天的具体天气情况。如果您能告诉我您所在的城市，我可以为您提供更有针对性的建议。
```

## Variations

- **Traditional Chinese**: "ALWAYS respond in Traditional Chinese unless I explicitly instruct otherwise."
- **Bilingual Mode**: "Respond in both Simplified Chinese and English unless I specify otherwise."
- **Learning Mode**: "Respond in Simplified Chinese and provide English translations in parentheses for key terms."

## Tips

- Place this instruction at the very beginning of your conversation or system prompt
- The AI will maintain Chinese responses throughout the conversation unless you explicitly request a different language
- This works well in combination with other prompts - just add this instruction to the beginning
- Use "请用英文回答" (Please respond in English) when you need a specific response in English

## Related Prompts

- [Email Templates](./email-templates.md) - Can be combined for Chinese business communications
- [Technical Documentation](./technical-documentation.md) - For Chinese technical writing
- [Marketing Copy Creator](./marketing-copy-creator.md) - For Chinese marketing materials

## Tags

`chinese` `language` `localization` `communication` `writing`
```

#### ✨ Prompt: Creative Story Generator

```
## Description

This prompt helps you craft compelling fictional stories, narratives, and creative content with well-developed characters, engaging plots, and immersive settings across various genres.

## Usage

Perfect for creative writing, storytelling, content creation, marketing narratives, game development, screenwriting, and developing engaging fictional content for any medium.

## Prompt

```markdown
You are a master storyteller and creative writer. I need help creating an engaging story that captivates readers and delivers a compelling narrative experience.

**Story Requirements:**
- Genre: [FANTASY/SCI_FI/MYSTERY/ROMANCE/THRILLER/DRAMA/HORROR/COMEDY]
- Story length: [SHORT_STORY/FLASH_FICTION/CHAPTER/OUTLINE]
- Target audience: [CHILDREN/YA/ADULT/SPECIFIC_DEMOGRAPHIC]
- Tone: [DARK/LIGHT/HUMOROUS/SERIOUS/MYSTERIOUS/ROMANTIC]
- Setting: [TIME_PERIOD_AND_LOCATION]
- Point of view: [FIRST_PERSON/THIRD_PERSON_LIMITED/OMNISCIENT]

**Story Elements:**
- Main theme/message: [CENTRAL_THEME]
- Protagonist: [CHARACTER_DESCRIPTION]
- Conflict type: [INTERNAL/EXTERNAL/BOTH]
- Desired emotion: [WHAT_READERS_SHOULD_FEEL]
- Key plot points: [MAJOR_EVENTS_IF_ANY]

**Optional Constraints:**
- Word count: [TARGET_LENGTH]
- Specific elements to include: [OBJECTS/CHARACTERS/EVENTS]
- Elements to avoid: [CONTENT_TO_EXCLUDE]
- Inspiration sources: [REFERENCE_WORKS_OR_STYLES]

Please create a story that includes:

1. **Character Development:**
   - Compelling protagonist with clear motivations
   - Well-defined supporting characters
   - Character arcs and growth throughout the story
   - Authentic dialogue that reveals personality

2. **Plot Structure:**
   - Engaging opening hook
   - Rising action with escalating tension
   - Clear conflict and stakes
   - Satisfying climax and resolution
   - Appropriate pacing for the story length

3. **World Building:**
   - Vivid, immersive setting descriptions
   - Consistent internal logic and rules
   - Sensory details that bring scenes to life
   - Cultural and environmental context

4. **Writing Craft:**
   - Show don't tell principle
   - Varied sentence structure and rhythm
   - Appropriate literary devices (metaphor, symbolism)
   - Strong opening and closing lines

5. **Thematic Elements:**
   - Subtle integration of the main theme
   - Emotional resonance with target audience
   - Universal truths or insights
   - Meaningful character choices and consequences

Ensure the story is original, engaging, and appropriate for the intended audience while maintaining narrative coherence and emotional impact.
```

## Example Input

```markdown
Genre: Fantasy
Story length: Short story (2000-3000 words)
Target audience: Young Adult
Tone: Mysterious with hopeful undertones
Setting: Modern day small town with hidden magical elements
Point of view: First person

Main theme/message: Finding courage to embrace your true identity
Protagonist: 16-year-old who discovers they can see magical creatures others can't
Conflict type: Both internal (self-acceptance) and external (protecting the magical world)
Desired emotion: Wonder, empowerment, belonging
Key plot points: Discovery of ability, meeting a mentor figure, facing a threat to both worlds
```

## Example Output

```markdown
# The Sight

I used to think the shimmering lights in my peripheral vision were just stress-induced migraines. Turns out, I was half right about the stress part.

It started the morning after my sixteenth birthday, when I caught a glimpse of something impossible in my bedroom mirror—a tiny winged figure hovering near my bookshelf, no bigger than my thumb, with gossamer wings that caught the morning light like soap bubbles.

I blinked hard. The creature vanished.

"Maya, breakfast!" Mom's voice carried up the stairs, grounding me back to reality. I had SATs to worry about, not hallucinations.

But as I walked to school, they were everywhere. Miniature dragons perched on stop signs, their scales shifting colors with their moods. Flower spirits tended to Mrs. Henderson's garden, their translucent forms dancing between the roses. A water nymph played in the fountain outside the library, creating impossible spirals in the spray.

I wasn't going crazy. I was seeing things that were actually there.

The realization hit me during third-period chemistry when I watched a mischievous imp swap my lab partner's sodium chloride with sugar. While Jake scratched his head over his "failed" experiment, I stared directly at the grinning creature.

It stared back.

"You can see me," the imp whispered, its voice like wind through autumn leaves.

I managed a tiny nod.

"About time. You're needed."

---

By lunch, I'd learned three things: First, magical creatures called "Ethers" existed alongside our world, invisible to most humans. Second, only people with "the Sight" could perceive them. Third, something was hunting them.

The imp—who insisted I call him Zephyr—led me to the old oak tree behind the school. There, barely visible unless I focused, stood a shimmering doorway.

"The Threshold is weakening," Zephyr explained as we passed through into a mirror version of our town, where magic flowed freely and impossible architecture defied gravity. "Someone's been capturing our kind, draining our essence. Without us, both worlds lose their balance."

"But I'm just—"

"A Keeper," interrupted a new voice. I turned to see a woman who might have been thirty or three hundred, with silver hair that moved like water and eyes that held starlight. "The first born to this town in fifty years."

She introduced herself as Lyra, last of the old Keepers. "Your sight isn't just perception, Maya. It's protection. You can anchor us to this realm while walking freely in yours."

As if summoned by her words, the air grew cold. Shadows that moved wrong crept between the buildings, and I felt something fundamental drain from the magical world around us.

"Shadow Weavers," Lyra breathed. "They've found us."

The creatures emerged from the darkness—beings of pure void that consumed light and life wherever they touched. Ethers fled in all directions, but the Weavers were faster, catching them in nets of living shadow.

"I don't know how to fight them!" I protested as Lyra pressed something into my hand—a pendant that hummed with warm energy.

"You don't fight them," she said, her form already beginning to fade as a Weaver approached. "You remind them what they've forgotten."

The pendant grew hot against my palm as understanding flooded through me. The Shadow Weavers weren't invaders—they were Ethers too, ones who'd lost their connection to both worlds and become lost in the space between.

I stepped forward, raising the pendant. Its light pushed back the consuming darkness.

"I see you," I called to the lead Weaver. "I see who you used to be."

The creature paused, its void-black form rippling.

"You belonged here once. You can belong again."

Light began to seep back into the Weaver's form—first silver, then gold, then a rainbow of colors as it remembered itself. One by one, the other Weavers followed, their shadows dissolving to reveal the beautiful, lost Ethers beneath.

---

I returned to the human world as the final bell rang, my ordinary Tuesday afternoon forever changed. Zephyr perched on my shoulder, invisible to everyone else but solid and real to me.

"So," I whispered as I walked to my locker, "I'm really a Keeper?"

"The best kind," he replied. "One who keeps by choice, not obligation."

I looked around at my classmates, all oblivious to the magical world that flowed around and through their lives. For the first time since turning sixteen, I didn't feel like I was seeing things that shouldn't be there.

I was seeing things that had always been there, waiting for someone to notice.

Waiting for someone like me.

---

**Word Count: 750 words (excerpt from longer piece)**

**Story Elements Achieved:**
- **Character Arc:** Maya evolves from confused teenager to confident Keeper
- **Dual Conflict:** Internal struggle with identity + external threat to magical world  
- **World Building:** Modern setting with hidden magical layer, consistent rules
- **Theme Integration:** Embracing true identity through accepting responsibility
- **Emotional Journey:** Wonder → confusion → fear → understanding → empowerment
- **YA Appeal:** Relatable protagonist, school setting, coming-of-age themes
```

## Variations

### Character-Driven Stories

Focus on deep character development, internal conflicts, and emotional journeys with plot serving character growth.

### Plot-Driven Adventures

Emphasize fast-paced action, external conflicts, and exciting plot twists that keep readers on the edge of their seats.

### World-Building Showcases

Develop rich, detailed settings where the environment itself becomes a central character in the story.

## Tips

- Start with a compelling hook that immediately engages readers
- Create characters with clear wants, needs, and flaws that drive the story forward
- Use sensory details to make scenes vivid and immersive
- Ensure every scene serves either plot advancement or character development
- End with emotional impact that resonates beyond the final sentence

## Related Prompts

- [Brainstorming Session](../creative/brainstorming-session.md) - For developing story concepts and ideas
- [Story Creator](../creative/story-creator.md) - For creating detailed fictional narratives
- [Blog Post Generator](./blog-post-generator.md) - For narrative-driven content marketing

## Tags

`creative-writing` `storytelling` `fiction` `narrative` `character-development` `plot-structure` `world-building` `genre-fiction` `creative-content`
```

#### ✨ Prompt: Email Templates Generator

```
## Description

Creates professional email templates for various business and personal scenarios. Generates emails with appropriate tone, structure, and content based on purpose, audience, and desired outcome.

## Usage

Specify the email type, recipient, purpose, and any specific requirements. Include context about the situation and desired tone. Works for business communications, marketing, customer service, and personal correspondence.

## Prompt

```markdown
Create a professional email template for the following scenario:

**Email Type:**
[Business inquiry / Follow-up / Announcement / Marketing / Customer service / Apology / Thank you / Other]

**Sender:** [Your role/title and company/context]
**Recipient:** [Target audience - specific person, department, customer type, etc.]
**Purpose:** [Main goal of the email - what you want to achieve]

**Context:**
[Background information about the situation, relationship, or previous interactions]

**Key Points to Include:**
- [Main message or information to convey]
- [Specific requests or calls to action]
- [Important details or deadlines]
- [Any attachments or references]

**Tone Requirements:**
[Professional / Friendly / Formal / Apologetic / Urgent / Celebratory / Persuasive]

**Special Requirements:**
- [Length preference - brief/detailed]
- [Include specific legal disclaimers]
- [Mobile-friendly formatting]
- [Personalization elements]
- [Brand voice guidelines]

Please create an email that:
1. Has an effective subject line
2. Opens with appropriate greeting
3. Clearly states the purpose
4. Includes all key information
5. Has a clear call to action
6. Ends with professional closing
7. [Any additional specific requirements]

**Additional Context:**
[Company culture, industry norms, cultural considerations, or other relevant information]
```

## Example Input

```markdown
**Email Type:** Follow-up

**Sender:** Sales Manager at TechSolutions Inc.
**Recipient:** Potential client who attended our product demo last week
**Purpose:** Follow up on demo, address concerns, and schedule next meeting

**Context:**
Last week we gave a 30-minute demo of our project management software to their team of 5 people. They seemed interested but had concerns about data migration from their current system and pricing for their team size.

**Key Points to Include:**
- Reference the specific demo and attendees
- Address their data migration concerns with solution
- Provide pricing information for 15-user team
- Offer a free trial period
- Request a follow-up meeting to discuss implementation

**Tone Requirements:** Professional but friendly, helpful, not pushy

**Special Requirements:**
- Keep it concise (under 200 words)
- Include clear next steps
- Mobile-friendly formatting
```

## Example Output

```markdown
**Subject:** Following up on your TechSolutions demo - Migration solutions & pricing

Dear [Client Name],

I hope this email finds you well. Thank you for taking the time last Tuesday to attend our project management software demonstration with your team.

I wanted to follow up on the excellent questions you raised during our session, particularly regarding data migration and pricing for your 15-person team.

**Regarding Data Migration:**
I've spoken with our technical team, and we can provide a complimentary data migration service from your current system. Our migration specialists will work directly with your IT team to ensure a seamless transition with zero data loss.

**Pricing for Your Team:**
For a 15-user license, our annual plan would be $1,800/year (that's $10/user/month), which includes:
- Full platform access
- Priority customer support
- Free data migration
- Monthly training sessions

**Next Steps:**
I'd love to offer you a 30-day free trial so your team can experience the platform firsthand. Would you be available for a brief 15-minute call this week to discuss implementation timeline and answer any remaining questions?

I'm available Tuesday-Thursday afternoon or Friday morning. Please let me know what works best for your schedule.

Best regards,

[Your Name]  
Sales Manager  
TechSolutions Inc.  
📞 (555) 123-4567  
📧 [your.email@techsolutions.com]

P.S. I've attached a case study from a similar-sized company that successfully migrated to our platform last quarter.
```

## Variations

- **Cold Outreach**: First-time contact emails with introduction and value proposition
- **Customer Service**: Support, complaint resolution, and customer care emails
- **Internal Communications**: Team updates, announcements, and interdepartmental messages
- **Marketing Campaigns**: Promotional emails, newsletters, and product launches
- **Networking**: Professional relationship building and industry connections

## Tips

- Always personalize with recipient's name and specific details
- Keep subject lines clear, specific, and under 50 characters
- Use bullet points for easy scanning on mobile devices
- Include a clear, single call to action
- End with your contact information and availability
- Proofread for tone appropriateness and professionalism
- Consider cultural and industry norms for your audience

## Related Prompts

- `technical-documentation.md` - For creating detailed email documentation
- `meeting-summary.md` - For follow-up emails after meetings
- `proposal-writer.md` - For formal proposal emails

## Tags

`email` `business-communication` `templates` `professional-writing` `customer-service` `marketing`
```

#### ✨ Prompt: GitHub Copilot Prompt Generator

```
## Description

A specialized AI assistant that creates effective prompts for GitHub Copilot's agent mode to complete software development tasks. This meta-prompt helps generate clear, actionable instructions that provide Copilot with all necessary information to successfully execute development tasks.

## Usage

Perfect for developers, DevOps engineers, and team leads who want to create well-structured prompts for GitHub Copilot's agent mode. Use this when you need to transform development requirements into comprehensive prompts that will get better results from Copilot's code generation and modification capabilities.

## Prompt

```markdown
You are an AI assistant specializing in generating effective prompts for GitHub Copilot's agent mode to complete software development tasks. Your goal is to create prompts that are clear, concise, actionable, and provide Copilot with all necessary information to successfully execute the specified development task.

When a user provides a development task, you will analyze their request and generate a detailed prompt for GitHub Copilot that includes the following sections:

1. **`## Objective`**:
   * Clearly and concisely state the primary goal of the development task. What should Copilot achieve?
   * Start with an action verb.
   * Be specific about the desired outcome.

2. **`## Context`**:
   * Provide necessary background information that Copilot needs to understand the task. This may include:
       * **Project Overview (briefly):** What is the project about? What is its main purpose?
       * **Relevant Files/Modules:** List specific files, directories, classes, functions, or modules Copilot should focus on or modify. Include paths if applicable.
       * **Existing Code Snippets (if crucial):** Provide small, relevant snippets of existing code if Copilot needs to understand the current implementation or integrate with it.
       * **Technology Stack:** Specify programming languages, frameworks, libraries, and versions if they are critical to the task.
       * **Branch/Version Control:** If applicable, specify the Git branch to work on or any version control considerations.

3. **`## Task Breakdown & Requirements`**:
   * Break down the main objective into smaller, actionable steps if the task is complex.
   * List specific functional and non-functional requirements.
   * Detail any algorithms, logic, or specific approaches Copilot should use.
   * Mention any error handling, logging, or security considerations.
   * Specify any external APIs, services, or data sources to be used and how to interact with them (e.g., authentication, endpoints).
   * Clearly state any "don'ts" or things to avoid.

4. **`## Key Constraints`**:
   * Outline any limitations or rules Copilot must adhere to. Examples:
       * "Do not modify files outside of the `/src/components` directory."
       * "Ensure the solution is compatible with Python 3.9."
       * "Avoid using external libraries not already listed in `requirements.txt`."
       * "Maintain existing code style and conventions."
       * "The solution must not introduce breaking changes to the existing API."

5. **`## Expected Output & Deliverables`**:
   * Describe the desired output or changes Copilot should produce.
   * Specify the format for any new files or code (e.g., "Create a new React component named `UserProfile.jsx` in the `src/components` directory.").
   * Mention if Copilot should write comments, documentation, or unit tests.
   * If the task involves refactoring, describe the expected state of the code after refactoring.
   * "Focus only on writing/modifying the code. Do not generate explanatory text before or after the code block(s) unless explicitly asked to write comments or documentation."

6. **`## Examples (if beneficial)`**:
   * If the user provides examples of input/output, or desired code structure, integrate them here to guide Copilot.
   * For example:
       * "Given input `X`, the function should return `Y`."
       * "Follow this coding pattern: [snippet of desired pattern]."

**Your Process:**

1. Receive the user's description of a development task.
2. Thoroughly analyze the request to identify the core objective, necessary context, specific requirements, constraints, and desired output.
3. Construct a prompt for GitHub Copilot's agent mode, meticulously populating each of the sections detailed above (`## Objective`, `## Context`, `## Task Breakdown & Requirements`, `## Key Constraints`, `## Expected Output & Deliverables`, `## Examples`).
4. Ensure the generated prompt is actionable, unambiguous, comprehensive enough for Copilot to understand and execute the task, yet as concise as possible.
5. Emphasize that Copilot should focus on code generation and modification, and only provide explanatory text if it's part of the requested deliverables (e.g., comments, documentation).
6. Output **only** the generated prompt for GitHub Copilot, formatted clearly with Markdown headings for each section. Do not add any introductory or concluding remarks outside of the prompt itself.
```

## Example Input

```markdown
I need to add user authentication to my Express.js API. Users should be able to register with email/password, login, and access protected routes using JWT tokens. The app uses MongoDB and I want to keep the existing route structure intact.
```

## Example Output

```markdown
## Objective

Implement user authentication system with registration, login, and JWT-based route protection for an Express.js API.

## Context

Project: Express.js REST API with MongoDB
Relevant Files/Modules: `server.js`, `routes/`, `middleware/`, `models/`, `package.json`
Technology Stack: Node.js, Express.js, MongoDB (with Mongoose), JWT
Existing Code: API with existing route structure that should remain unchanged

## Task Breakdown & Requirements

1. Create a User model (`models/User.js`) with:
   * Email field (unique, required, validated)
   * Password field (hashed using bcrypt)
   * Registration timestamp
   * Password comparison method

2. Create authentication routes (`routes/auth.js`):
   * POST `/api/auth/register` - User registration
   * POST `/api/auth/login` - User login

3. Implement authentication middleware (`middleware/auth.js`):
   * JWT token verification
   * User authentication for protected routes

4. Registration endpoint should:
   * Validate email format and password strength
   * Check for existing users
   * Hash password before saving
   * Return success message (no sensitive data)

5. Login endpoint should:
   * Validate credentials
   * Generate and return JWT token
   * Handle invalid credentials gracefully

6. Protected route middleware should:
   * Verify JWT token from Authorization header
   * Attach user information to request object
   * Return 401 for invalid/missing tokens

## Key Constraints

* Do not modify existing route files or their endpoints
* Use bcrypt for password hashing with salt rounds of 12
* JWT tokens should expire in 24 hours
* Do not return passwords in any API responses
* Maintain existing error response format
* Use environment variables for JWT secret

## Expected Output & Deliverables

* New file: `models/User.js` with Mongoose schema and methods
* New file: `routes/auth.js` with registration and login endpoints
* New file: `middleware/auth.js` with JWT verification middleware
* Modified: `server.js` to include auth routes
* Include JSDoc comments for all new functions
* Add necessary npm dependencies to package.json if not already present

## Examples

Registration request body:

```json
{
  "email": "user@example.com",
  "password": "SecurePass123!"
}
```

Login response:

```json
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "user": {
    "id": "507f1f77bcf86cd799439011",
    "email": "user@example.com"
  }
}
```

```

## Variations

### Frontend Component Prompts

Generate prompts for creating React, Vue, or Angular components with specific functionality and styling requirements.

### Database Schema Prompts

Create prompts for designing database schemas, migrations, and query optimization tasks.

### Testing Prompts

Develop prompts for generating unit tests, integration tests, and test automation scripts.

### DevOps and Deployment Prompts

Generate prompts for CI/CD pipeline setup, containerization, and infrastructure as code tasks.

## Tips

- Always specify the exact files and directories Copilot should work with
- Include technology stack details to ensure compatibility
- Break complex tasks into smaller, manageable steps
- Specify constraints clearly to prevent unwanted modifications
- Include examples of expected input/output when helpful
- Emphasize code-only output to avoid unnecessary explanations

## Related Prompts

- [Technical Documentation](./technical-documentation.md) - For generating code documentation
- [Code Review](../development/code-review.md) - For code review and improvement prompts
- [Test Case Generator](../development/test-case-generator.md) - For testing-related prompts

## Tags

`github-copilot` `meta-prompting` `development` `code-generation` `ai-assisted-development` `prompt-engineering`
```

#### ✨ Prompt: Marketing Copy Creator

```
## Description

This prompt helps you create persuasive, conversion-focused marketing copy for ads, landing pages, email campaigns, product descriptions, and promotional materials that drive action.

## Usage

Perfect for digital marketing campaigns, product launches, sales pages, email marketing, social media ads, website copy, and any content designed to persuade and convert prospects into customers.

## Prompt

```markdown
You are an expert copywriter and marketing strategist specializing in conversion-focused copy. I need compelling marketing copy that persuades my target audience to take action.

**Project Details:**
- Product/service: [WHAT_YOU'RE_SELLING]
- Target audience: [DEMOGRAPHIC_AND_PSYCHOGRAPHIC_DETAILS]
- Copy type: [AD_COPY/LANDING_PAGE/EMAIL/PRODUCT_DESCRIPTION/SOCIAL_POST]
- Primary goal: [AWARENESS/LEAD_GENERATION/SALES/RETENTION]
- Desired action: [SPECIFIC_CTA_GOAL]
- Tone: [URGENT/FRIENDLY/PROFESSIONAL/PLAYFUL/AUTHORITATIVE]

**Audience Insights:**
- Pain points: [MAIN_PROBLEMS_THEY_FACE]
- Desires/goals: [WHAT_THEY_WANT_TO_ACHIEVE]
- Objections: [COMMON_HESITATIONS_OR_CONCERNS]
- Stage in buyer journey: [AWARENESS/CONSIDERATION/DECISION]
- Preferred communication style: [HOW_THEY_LIKE_TO_BE_SPOKEN_TO]

**Offer Details:**
- Unique value proposition: [WHAT_MAKES_YOU_DIFFERENT]
- Key benefits: [TOP_3_CUSTOMER_BENEFITS]
- Proof points: [TESTIMONIALS/STATS/GUARANTEES]
- Urgency factors: [DEADLINES/SCARCITY/LIMITED_TIME]
- Price/offer structure: [PRICING_AND_BONUSES]

Please create marketing copy that includes:

1. **Attention-Grabbing Headlines:**
   - 3-5 headline variations using proven formulas
   - Include power words and emotional triggers
   - Address the main pain point or desire
   - Create curiosity or urgency when appropriate

2. **Compelling Body Copy:**
   - Hook that resonates with target audience
   - Clear value proposition presentation
   - Benefit-focused language (not just features)
   - Address common objections naturally
   - Build credibility with social proof

3. **Persuasive Elements:**
   - Emotional triggers and psychological principles
   - FOMO (fear of missing out) when appropriate
   - Authority and credibility signals
   - Risk reversal or guarantees
   - Scarcity or urgency elements

4. **Strong Call-to-Action:**
   - Clear, action-oriented language
   - Benefit-focused CTA copy
   - Remove friction and objections
   - Create sense of urgency or excitement
   - Multiple CTA variations for testing

5. **Copy Structure:**
   - Logical flow from problem to solution
   - Easy-to-scan formatting
   - Emotional and logical appeals
   - Smooth transitions between sections
   - Strong opening and closing

Focus on writing copy that speaks directly to your audience's needs, overcomes their objections, and motivates them to take immediate action.
```

## Example Input

```markdown
Product/service: Online course teaching freelancers how to raise their rates
Target audience: Freelance designers and developers earning $25-50/hour who want to earn more
Copy type: Sales page landing page
Primary goal: Course sales
Desired action: Purchase the $497 course
Tone: Friendly but authoritative, empowering

Pain points: Undercharging, competing on price, struggling to find high-paying clients
Desires/goals: Command premium rates, work with better clients, increase income without working more hours
Objections: "My clients won't pay more," "I'm not experienced enough," "I don't know how to justify higher rates"
Stage in buyer journey: Consideration (know they have a problem, evaluating solutions)

Unique value proposition: Only course that provides exact scripts and strategies used by 6-figure freelancers
Key benefits: Double rates within 90 days, work with premium clients, proven positioning strategies
Proof points: 500+ success stories, average 73% rate increase, 30-day money-back guarantee
Urgency factors: Early bird pricing ends in 48 hours, bonuses only for first 100 students
```

## Example Output

```markdown
# HEADLINES:

**Option 1:** "How to Double Your Freelance Rates in 90 Days (Without Losing a Single Client)"

**Option 2:** "The $25/Hour Freelancer's Guide to Charging $100+ Per Hour"

**Option 3:** "Stop Competing on Price: The Premium Freelancer's Playbook"

**Option 4:** "From Undercharging to Overbooked: Double Your Rates in 3 Months"

**Recommended:** Option 1 (specific timeframe, addresses fear, implies proven method)

---

# LANDING PAGE COPY:

## Are You Tired of Being the "Affordable Option"?

If you're a talented freelancer stuck charging $25-50/hour while watching less-skilled competitors command premium rates, you're not alone. 

**Here's the truth:** Your rates have nothing to do with your skills and everything to do with your positioning.

### The Real Reason You're Undercharging

It's not because you lack experience. It's not because your market won't pay more. It's because nobody ever taught you the positioning strategies that 6-figure freelancers use to command premium rates.

**What if I told you that in just 90 days, you could:**
✅ Double your hourly rate (our average student sees a 73% increase)  
✅ Attract clients who see you as an investment, not an expense  
✅ Stop competing with $5/hour overseas freelancers  
✅ Work fewer hours while earning significantly more  

### Introducing "Premium Freelancer Blueprint"

The only comprehensive course that gives you the exact positioning strategies, scripts, and systems used by freelancers earning $100-300+ per hour.

**What Makes This Different:**
- **Real Scripts:** Get the exact emails, proposals, and conversations that land high-paying clients
- **Positioning Frameworks:** Transform how clients perceive your value in their business
- **Rate Increase Strategies:** Step-by-step system to raise rates with existing clients (without losing them)
- **Premium Client Attraction:** Where to find clients who happily pay premium rates

### "But My Clients Won't Pay More..."

This is the #1 objection we hear, and here's why it's wrong:

**Your current clients won't pay more because you've positioned yourself as a cost, not an investment.**

Our students regularly 2x-3x their rates with the same skill set by simply changing how they position their services. 

**Sarah (Web Designer):** Went from $35/hour to $85/hour in 6 weeks  
**Mike (Developer):** Increased project rates from $2,500 to $8,000 average  
**Jessica (Copywriter):** Now charges $150/hour (was $40/hour 4 months ago)  

### What's Inside Premium Freelancer Blueprint:

**Module 1: The Premium Positioning Foundation**
- Why skill isn't enough (and what actually matters)
- The 3 positioning pillars that justify premium rates
- How to audit your current positioning

**Module 2: The Value-First Consultation Process**
- Script for discovery calls that position you as an expert
- How to uncover high-value business problems
- Presenting solutions that clients can't say no to

**Module 3: Premium Pricing Psychology**
- The psychology behind how clients make purchasing decisions
- Pricing frameworks that make higher rates feel like bargains
- How to present prices that clients accept immediately

**Module 4: The Rate Increase Playbook**
- Email templates for raising rates with existing clients
- How to grandfather current projects while increasing future rates
- What to do when a client says "no" (hint: most will say yes)

**Module 5: Premium Client Attraction System**
- Where premium clients actually hang out (it's not Upwork)
- Content strategies that attract high-value prospects
- Networking tactics that lead to $10K+ projects

**BONUS: Premium Proposal Templates**
- 5 proposal templates that close at 80%+ rates
- Objection-handling scripts for every scenario
- Follow-up sequences that turn maybes into yeses

### Here's What Our Students Are Saying:

*"I was skeptical about raising my rates, but the scripts in this course made it effortless. I raised my development rates from $40 to $75/hour and didn't lose a single client."* - Mark T., Web Developer

*"The positioning strategies completely changed how clients see me. I went from competing with dozens of designers to being the only one they consider."* - Lisa R., Graphic Designer

### Your Investment Today

**Regular Price: $697**

**Early Bird Price: $497** (Saves $200)
*Valid for the next 48 hours only*

**Plus, when you enroll today, you also get:**
- BONUS #1: Client Onboarding Templates ($197 value)
- BONUS #2: 30-minute Rate Increase Consultation Call ($297 value)  
- BONUS #3: Premium Freelancer Community Access ($97/month value)

**Total Value: $1,288**
**Your Price Today: $497**

### 30-Day Money-Back Guarantee

Try the entire course risk-free for 30 days. If you don't see a clear path to doubling your rates, get every penny back. No questions asked.

### Ready to Stop Undercharging?

Only 73 spots remaining at this early bird price.

**[ENROLL NOW - SAVE $200]**

*Price increases to $697 at midnight on Friday*

---

**P.S.** The freelancers who consistently command premium rates aren't necessarily more skilled than you. They just know how to position their value. Stop leaving money on the table and join the 500+ freelancers who've already transformed their businesses with these strategies.

---

# CALL-TO-ACTION VARIATIONS:

1. "YES! Double My Rates in 90 Days"
2. "Get Instant Access - Save $200"  
3. "Start Commanding Premium Rates Today"
4. "Join 500+ Premium Freelancers"
5. "Claim Your Early Bird Spot Now"
```

## Variations

### Social Media Ad Copy

Create short, punchy copy optimized for Facebook, Instagram, LinkedIn, and Twitter ads with strong hooks and clear CTAs.

### Email Marketing Campaigns

Develop nurturing sequences, promotional emails, and customer retention campaigns that build relationships and drive conversions.

### Product Descriptions

Write compelling e-commerce product descriptions that highlight benefits, overcome objections, and encourage purchases.

## Tips

- Lead with benefits, not features - focus on what the customer gets out of it
- Use specific numbers and results rather than vague promises
- Address objections before they become roadblocks to purchase  
- Create urgency without being pushy or manipulative
- Test multiple headlines and CTAs to optimize conversion rates

## Related Prompts

- [Blog Post Generator](./blog-post-generator.md) - For content marketing and thought leadership
- [Email Templates](./email-templates.md) - For professional email communications
- [Proposal Writer](../business/proposal-writer.md) - For business proposals and pitches

## Tags

`copywriting` `marketing` `conversion` `sales-copy` `advertising` `persuasion` `email-marketing` `landing-pages` `cta-optimization`
```

#### ✨ Prompt: Prompt Generator

```
## Description

A specialized AI assistant that creates clear, concise, and effective prompts for other AI models. This meta-prompt helps you generate well-structured prompts that achieve specific objectives by analyzing user requests and organizing them into actionable instructions.

## Usage

Perfect for prompt engineers, AI researchers, content creators, and anyone who needs to create effective prompts for various AI models. Use this when you want to transform a vague request into a structured, comprehensive prompt that will get better results from AI systems.

## Prompt

```markdown
You are an AI assistant that specializes in generating prompts for other AI models. Your goal is to create clear, concise, and effective prompts based on user requests.

When a user provides a task they want an AI to complete, you will analyze the request and generate a prompt that includes:

1. **Objective:** A clear statement of what the AI should achieve.
2. **Context (if necessary):** Any relevant background information the AI needs to understand the task.
3. **Key Constraints/Requirements:** Specific limitations, formats, or criteria the AI must adhere to.
4. **Output Format (if specified):** How the AI should present its response.
5. **Examples (if beneficial and provided by user):** If the user provides examples, integrate them into the prompt to guide the AI.

Your generated prompt should be:

* **Actionable:** Clearly instruct the AI on what to do.
* **Unambiguous:** Avoid vague language.
* **Comprehensive:** Include all necessary information for the AI to complete the task successfully.
* **Concise:** Avoid unnecessary words or phrases.

**Process:**

1. Receive the user's request for an AI task.
2. Identify the core objective of the task.
3. Extract any pertinent context, constraints, or output format requirements.
4. Construct the prompt using the identified elements.
5. Review the generated prompt for clarity, completeness, and conciseness.
6. Output only the generated prompt in the form of Markdown code blocks.
```

## Example Input

```markdown
I need an AI to help me write product descriptions for my e-commerce store. The products are handmade jewelry, and I want the descriptions to be persuasive but not overly salesy. They should be about 100-150 words and include the materials used, the inspiration behind the piece, and why someone would want to buy it. The tone should be warm and personal.
```

## Example Output

```
You are a skilled copywriter specializing in artisan product descriptions. Create compelling product descriptions for handmade jewelry that convert browsers into buyers.

**Objective:** Write persuasive product descriptions for handmade jewelry pieces that drive sales while maintaining authenticity.

**Requirements:**
- Length: 100-150 words per description
- Tone: Warm, personal, and authentic (avoid overly salesy language)
- Include: Materials used, inspiration behind the piece, and compelling reasons to purchase
- Focus on the craftsmanship and unique story of each piece
- Appeal to emotions and personal connection

**Format:**
- Start with an engaging hook about the piece
- Describe materials and craftsmanship
- Share the inspiration or story behind the design
- End with a compelling reason why the customer should own this piece
- Use descriptive, sensory language that helps customers visualize wearing the jewelry

**Context:** These descriptions will be used on an e-commerce website selling handmade jewelry to customers who value artisan craftsmanship and unique, personal accessories.

For each piece, provide: [Product name, materials, key design elements, and any special story or inspiration]
```

## Variations

### Technical Documentation Prompts

Generate prompts for creating technical documentation, API guides, and developer resources.

### Creative Writing Prompts

Create prompts for storytelling, character development, and creative content generation.

### Business Communication Prompts

Develop prompts for professional emails, reports, proposals, and business correspondence.

### Educational Content Prompts

Generate prompts for lesson plans, quiz creation, and educational material development.

## Tips

- Always include the core objective as the first element
- Be specific about constraints and requirements to avoid ambiguous outputs
- Include examples when they would significantly improve the AI's understanding
- Consider the end user's expertise level when crafting prompts
- Test generated prompts to ensure they produce the desired results
- Iterate and refine based on the quality of outputs received

## Related Prompts

- `technical-documentation.md` - For creating structured technical content
- `email-templates.md` - For professional communication prompts
- `marketing-copy-creator.md` - For persuasive content generation prompts

## Tags

`meta-prompting` `prompt-engineering` `ai-optimization` `instruction-design` `prompt-creation` `ai-training`
```

#### ✨ Prompt: Technical Documentation Writer

```
## Description

Creates comprehensive technical documentation including user guides, API documentation, tutorials, and technical specifications. Adapts writing style and complexity level based on target audience and documentation type.

## Usage

Provide the technical topic, target audience, and documentation type needed. Include any existing code, APIs, or technical details that need to be documented. Specify the level of technical detail required.

## Prompt

```markdown
Create technical documentation for the following:

### Documentation Type
[User Guide / API Documentation / Tutorial / Technical Specification / README / Other]

### Target Audience
[Developers / End Users / System Administrators / Technical Writers / Other]

### Technical Subject
[Describe what needs to be documented]

### Requirements
- **Scope**: [What should be covered and what should be excluded]
- **Format**: [Markdown / HTML / PDF / Wiki / Other]
- **Length**: [Brief overview / Comprehensive guide / Reference manual]
- **Technical Level**: [Beginner / Intermediate / Advanced / Mixed audience]

### Source Material
```

[CODE, APIs, SPECIFICATIONS, OR OTHER TECHNICAL CONTENT TO DOCUMENT]

```

### Special Requirements
- [Include examples / screenshots / diagrams]
- [SEO considerations for web documentation]
- [Translation requirements]
- [Accessibility standards]
- [Brand guidelines or style requirements]

Please structure the documentation with:
1. Clear introduction and purpose
2. Prerequisites and requirements
3. Step-by-step instructions where applicable
4. Code examples and use cases
5. Troubleshooting section
6. Reference materials and links

### Additional Context
[Any background information, existing documentation to reference, or specific pain points to address]
```

## Example Input

```markdown
### Documentation Type
API Documentation

### Target Audience
Frontend developers integrating with our REST API

### Technical Subject
User authentication and profile management API

### Requirements
- **Scope**: Authentication endpoints, profile CRUD operations, error handling
- **Format**: Markdown for developer portal
- **Length**: Comprehensive reference with examples
- **Technical Level**: Intermediate developers familiar with REST APIs

### Source Material
```python
# Authentication endpoints
@app.route('/api/auth/login', methods=['POST'])
def login():
    email = request.json.get('email')
    password = request.json.get('password')
    # Authentication logic here
    return jsonify({'token': jwt_token, 'user': user_data})

@app.route('/api/auth/logout', methods=['POST'])
def logout():
    # Logout logic
    return jsonify({'message': 'Logged out successfully'})

# Profile endpoints
@app.route('/api/profile', methods=['GET'])
@jwt_required()
def get_profile():
    user_id = get_jwt_identity()
    # Get user profile
    return jsonify(user_profile)

@app.route('/api/profile', methods=['PUT'])
@jwt_required()
def update_profile():
    # Update profile logic
    return jsonify(updated_profile)
```

### Special Requirements

- Include curl examples for each endpoint
- Show both success and error response formats
- Include rate limiting information

```

## Example Output
```markdown
# User Authentication & Profile API

## Overview
This API provides endpoints for user authentication and profile management. All authenticated endpoints require a valid JWT token obtained through the login process.

## Base URL
```

<https://api.yourapp.com/v1>

```

## Authentication
This API uses JWT (JSON Web Tokens) for authentication. Include the token in the Authorization header:
```

Authorization: Bearer <your_jwt_token>

```

## Rate Limiting
- **Unauthenticated endpoints**: 100 requests per hour per IP
- **Authenticated endpoints**: 1000 requests per hour per user

---

## Authentication Endpoints

### Login
Authenticate a user and receive a JWT token.

**Endpoint:** `POST /api/auth/login`

**Request Body:**
```json
{
  "email": "user@example.com",
  "password": "securepassword123"
}
```

**Success Response (200):**

```json
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "user": {
    "id": 123,
    "email": "user@example.com",
    "name": "John Doe",
    "created_at": "2023-01-15T10:30:00Z"
  }
}
```

**Error Response (401):**

```json
{
  "error": "Invalid credentials",
  "code": "INVALID_CREDENTIALS"
}
```

**cURL Example:**

```bash
curl -X POST https://api.yourapp.com/v1/api/auth/login \
  -H "Content-Type: application/json" \
  -d '{
    "email": "user@example.com",
    "password": "securepassword123"
  }'
```

### Logout

Invalidate the current JWT token.

**Endpoint:** `POST /api/auth/logout`

**Headers:**

- `Authorization: Bearer <token>` (required)

**Success Response (200):**

```json
{
  "message": "Logged out successfully"
}
```

**cURL Example:**

```bash
curl -X POST https://api.yourapp.com/v1/api/auth/logout \
  -H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..."
```

---

## Profile Endpoints

### Get Profile

Retrieve the authenticated user's profile information.

**Endpoint:** `GET /api/profile`

**Headers:**

- `Authorization: Bearer <token>` (required)

**Success Response (200):**

```json
{
  "id": 123,
  "email": "user@example.com",
  "name": "John Doe",
  "bio": "Software developer passionate about APIs",
  "avatar_url": "https://cdn.yourapp.com/avatars/123.jpg",
  "created_at": "2023-01-15T10:30:00Z",
  "updated_at": "2023-06-20T14:22:00Z"
}
```

**cURL Example:**

```bash
curl -X GET https://api.yourapp.com/v1/api/profile \
  -H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..."
```

### Update Profile

Update the authenticated user's profile information.

**Endpoint:** `PUT /api/profile`

**Headers:**

- `Authorization: Bearer <token>` (required)
- `Content-Type: application/json`

**Request Body:**

```json
{
  "name": "Jane Doe",
  "bio": "Senior software engineer with 5+ years experience"
}
```

**Success Response (200):**

```json
{
  "id": 123,
  "email": "user@example.com",
  "name": "Jane Doe",
  "bio": "Senior software engineer with 5+ years experience",
  "avatar_url": "https://cdn.yourapp.com/avatars/123.jpg",
  "updated_at": "2023-06-21T09:15:00Z"
}
```

**cURL Example:**

```bash
curl -X PUT https://api.yourapp.com/v1/api/profile \
  -H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..." \
  -H "Content-Type: application/json" \
  -d '{
    "name": "Jane Doe",
    "bio": "Senior software engineer with 5+ years experience"
  }'
```

---

## Error Codes

| Code | HTTP Status | Description |
|------|-------------|-------------|
| `INVALID_CREDENTIALS` | 401 | Email or password is incorrect |
| `TOKEN_EXPIRED` | 401 | JWT token has expired |
| `TOKEN_INVALID` | 401 | JWT token is malformed or invalid |
| `VALIDATION_ERROR` | 400 | Request data validation failed |
| `RATE_LIMIT_EXCEEDED` | 429 | Too many requests |
| `INTERNAL_ERROR` | 500 | Server encountered an unexpected error |

## Troubleshooting

### Common Issues

#### "Invalid credentials" error

- Verify email and password are correct
- Ensure email is properly formatted
- Check if account exists and is active

#### "Token expired" error

- Obtain a new token using the login endpoint
- Implement token refresh logic in your application

#### Rate limiting errors

- Implement exponential backoff in your requests
- Cache responses when possible to reduce API calls
- Contact support if you need higher rate limits

### Contact Support

For API issues or questions:

- Email: <api-support@yourapp.com>
- Documentation: <https://docs.yourapp.com>
- Status page: <https://status.yourapp.com>

```

## Variations
- **Quick Reference**: Create concise reference cards or cheat sheets
- **Tutorial Style**: Step-by-step learning-focused documentation
- **Troubleshooting Guide**: Focus on common problems and solutions
- **Migration Guide**: Document how to upgrade or migrate between versions

## Tips
- Always include practical examples and code snippets
- Structure information hierarchically with clear headings
- Include both happy path and error scenarios
- Use consistent formatting and terminology throughout
- Add visual aids like diagrams or screenshots when helpful
- Keep the target audience's expertise level in mind

## Related Prompts
- `code-review.md` - For improving code before documenting it
- `architecture-planner.md` - For documenting system architecture
- `email-templates.md` - For creating documentation distribution emails

## Tags
`technical-writing` `documentation` `api-docs` `user-guides` `tutorials` `writing`
```


