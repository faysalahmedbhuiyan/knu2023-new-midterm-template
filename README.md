# (new) Midterm Exam: Analyze member function structure.

Your submission must satisfy the following requirements:

* R1. Shall initialize your assignment repository from https://classroom.github.com/a/l-_DumVf
* R2. Write your `extractor.py` in the repository.
* R3. Test your `extractor.py` by using `pytest`.
* R4. You need to let your TA know your repository URL and your student ID together via Slack.
* R5. Check out `test_extractor1.py` to figure out the output format.
* R6. Assume that there are no nested classes and anonymous classes.
* R7. Assume that the source code may contain a nested function.
* R8. The function `collect_function_structure` takes a path of a Python file, and produces a dictionary of function structure metrics for each function in each class. (type hint: Dict[str, Dict[str, Dict[str, int]]] ):
```
{'class1': {'func1': {'num_total_if': num1, 'max_nested_if': num2, 'num_total_for': num3, 'max_nested_for': num4}, ...}, ...},
```
* R9: Asynchronous functions (`async def`) should be included.
* R10: Asynchronous for (`async for`) should *NOT* be counted.
* R11: Assume that all classes have at least one function.
* R12: If a function contains nested functions, the function's metrics should be computed, including the structures of the nested functions. In addition, each nested function should be included as well.


## Note:

* N1. `pytest` (based on `test_extractor1.py`) is just for validating your program. The final grading will be made by other test cases.
* N2. Submissions via GitHub Classroom will only be accepted. Submissions via LMS or any other means are not accepted.
* N3. DO NOT change files in this repository except for `extractor.py`. Adding new files is allowed.
* N4. Late submissions after 4:15pm are *NOT* allowed.
