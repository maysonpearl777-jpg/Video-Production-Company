A/B Test Plan - Sage & Frame Studio Digital Marketing

Page: Wedding Videography
Element Changed: $400 discount on wedding 2 package. 

Version A (Control group): The original wedding videography package, with The Story package is offered at $4,000, which includes: eight hours of coverage, two filmmakers, professional audio, full ceremony coverage, and 6-8 minute cinematic film.

Version B (Treatment group): Features the same wedding videography page, but lists the Story package at $3,600 striking $4,000, which will show a seasonal $400 discount for winter weddings with the time-frame being in December through February. All other content on the page will remain the same. 

Hypothesis: Version B will have a higher percentage of people who will purchase the story package compared to Version A. I think this because with a lower deal, people will be more prone to purchasing the second most expensive package due to scarcity bias and couples who want a winter wedding will find the discount to be more affordable. 

Model: ChatGPT Codex GPT-6

Target Audience: Engaged people in the Midwest who are planning a winter wedding. 

Exact Prompt: AI Prompt:

You are an engaged person in the Midwest planning a winter wedding. You are comparing wedding videography packages from several companies and have a limited wedding budget.
Review the wedding videography packages on the following website:

[INSERT WEBSITE LINK]
Decide whether you would purchase The Story package at its advertised price.

Consider the package's price, included services and your wedding budget.

Answer only Yes or No, followed by one sentence explaining your decision. 

Assignment: I will list 50 A trials and 50 B trials, then I will use rand() generator to sort the trials into a random sequence, so there will be an even 50 A trials and 50 B trials but they are conducted in a random order.

Primary Outcome: The primary outcome will be the percentage of AI visitors who indicate willingness to purchase the story wedding videography package. Yes = 1: The AI visitor chose to buy the package, and anything other than yes = 0: any response that is not a definite yes (no, maybe, something unexpected).

Sample Size & Timeline:
I will include 100 AI visitor trials, with 50 trials per version.
	- November 8: Commit the plan to Github
	- November 17: Publish version B and launch the experiment
	- November 19: Complete all 100 AI visitor trials in the same day with the same model and record the results.
	- November 26-30: Analyze the results and prepare the final report
	- December 1: Submit the final project by deadline

Comparison & Significance: 
I will compare the percentage of AI visitors that answered "yes" for both versions separately. The difference in purchase-intention rates will be measured in percentage points. A two-proportion statistical test will be conducted to evaluate whether the observed difference could be reasonably attributed to chance. The point at which I will determine significance will be 0.05 or below. 
