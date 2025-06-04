# TTR-WAF Risk Score Calculator

A web-based calculator to estimate the TTR-WAF risk score based on specific clinical parameters. This tool is intended for educational purposes.

**Access the Calculator:**
[Link to your GitHub Pages URL]

**About the Score:**
This calculator implements a scoring system based on:
* Absence of diabetes mellitus (RS = 1)
* No prior ischemic stroke (RS = 1)
* No use of anti-thyroid drugs (RS = 2)
* Achieving first therapeutic INR within 15 to 28 days (RS = 2)
* Total warfarin dose < 20 mg/week for first therapeutic INR (RS = 1)

A total score of 5 or more suggests "Likely TTR ≥ 70%", while a score less than 5 suggests "Less likely TTR ≥ 70%".

**Disclaimer:**
This calculator is for educational and illustrative purposes ONLY. It is NOT a substitute for professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare professional.

**Technology:**
HTML, Tailwind CSS, JavaScript
