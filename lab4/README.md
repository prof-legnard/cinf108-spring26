# Lab 4
For this lab we are going to work with dictionaries to analyze some fake retail data from a small electronics store. This will test your ability to work with dictionaries and lists (or tuples). You may use your full knowledge of Python to solve each question. Remember that you have the following at your disposal:
- loops (for/while)
- conditional statements (if/elif/else)
- functions (create your own `def`, use built-ins)
- lists, dictionaries, tuples, strings (any standard data types we have gone over)
- list comprehensions

You may not import any external public Python libraries for this assignment. I want to see you work with the tools above.

Starting with the lab4 files, `lab4_template.py` and `retail_data.py`, run `lab4_template.py` to familiarize yourself with a python dictionary, and accessing it's keys and values. Then add code to answer the questions below.  Submit one `.py` file with the answers to the questions. You do not need to submit `retail_data.py` Make sure the import statement at the top of the template code is in your submission, and you are using `RETAIL_ITEMS` in some capacity, or else when I run your code to grade it won't work, and you will lose points.

## Setup Instructions
Create a `lab4` folder on your computer. Download the contents of the `lab4` folder in this github repository into your `lab4` folder. 

(you can either the code and save it into a file, hit the download button in the Github UI,  or if you have working knowledge of `git`, and can figure it out, clone it to your desktop)  

Before you start, your folder should contain the following:
```
├── README.md
├── lab4_template.py
└── retail_data.py
```
You will need `retail_data.py` for `lab4_template.py` to work. **Do not modify** `retail_data.py`. If you are tasked with modifying the dictionary, make a copy of the dictionary or make the adjustments to the data structure with Python statements in your submitted lab .py file.

Open a VSCode workspace from this folder (or set the current working directory or Powershell/terminal to be this folder). Run `lab4_template.py`
Once you are able to run `lab4_template.py`, save it as your lab submission file: `lastname_firstname_lab4.py`.

You may modify the template code as you see fit, just do not modify `retail_data.py`, or modify the `import` statement on line 1 of `lab4_template.py`. You may work with the global `RETAIL_ITEMS` variable as is, but I have provided some code that converts it into a nested dictionary, if that's easier for you to use.
After completing the following, and checking to make sure your code runs, submit your `lastname_firstname_lab4.py` file on Brightspace.

## Retail Analysis Questions

You can now answer the questions below, and attach this `lastname_firstname_lab4.py` file in your submission. **For any calculations with prices, round to two decimal places, and include dollar signs**. Each question is worth up to 5 points.

1. (5 points) Use the bracket [] notation and the correct keys and print the following values, make sure your print statements are labeled with contextual information and formatted: 
   - a. The full dictionary of keys and values for the "Portable Bluetooth Speaker"
   - b. The price of the "Wireless Headphones X1"
   - c .The total units sold, 2024 and year-to-date (`ytd_units_sold`) for "Electric Scooter V2"
   - d. print all the highest level keys of `retail_dict` in one line.
2. (5 points) 
- a. Write a for loop that will provide the revenue for each retail for the year 2024
revenue = [2024_units_sold] * price

- b. With Python, calculate and print the total revenue for 2024.

3. (5 points) Write a loop and/or use your knowledge of dictionaries identify how many more units
of each item available needs to be sold (YTD) in 2025 to meet the same number sold for 2024.

4. (5 points)
    - a. A new product is coming to the store! The "Gaming Console 3". Add a new key: value pair with "Gaming Console 3" as the key and a new dictionary as the value. Add key value pairs for this new retail item dictionary.The price should be set to $599.99. Set the ytd_units_sold to 0. Print your full dictionary orjust the new portion with details on "Gaming Console 3" to show it has been added.

    - b. How many units of "Gaming Console 3" need to be sold for that revenue plus the YTD revenue units sold for 2025 for "Gaming Console 2" to match the total 2024 revenue for  "Gaming Console 2".

    Use your knowledge of loops and dictionaries to calculate this revenue
    value. Write a print statement describing how many units need to be sold, as well as
    the revenue values for Gaming Console 2 in 2024, and (Gaming Console 2 + Gaming Console 3)
    units sold YTD.

5.(4 points)
The store manager is reporting numbers to the corporate office, but forgot to account
for a sale on "Electric Scooter V2" applying a 25% discount to 30 of the units sold in 2024.

What is the adjusted revenue figure for 2024 units sold for "Electric Scooter V2" retail item, where revenue would
decrease based on this discount, calculate and print this figure using python so the store manager can add it to their reporting.

1 POINT FOR CORRECT FILENAME - total 25 points.
