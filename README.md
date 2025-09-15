# Name: Mopuri Ankitha
# Register Number: 212223040117
# Experiment-11
## Pytest Installation

# Aim:
To test multiple addition scenarios using Pytest without using the decorator and verify correct functionality of addition operation.

# Pytest:

Pytest is a Python testing framework that allows easy creation of simple as well as complex test cases. It helps in automating testing, detecting errors, and validating expected outcomes.

# Procedure:

1. Open the command prompt or terminal.

2. Create a Python file named `add.py` with the following content:

   ```python
   def test_add():
       test_cases = [
           (5, 5, 10),
           (3, 5, 8)
       ]
       
       for input1, input2, output in test_cases:
           assert input1 + input2 == output
   ```

3. Run the test using the command:

   ```bash
   python -m pytest add.py
   ```


# Output:
<img width="1641" height="639" alt="image" src="https://github.com/user-attachments/assets/f01cd0a5-3938-4222-a394-eb5f37c1e0be" />



# Result:

The test ran successfully, passing all test cases.
This confirms that the addition logic works correctly for the provided inputs without using decorators.



