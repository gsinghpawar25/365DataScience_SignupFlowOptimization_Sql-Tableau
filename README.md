# 365 Data Science Website Sign-Up Flow Optimization Analytical Report

# Table of Contents

1. [Introduction](#introduction)
2. [Importance of Dashboards](#importance-of-dashboards)
3. [Objective](#objective)
4. [Report Structure](#report-structure)
5. [365 Data Science Sign-Up Flow Optimization Analysis Report](#365-data-science-sign-up-flow-optimization-analysis-report)
    - [Introduction](#introduction-1)
    - [Current State of Affairs](#current-state-of-affairs)
        - [Sign-Up Methods](#sign-up-methods)
        - [Dashboard Analysis](#dashboard-analysis)
        - [Visitor Behaviour Analysis](#visitor-behaviour-analysis)
        - [Sign-Up Method Analysis](#sign-up-method-analysis)
        - [Conclusion](#conclusion)
6. [Sign-Up Types Analysis Report](#sign-up-types-analysis-report)
    - [Sign-Up Preferences](#sign-up-preferences)
    - [Factors Influencing Sign-Up Choices](#factors-influencing-sign-up-choices)
    - [Sign-Up Interface Analysis](#sign-up-interface-analysis)
    - [Mobile Device Considerations](#mobile-device-considerations)
    - [Conclusion](#conclusion-1)
7. [Sign-Up Success and Failure Rates Analysis Report](#sign-up-success-and-failure-rates-analysis-report)
    - [Failure Rates Analysis](#failure-rates-analysis)
    - [Device-Specific Challenges](#device-specific-challenges)
    - [External Factors and Solutions](#external-factors-and-solutions)
    - [Success Rates Analysis](#success-rates-analysis)
    - [Conclusion and Recommendations](#conclusion-and-recommendations)
8. [Login Patterns and Challenges Analysis Report](#login-patterns-and-challenges-analysis-report)
    - [Introduction](#introduction-2)
    - [Login Preferences](#login-preferences)
    - [Device Usage Insights](#device-usage-insights)
    - [Login Challenges](#login-challenges)
    - [Google Login Challenges](#google-login-challenges)
    - [Strategic Considerations](#strategic-considerations)
9. [Actionable Insights Report](#actionable-insights-report)
    - [Introduction](#introduction-3)
    - [Key Actionable Insights](#key-actionable-insights)
    - [Expected Outcomes](#expected-outcomes)
    - [Next Steps](#next-steps)

## Introduction
A “Tableau story” based dashboard using actual data from our website to analyse visitor behaviour and identify trends in the sign-up flow.

## Importance of Dashboards
- **Value for Businesses:** Dashboards provide at-a-glance insights into key performance metrics, enabling real-time monitoring and evaluation.
- **Graphical Representation:** They offer a clear, concise, and visually engaging view of complex datasets, helping managers and executives understand information quickly and accurately.
- **Predictive Capabilities:** By integrating data analysis and dashboards into regular workflows, businesses can refine predictive capabilities and seize future opportunities.

## Objective
- Used the story-based dashboard to analyse the behaviour of 365 Data Science website visitors, identify trends, and define issues in the sign-up flow. Streamline findings and recommend actions to improve the website’s sign-up experience.

## Report Structure
1. **Current State of Affairs:**
    - Define the current sign-up experience using visualizations from the story.
    - Highlight key observations, visitor behaviour, preferences, and challenges.
    - Use numbers from graphs to support research.
2. **Actionable Insights:**
    - Generate practical ways to improve the web page.
    - Provide strategic actions based on analysis findings.

---

# 365 Data Science Sign-Up Flow Optimization Analysis Report

## Introduction
- This report provides an in-depth analysis of the 365 Data Science platform's sign-up process.
- The focus is on understanding the current state of the sign-up flow and identifying areas for optimization.

## Current State of Affairs

### Sign-Up Methods:
The platform offers a free registration option with two primary methods:
- **Email Sign-Up:** Requires users to input their email address, password, and names.
- **Social Media Sign-Up:** Users can register using existing accounts from Facebook, LinkedIn, or Google.

Both methods are accessible on desktop and mobile devices, ensuring flexibility for users.

### Dashboard Analysis

#### Dashboard 1: Monthly Visitors and Conversion Rates:
A dual chart on the dashboard displays the number of monthly visitors alongside the corresponding sign-up conversion rates.

- **Insights:**
    - November records the highest visitor count and conversion rate, exceeding 26%.
    - This spike is attributed to a 21-day free campaign offering unlimited access to all content.
    - The campaign's success is acknowledged, but November's data is considered an outlier for average behaviour analysis., since usual trend follows 2%-5% conversion rate.
- **General Trends:**
    - In other months, conversion rates approximately range between 2% and 5%, aligning with industry benchmarks for online educational platforms.
    - December shows a slight dip in conversion rates, likely due to the global holiday season.

**Factors Influencing Conversion Rates:**
Variations in conversion rates may result from:
- Marketing campaigns and initiatives.
- Seasonality and related website activities.
- Integration of new features and addition of new courses on the platform.

The goal is to understand the current state of the sign-up flow and identifying areas for optimization, in order to identify factors that consistently drive new registrations and improve conversion rates.

### Visitor Behaviour Analysis

- **Device Usage:**
    - A graph comparing mobile versus desktop sign-ups reveals:
        - Mobile sign-ups are approximately 1% higher than desktop, but the difference is not significant enough to conclude greater convenience.
        - Failed sign-up attempts on mobile devices are nearly three times higher than on desktops.
    - This discrepancy highlights potential issues with mobile sign-up attempts that require further investigation.

- **Operating Systems:**
    - Analysis of operating systems used for sign-ups shows:
        - Android is the most popular OS, followed closely by Windows.
        - Apple devices, including iOS and Mac OS X, occupy the third and fourth positions.
- **Failed Attempts Analysis:**
    - Android devices account for a high number of failed attempts, MOST FAILED ATTEMPTS, nearly triple the failures on Windows and four times higher than iOS.
    - Despite the high failure rate, Android also shows a significant number of successful retries, MOST SUCCESSFUL RETRIES, indicating users eventually succeed after initial failures.

### Sign-Up Method Analysis

#### Correlation with Operating Systems and Devices:
- Filtering out email sign-ups reveals:
    - Windows and Android swap places in the overall attempts ranking.
    - Half of the Android failures are linked to email registration attempts.
- **Social Media Sign-Ups:**
    - LinkedIn, Facebook, and Google sign-ups produce fewer failures compared to email.
    - This suggests that email registration on Android is particularly problematic.
- **Detailed Observations:**
    - When focusing on Google sign-ups, Android failures are fewer than those with email.
    - LinkedIn and Facebook sign-ups show even fewer failures, reinforcing the email issue on Android.

### Conclusion
- **Key Findings:**
    - Mobile sign-up issues, especially on Android devices, are a significant concern.
    - Email registration attempts on Android are identified as the most problematic area.
    - Addressing these issues should be a priority to enhance the overall conversion rate and user experience.

---

# Sign-Up Types Analysis Report

In this portion of report, we focus on understanding the different sign-up types and their popularity among users.

## Sign-Up Preferences
- **Preferred Sign-Up Options:**
    - Google: The most popular choice with over 54,000 visitors opting for it.
    - Email: Approximately 24,000 users choose to register via email.
    - LinkedIn and Facebook: Combined, these options account for nearly 11,000 visitors, with usage roughly split between them.
- **Conclusion:** Google is the 1st choice, indicating a preference for using existing accounts to sign in.

## Factors Influencing Sign-Up Choices
- **External Factors:**
    - **Google's Popularity:**
        - Google accounts are widely used for various online services, making them a convenient choice.
        - Facebook and LinkedIn serve different purposes—social connections and professional networking, respectively—which may explain their lower usage.
    - **Email Preference:**
        - Many users prefer email sign-up to avoid sharing personal information from social media accounts.
        - Email offers a sense of privacy, which is appealing to users wary of disclosing sensitive data.
- **Internal Triggers:**
    - **Convenience of Existing Accounts:**
        - Using an existing account simplifies access, eliminating the need to remember multiple credentials.
        - The process is straightforward: click on the Google sign-up icon and start using the platform.
    - **User Experience:**
        - Social media sign-ups are attractive if they offer a quick and hassle-free experience.

## Sign-Up Interface Analysis

### 365 Sign-Up Window:
- Options include Google, Facebook, LinkedIn, and email.
- **Visual Impact:**
    - Email sign-up fields are the most prominent, occupying the largest screen area.
    - Google's button, with its vibrant logo, is the second most noticeable.

- **Correlation with Sign-Up Attempts:**
    - The prominence of sign-up options on the screen influences user choice.
    - Users in a hurry or on mobile devices might default to the most visible options—email or Google.

### Mobile Device Considerations
- **Screen Size Impact:**
    - Smaller screens may lead users to overlook less prominent options.
    - This aligns with previous observations of mobile sign-up issues, particularly with social media options.

### Conclusion
- **Key Insights:**
    - Google and email are the top sign-up choices due to their screen prominence and global popularity.
    - Users appreciate Google's ease of use, which minimizes manual data entry and password creation.

---

# Sign-Up Success and Failure Rates Analysis Report

## Failure Rates Analysis
    Failure Rate= (Total Fail attempts / Total attempts) * 100 
- **Google vs. Email:**
    - Google Fail Rate: 3.2% 
    - Email Fail Rate: 6.5%, which is twice as high as Google's.
    - **Conclusion:** Email registration is twice as likely to fail compared to Google.
- **Social Media Sign-Ups:**
    - Facebook Fail Rate: 7.6%.
    - LinkedIn Fail Rate: 4%.

Google is the most favoured sign-up choice with the lowest fail rate, while email shows a significant fail rate.

## Device-Specific Challenges
- **Desktop vs. Mobile:**
    - Desktop failures: 700+ for Google, 200+ for email, 50+ for Facebook, and 40+ for LinkedIn.
    - Mobile failures: 1100+ for Google, 1400+ for email, 400+ for Facebook, and 40+ for LinkedIn.
    - This highlights significant challenges with mobile email sign-ups.

## External Factors and Solutions
- **Google Sign-Up Challenges:**
    - Users may abandon the process if signed into an unwanted Google account or not logged in at all.
    - Pop-up windows may be blocked by browser settings, a common Google error.
    - Coordination with the web development team is needed to address these issues.
- **Facebook Mobile Failures:**
    - 400+ failures with mostly unknown errors.
    - Clearer error messages are needed to identify and resolve these issues.

## Success Rates Analysis
- **Success Rates by Sign-Up Type:**
    - Google: 91% success rate (most successful method).
    - Email: 77% success rate.
    - LinkedIn: 87% success rate.
    - Facebook: 69% success rate.

## Conclusion and Recommendations
- **Key Insights:**
    - Google is the leading choice for sign-ups, with a high success rate despite challenges.
    - Email sign-ups face significant difficulties, especially on mobile devices.
- **Recommendations:**
    - Adapt the email sign-up process to mirror Google's efficient and user-friendly design.
    - Modify the email sign-up interface and functionality to reduce mobile registration difficulties.
    - This strategy aims to optimize the sign-up flow and enhance user experience.

---

# Login Patterns and Challenges Analysis Report

## Introduction
- After examining sign-up patterns, we now turn our attention to login behaviours on the website.
- This analysis is based on the third page of our sign-up story, which describes the login type and login related errors.

## Login Preferences
- **Preferred Login Methods:**
    - Email: The most preferred login choice, unlike sign-ups where Google led.
    - Google: A close second in login attempts.
    - **Note:** We observe visitor sessions rather than visitor counts, as users may log in multiple times using different methods.
- **Importance of Session Observation:** Observing sessions allows us to capture all login attempts, providing a comprehensive view of potential issues with each login type.

## Device Usage Insights
- **Desktop vs. Mobile:**
    - Most login attempts occur on desktop computers, likely due to users preferring larger screens for accessing course materials.

## Login Challenges
- **Email Login Issues:**
    - Approximately 55,000 unsuccessful attempts out of over 218,000, with nearly one-fourth resulting in failure.
    - Common errors include invalid email or password, often due to typos, forgotten passwords, or confusion with other accounts.
    - **Recommendations to reduce failures:**
        - Simplify password requirements if security allows.
        - Improve the forgotten password process.
        - Implement a "Remember me" option or suggest strong, auto-generated passwords.
- **Social Media Login Performance:**
    - Facebook and LinkedIn show significantly fewer failures.
    - Encouraging users to opt for social media logins could improve success rates.

## Google Login Challenges
- **Google Login Failures:**
    - 12,000+ failures, primarily due to users closing the Google pop-up window.
- **Operating System Analysis:**
    - Nearly half of the errors occur on Android, with the rest on Windows.
    - iOS and Mac desktops show fewer issues.

**Reasons for Google Pop-Up Closure**
- Possible causes include slow loading, technical issues, browser settings, or accidental closure.
- **Recommendations:**
    - Conduct manual tests of the Google login process to identify recurring issues.
    - Implement automatic alerts to guide users through resolution steps.
    - Suggest browser changes or adjustments to blocking add-ons if necessary.

**Strategic Considerations**
- Current focus is on modifying the sign-up screen, but insights from this analysis will inform future enhancements.
- The findings provide a framework for ongoing strategy to optimize user experience.

---

# Actionable Insights Report

## Introduction
The final part of our analysis report, where we outline actionable insights to achieve our business objective. Derived from data analysis, these insights offer precise suggestions to enhance business processes, products, or services. They address specific questions, problems, or goals and provide a clear path for action.

## Key Actionable Insights
1. **Emphasize Social Media Sign-Up Options:**
    - Reorganize the sign-up screen to highlight more efficient alternatives, especially Google, identified as the most successful option.
    - Single-click sign-up methods can improve the mobile user experience.
    - Making social media options more prominent can attract more users and potentially increase the sign-up success rate.
2. **Simplify the Email Sign-Up Process:**
    - Modify the process by initially displaying a "Sign Up with Email" button instead of empty input fields.
    - Redirect users to a separate page with required input fields upon clicking the button, making the process more intuitive and user-friendly.
    - Minimize email registration password requirements and simplify the password restoration process.
3. **Investigate Facebook Sign-Up Errors:**
    - Collaborate with the development team to identify and resolve the unknown error affecting Facebook sign-ups.
    - Ensuring a seamless sign-up experience for users choosing this option is crucial.

## Expected Outcomes
- Implementing these insights can improve user experience and increase the overall visitor-to-registered conversion rate.
- Continuous monitoring and analysis over the coming months and years will allow for further optimization and adaptation to user needs and preferences.

## Next Steps
- While conclusions are promising, they require rigorous testing before implementing substantial changes like altering the sign-up screen design.
- **A/B Testing Methodology:**
    - Apply A/B testing to measure the performance of different variations of the sign-up component.
    - Evaluate a version of the proposed sign-up window emphasizing social media options against the existing one.
    - Determine if the revised version outperforms the original.
    - If successful, convert the actionable insight into an actual website upgrade.
