https://docs.google.com/document/d/1vY8sC8DvY2Fn93E-TBujV--IKvgpqCcHKkH3WrggTDE/edit?usp=drivesdk

https://github.com/user-attachments/assets/b0512d1a-34c8-42bd-9510-4509283153f7

Part 2: Practical Implementation (60%)

Task 1: AI-Powered Code Completion

Tool: GitHub Copilot

Manual Implementation:

def sort_dict_list(data, sort_key):
    return sorted(data, key=lambda x: x[sort_key])

Copilot-Suggested Version:

def sort_dicts_by_key(lst, key):
    return sorted(lst, key=lambda d: d.get(key, ''))

Analysis: Copilot suggested a safer implementation using .get() to avoid key errors, making it more resilient. Both are efficient (O(n log n)), but Copilot's version handles edge cases. The AI-assisted version is preferred due to its robustness and time savings.

Task 2: Automated Testing with AI

Framework: Selenium + AI Plugin (e.g., Selenium IDE with Testim.io integration)

Test Case:

Valid login: Correct credentials → redirect to dashboard.

Invalid login: Wrong credentials → show error message.


Result Screenshot: [Screenshot in Report]

Summary: AI enhances test coverage by auto-generating test paths and detecting changes in UI. Unlike manual testing, it quickly adapts to new elements and reduces regression bugs. This saves time and increases reliability.

Task 3: Predictive Analytics for Resource Allocation

Dataset: Kaggle Breast Cancer Dataset (repurposed to simulate issue prioritization)

Workflow:

1. Loaded and cleaned dataset.

3. Engineered features and labeled samples as high/medium/low risk.


4. Trained Random Forest Classifier.


5. Evaluated with train/test split and metrics.



Performance:

Accuracy: 96.1%

F1 Score: 95.8%

Part 3: Ethical Reflection (10%)

Reflection: Deployed models may reflect hidden biases from skewed datasets—e.g., prioritizing tasks from historically dominant teams. IBM AI Fairness 360 can audit models for fairness, analyze feature impact, and mitigate bias through preprocessing and reweighting. Integrating such tools ensures just and reliable predictions.

Codebase: GitHub Repository

Bonus Task: Innovation Challenge (10%)

Proposal: IntelliDocs – AI-Powered Documentation Assistant

Purpose: Automatically generates and maintains code documentation using NLP.

Workflow:

1. Scans source code for functions/classes.


2. Uses NLP to generate explanations and docstrings.


3. Integrates with CI to update docs automatically.



Impact:

Reduces time spent on documentation.

Boosts code readability and onboarding.

Encourages consistent documentation standards.

