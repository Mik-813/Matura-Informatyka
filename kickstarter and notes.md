## Quick Start Guide for the Practical Part

0. Make sure you have permission to create, edit, and import files/folders in your chosen directory.
1. Create a *root* folder with `Ctrl + Shift + N`, named after your PESEL number (it's best to know it by heart).
2. Open this directory with **PyCharm**.
3. While **PyCharm** is opening, create a folder called `dane` and move the provided `załączniki` (attachments) into it.
4. Once it has opened, use `Ctrl + N` to add new files:
   - `wyniki4.txt`
   - `zadanie4.py`
5. To run `zadanie4.py`, press `Ctrl + Shift + F10`.
6. Import the data into `python`:
    > *Assume the file is called **name***
    ```python
    1   file = [x.strip() for x in open("dane/name.txt").readlines()]
      
    # if the data consists of numbers, it's better to write int(x.strip()) right away
    ```
- Copy the line above and change `name.txt` to `przyklad.txt`.

    Comment out one of them:

    ```python
    1    # file = [x.strip() for x in open("dane/przyklad.txt").readlines()]
    2    file = [x.strip() for x in open("dane/name.txt").readlines()]
    ```
- Now, to switch between them quickly, click on the line above and press `Ctrl + / + /`:
    ```python
    1    file = [x.strip() for x in open("dane/przyklad.txt").readlines()]
    2    # file = [x.strip() for x in open("dane/name.txt").readlines()]
    ```
    Simple and fast.

## Notes:

> When entering tables into `wyniki`, always include column headers if there is more than one column.

> For every programming task, ALWAYS check your data against `przyklad.txt`.
Checking doesn't take much time and makes you more confident in your answer.

> In PyCharm: `Ctrl + Alt + S` > `keymap` > switch `Windows` to `Sublime` for better shortcuts.

> While working on tasks, don't delete your ***draft/scratch*** data - instead, move it to a separate sheet, but make sure to keep it.

> In **Excel**, you can use *smart* paste with `Ctrl + Alt + V`.

> It's better not to create the Access file right away, as this can cause saving issues. Instead, save from within the program itself once all the data has already been imported.
> Also, when writing multi-step queries, first output and check all the columns you need before moving on to further processing steps.

> Stay calm about errors, don't be intimidated by them. Reread the task instructions.

> Read everything written in the task carefully, otherwise you might miss details that matter for completing it.
> Make sure you understand the task and exactly what is being asked of you.
> If you don't do this, you'll end up completing the task incorrectly.

> Do not close **PyCharm** during the entire exam.
**PyCharm** is more convenient for viewing and editing text files (wyniki). You may also need help from a programming language for one of the tasks.

> It's more convenient to write queries in **PyCharm** - for this task, I create a file called `zadanie6.sql`.
> Don't delete it either - if Access somehow loses your data, you'll always have a guaranteed backup solution.
> If you decide to use this method, write a comment in the `zadanie6.sql` file listing the names of all tables and their columns.
> **PyCharm** will use this for `autocompletion`, so you won't have to keep retyping them.

> At the end of the exam, delete the `.idea` folder from the root directory.

#### Good luck.
