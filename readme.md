# 404B Lesson 3 Class Exercise - Return Values

## Instructions

### Split VS Code Window

You can drag `main.py` tab to the right side of the window to split the window into two panes. This will allow you to see the instructions and the code at the same time.

### Answering

You can answer the questions by writing your answers in the `main.py` file.

You can run the code by clicking the `Run` button on the top right corner of the editor.

The output will be shown in the `Terminal` tab at the bottom of the editor.

## if/elif/else Examples

### Sample

```python
def square_a_number(x):
   result = x * x
   return result

sq1 = square_a_number(5)   # sq1 = 25
```

## Questions

1. What is wrong with the following code, which attempts to add all numbers from 1 to a given maximum? Correct the code.

   ```python
   def cube_a_number(x):
       result = x * x * x

   cubed_res = cube_a_number(10)
   print(f'The result is {cubed_res}.')
   ```

2. What is wrong with the following code, which attempts to check if the given number is even number? Correct the code.

   ```python
   def is_even(n):
       if n % 2 == 0:
           # ???
       else:
           # ???
    
   result = is_even(13)    # result => True or False
   print(f'13 is even: {result}')
   ```

3. Simplify the program in Q2 without using if/else.

4. Write a program that accepts an integer representing a student’s grade percentage in a course and returns that student’s numeral course grade.
  
   The grade can be between 0.0 (failing) and 4.0 (perfect).

   ```python
   ...
   
   alice_score = score_to_gpa(50)  # 2.0
   bob_score = score_to_gpa(90)    # 3.6
   ```

## Challenge

The following method attempts to return the median (middle) of three integer values, but it contains logic errors.

In what cases does the method return an incorrect result?

How can the code be fixed?

```python
def middle_of_3(n1, n2, n3):
   if n1 < n2:
       if n2 < n3:
           return n2
       else:
           return n3
   else:
       if n1 < n3:
           return n1
       else:
           return n3
```

## Submitting Your Work

1. Make sure the assignment repository is opened in VS Code.

2. Make sure you have completed all the tasks.

3. (First time only)
Use Command + J to open the Terminal tab and config your git username and email:

    ```bash
    git config user.name "Your Name"
    git config user.email "Your GitHub Email"
    ```

4. Click on the "Source Control" icon on the left. Source Control

    ![1](https://github.com/BlueinnoClassroom/404B-L2.1-Template/assets/155412668/2c31026e-c14d-484f-bb9e-dc87189a0216)

5. Enter a commit message and click on the "Commit" button.

6. Click on the "Sync Changes" button.
