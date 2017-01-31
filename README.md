<!-- TOC depthFrom:1 depthTo:3 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Engima 2017 Notes](#engima-2017-notes)
	- [Behaviors and Detection](#behaviors-and-detection)
		- [StreamAlert: A Serverless, Real-time Intrusion Detection Engine](#streamalert-a-serverless-real-time-intrusion-detection-engine)
	- [Neuroscience and Security](#neuroscience-and-security)
		- [Neural and Behavioral Insights on Trust](#neural-and-behavioral-insights-on-trust)
		- [What Does the Brain Tell Us about Usable Security?](#what-does-the-brain-tell-us-about-usable-security)
	- [Security Helping Society](#security-helping-society)
		- [Security in the Wild for Low-Profile Activists](#security-in-the-wild-for-low-profile-activists)
		- [Won't Somebody Please Think of the Journalists?](#wont-somebody-please-think-of-the-journalists)
		- [Why Philanthropy is Critical for Cybersecurity](#why-philanthropy-is-critical-for-cybersecurity)
		- [Security for Vulnerable Populations](#security-for-vulnerable-populations)
	- [Trustworthy Computing](#trustworthy-computing)
		- [Beyond Warm & Fuzzy: Ethics as a Value Prop](#beyond-warm-fuzzy-ethics-as-a-value-prop)
		- [A](#a)

<!-- /TOC -->

# Engima 2017 Notes

## Behaviors and Detection

### StreamAlert: A Serverless, Real-time Intrusion Detection Engine

#### Overview
- Low cost
- Role based Access Control - AWS IAM

#### Writing Rules
- User defined function that evaluates to false/true
- Rule looks like this:
```python
@rule('invalid_user, ...)
   def invalid_user (rec):
     return true
```

## Neuroscience and Security

### Neural and Behavioral Insights on Trust

##### Overview
- More activity in Amygdala related to more distrust.
- Don't make people think of things they don't do in offline situations
  - Example: Store credit card at checkout.
- Don't make people think about uncertainity (50/50 risk).
- People hate ambiguity (no/little information about risk and reward) even more than uncertainity.
- Activity in Amygdala doesn't clearly mean that people distrust online activity, but it may be related.

##### Toy task
- 100 chips in bag. Red or Blue. No other color.
- If I draw Red, you win!
- But I may not tell you how many Red chips there are.
- Result: Finding out more data makes you more confident. (Makes sense.)

##### Summary
- Don't focus on trust -- focus on uncertainity.
- Favorable and unfavorable information has value for uninformed.
- How people feel is critical in determining how people act.


### What Does the Brain Tell Us about Usable Security?

##### Overview
- If asked to choose between dancing pigs and usable security, users would always choose dancing pigs. That's sad.
- Most people don't notice the "Chrome cleanup tool" message popup.
- We're bad at multi-tasking. Performance on all tasks suffers.
- Security messages are displayed usually as a result of a security event without regard to user's current task. (Cue: Microsoft Update doalog)
- Ran a study
  - Have a baseline task.
  - Then have a memory task (6 digit number to remember).
  - Then added a task to install a Chrome extension that may have dangerous permissions.
  - <Something I missed>
- Results:
  - High dual task message: Warning disregard: 22.9%
  - Showing warning later: Warning disregard: 7.4%
- Low DTI times:
  - After video completes.
  - Waiting for download to complete (or start?)

##### Takeaways
- Brain not good at handling interruptions.
- Timing a security messages makes a marked improvement.

##### Habituation
- Observed in all animal life. Including human brain.
- Each display of warning, brain pays less and less attention.
- 40 real world wawrnings in FMRI scanner.
- Dramatic drop in activity after second exposure to warning and drop off after successive exposures.
- Also increase in boredom.
- Then added animations to the warnings. Swirl, Jingle, ...
- Notably better results.
- Still led to bordom and ignoring warnings with polymorphic warnings but still higher than static warnings.

##### Mobile experiment
- Install 3 apps from a category of apps every day.
- Warning on install.
- If they ignored warning, that was counted as disregard.
- Chose 4 really bad warnings.
- Polymorphic warnings (different warning format over 15 days) had better effect.

##### Habituation carries over
- Dismissing one kind of notification (eg system notification on phone) can carry over to rare security events.
- User may already be deeply habituated.
- Design security messages to be visually distinct and/or different mode of dismissal.

*Not only think about the bad guys, but also think about the user who needs to respond to the security warnings, etc.*

## Security Helping Society

### Security in the Wild for Low-Profile Activists

##### Overview
- There's an app for that! To measure and track all your signals and activity.
- Helps people keep track of their life, fun activities, etc.
- Idea: Devices attached with brain. Non-invasive.
- But, wait.. Malware! In the brain!

##### Brain spyware
- Any malicious app that extracts private information about the user.
- Why/how does it work:
  - A malicious app could intercept the digitized signal from the sensor to the signal processing app.
  - Event Related Potentials (ERPs): Responses associated with specific sensory, cognitive, and motor events.

##### Subliminal Brain Spyware experiment
- During the game:
  - 5 different stimuli for 7 seconds at a time.
  - Different logos such as Starbucks, ...
  - Measured ERPs

- Brain signals can then be used to find out:
  - Coffee preferences, but also
  - Religious preferences,
  - Political preferences, etc.
  - Privately held thoughts can be captured(?)

...

##### Mitigation: BCI Anonymizer
- Idea: Neural signals should be treated as PII


### Won't Somebody Please Think of the Journalists?

#### Overview
- When a journalist is kidnapped, you can help them financially but not erase the horror.
- When they die, there's absolutely nothing you can do for them.
- Technical attacks against journalists but not enough security community focus.
- Motivated state actors have the resources to find vulnerabilities and deploy them as needed.
- **Focus on security requirements for a journalist, and then**
- **Adopt those products/ideas to people at large.**

- Being a journalist used to be expensive: Camera, Printing press, reach, ...
- That's not true anymore.
- Everyone has a camera now, and a blog, or Medium.

##### Change from focussing on keeping journalists safe to journalism safe
- Everyone should have the ability to be safe about their communications.

##### Questions
- Computers today are garbage. We need better computers.
- How do we distinguish between acts of journalism and acts of alternate reality.
  - There are good journalists, there are bad journalists. And then, there are liars.
- What should be focus on?
  - Passwords are garbage. Phishing is easy.
  - #1 priority is to make authentication work.
  - Hardened or proven kernels.
- Why not focus on anonymity?
  - Not a lot of people die because of lack of anonymity.
  - Plus, there are some good tools already for that.

### Why Philanthropy is Critical for Cybersecurity

##### Overview

##### Another


### Security for Vulnerable Populations

##### Overview

##### Another

## Trustworthy Computing

### Beyond Warm & Fuzzy: Ethics as a Value Prop

##### Overview

##### Another

### A

##### Overview

##### Another
