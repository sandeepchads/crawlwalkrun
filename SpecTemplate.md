# Spec Template

Work item: _add a link_
Product Manager: _PM Name_
Date: _date when you author the spec_

Author’s note: The template should help you in outlining the key aspects while writing a spec. Feel empowered to move sections around, make new ones, but make sure you answer: “what are we building and why?”

## Summary
This is your short and sweet elevator pitch. What are we building and why? It should help the reader understand in a few lines, what is the value that you wish to deliver by shipping this feature. 

## Problem 
This section should contain: What problem are we addressing? How do we know that this is a problem? What is our source of data?  What assumptions are we making? 
Are we seeing evidence of this problem in:
-	User feedback? You can site the source of the information : UserVoice, public forums, interviews, research, blog posts, social media etc.
-	Telemetry/ Metrics? (each PM is expected to know the product metrics)
-	User research? 
-	What are our competitors building?

## Personas 
Who are our intended users? 
How big is that population? 

## Urgency
How does this work fit in with our product-wide priorities and strategy?  
Why should we address this problem now? 
What is the size of this opportunity?

## Scope
What are the scenarios and personas that are in scope of this document. 
Non-goals
What work is out of scope for this project? What problems are we not solving now?

## Current experience 
Is there a gap in the current experience? If yes, then articulate it.

## Competitive / Partner landscape
What do competitor products do here? Anything to learn or unlearn?

## Proposed Solution 
This section should be fleshed out: What do we want to build/do to address the problem? How can we know its successfully addressing the problem? 

Consider sections such as: 

### Guiding principles 
Are there any guiding rules we want to guide our design and implementation? Are there any hard requirements? 

### Scenarios
List of user goals or stories. Depending on the feature, these can be high level, like Jobs to be done, or low level like simple “I can…” statements. The Design Review Template uses the form: “As a user ___ so I can _____ because ________.” 
Which of these are required and which are nice to have (P0, P1, etc)? Consider adding these in a table if necessary.
Define the MVP scenarios that must be accomplished.

### Measuring success and OKRs
How will we know our solution is successful at addressing the problem? How are we validating our hypothesis? Note that addressing the problem isn’t always the same as feature engagement. When would we ship worldwide and when would we kill it off/iterate on the experience? 

## Design details 
This is where a user experience walkthrough or more detailed flows would be useful. Feel free to put them in a linked slide deck if that’s more convenient. You can think of:
-	Happy path scenarios
-	Corner cases
-	Important edge and error cases  
-	Accessibility requirements 

### Implementation 
This section should be fleshed out: how are we going to deliver the proposed solution? How are we going to validate our assumptions? This doesn’t need to be a comprehensive spec but should answer any big questions before development starts. Or these could also be things that the engineering team should keep in perspective while building the technical design.

### Performance 
What are the performance metrics that you expect from your feature. Focus on perf metrics that are relevant for your scenario.

### Telemetry
Are there other data points you’d like to collect, beyond what is called out above in the “Measuring Success” section?  Capture why are these metrics important? For a service refer to availability, reliability, and performance of a service. 

### Privacy/Security Concerns 
Have you talked to your privacy and security champ? Is there anything notable that needs to be done in this area? 

### Security & Access Control
Does your feature require any additional security requirements? 

### Costing
It is crucial that the PMs estimate how new product features will impact the COGS (Cost of good sold). Think about the impact of this feature on cost and how do you assess the pricing or price tiering of this feature. 

### Timelines
This section covers how you wish to deliver the feature from a roadmap and timeline perspective. While you focus on dates, also mention what you’d like to learn/measure at each stage.
Also state whether there are any commitments, agreed upon timelines, or estimated time to complete various milestones of the product delivery.

### Dependencies
Are there big technical or organizational dependencies? When will you want them to be ready? 

### Exposure
Are you planning a controlled exposure of the feature to few customers or regions. Layout the plan in this section.

## Other resources (optional)
Are there older specs, research reports or documentation that can add extra context here? If you haven’t linked to them yet, they may be worth adding here. 

## Open questions (optional) 
This section is a good place to put unanswered questions that you have while writing. 
