# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Kate Ysabel D. Cam
- Section: TN36
- Repository name: `it0123-devnet-resource-plan`

## Purpose
Selecting the correct DevNet resource ensures that the decisions the developer makes meet the requirements for different uses. The use of DevNet resource greatly impacts security, efficiency, and the success of the deployment. Chosing the wrong DevNet resource will hinder the developer "

## Validated Resource Decisions
Use Case 1: "A student team needs immediate access to a shared Cisco environment to practice safe read-only API requests. Administrative changes are not required, and the team cannot wait for provisioning."

    According to the official Cisco Developer Page, Always-On Sandboxes provide the instant access without provisions. With restricted administrative access, it meets the requirements of the use case. In conclusion, the AI Assistant also provided the correct suggestion.

    https://developer.cisco.com/docs/sandbox/getting-started/#always-on-sandboxes

Use Case 2: "A development team must test configuration changes with administrative access in a private environment. The team can schedule access, use a VPN, and accept setup time."

    According to the DevNet Resources website, Reservation Sandboxes are private access environments with Administrative Access. Here they have In-lab Automation Tools and custom setup automation for a team to use. The AI Assistant also provided the same suggestions.

    https://developer.cisco.com/docs/sandbox/getting-started/?utm_source=chatgpt.com#reservation-sandboxes

Use Case 3: "A beginner needs structured, step-by-step learning content before attempting an independent API activity. The immediate goal is guided practice rather than access to administrative devices."

    In the official Cisco Developer Page, Learning Labs provides interactive tutorials where developers can learn about processes through reading Modules and going on Learning Tracks. With this, a beginner can use these resources to learn differnt concepts before attempting an independent API activty. The AI assistant also provided the same suggestions. However, it provided me with the wrong link so I navigated to the Learning Labs website instead.

    https://developer.cisco.com/learning/

Use Case 4: "A developer wants to examine community and Cisco-maintained code repositories for an existing network-automation use case before designing a new solution."

    According the DevNet Resources website, Cisco Code Exchange provides code examples and automation use cases in an online, curated set of code repositories. Developers can look through the website to explore code repositories to get ideas on their own solution. AI assistan provided the correct suggestion but also provided the incorrect link.

    https://developer.cisco.com/codeexchange/about/ 


## AI Evaluation
All AI recommendations were accepted except for the Learning Labs and Code Exchange links as it only gave the home page. With this, I ended up navigating through the website to validate the information further and all suggestions matched  with the DevNet Resource information.

## Validation Evidence

- Validator result:
    PASS: JSON file loaded
    PASS: student and AI disclosure completed
    PASS: all four scenario IDs present
    PASS: resource classifications match scenario requirements
    PASS: official Cisco evidence URLs supplied
    PASS: AI verification statuses are valid
    PASS: rationales are sufficiently detailed
    PASS: AI recommendations are summarized in the student's own words
    PASS: no credential-like fields detected

    VALIDATION COMPLETE: 9/9 checks passed.

- Command used: python validate_plan.py

- Official Cisco pages reviewed: 
    https://developer.cisco.com/docs/sandbox/getting-started/#always-on-sandboxes 
    https://developer.cisco.com/docs/sandbox/getting-started/?utm_source=chatgpt.com#reservation-sandboxes
    https://developer.cisco.com/learning/
    https://developer.cisco.com/codeexchange/about/ 

## Git Evidence

- Initial commit message: Initial Commit of README.md file
- Validation commit message: Answers Validated 9/9
- Output of `git log --oneline`:
    3f7f015 (HEAD) Answers Validated 9/9
    e0521b1 UC 4 Answered and corrections on UC 1 resource field
    f67b4f3 Adding the right DevNet Link
    f5605d4 UC 3 answered
    29daf45 UC 2 answered
    e71abfc UC 1 answered with references
    d3f203a Blank Student JSON
    672b9ad Initial Commit of README.md file

## AI-Use Disclosure
ChatGPT was used to assist in the completion of these requirement. Each answers have been validated thoroughly.
