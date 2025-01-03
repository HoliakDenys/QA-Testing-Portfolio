Accessibility Testing Report

Overview
This report provides the results of accessibility testing performed on a website using the WAVE accessibility evaluation tool. The goal of this test was to identify potential accessibility issues that could hinder users with disabilities from interacting effectively with the site.

Testing Tool
1. Tool Used: WAVE (Web Accessibility Evaluation tool)
2. Website Tested: https://www.wikipedia.org/

Findings
1. Empty Form Label. Count: 1. This issue occurs when a form label is present but does not contain any text. This makes it difficult for screen reader users to understand the purpose of the form field. Recommendation: Ensure that the form label contains text that describes the function of the associated form control. Labels are not required for image, submit, reset, button, or hidden form controls. If a label is not necessary visually, a descriptive title attribute may be added to the form control.
2. Language missing or invalid. Count: 5. The page is missing a valid language attribute (lang) or it is set incorrectly. This can make it difficult for screen readers to interpret the content properly, leading to accessibility issues for users with disabilities. Recommendation: Identify the document language using the <html lang> attribute with a valid value (e.g., <html lang="en">). Ensure that all lang attribute values are valid.
3. Very low contrast. Count: 1. This issue refers to the text not having enough contrast against the background. Low contrast can make it difficult for users with low vision or color blindness to read the content. Recommendation: Increase the contrast between the foreground (text) color and the background color. Large text (larger than 18 point or 14 point bold) does not require as much contrast as smaller text.
