## GenA11y

- Install the required Python packages through `requirements.txt`.

- Create a `.env` file located in the A11yDetector folder. The key name should be *OPENAI_API_KEY*, and replace the value with your actual OpenAI key.

- Locate `executor.py` in the Executor folder and run the main function.

- A report is generated for each criterion. If there is an accessibility issue for a criterion, the result is provided in the following JSON format.

  ```python
  {
      "overall_violation": "Yes or No",
      "violated_elements_and_reasons": [
          {
              "element": "outerHTML of the element",
              "reason": "Explanation of why it violates the criterion",
              "recommendation": "Recommendation to fix the violation for this specific element"
          }
      ]
  }
  ```

  
