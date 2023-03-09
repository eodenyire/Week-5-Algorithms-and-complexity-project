# Week-5-Algorithms-and-complexity-project
Title: Algorithms and Complexity Analysis in Python(Laptop Store Inventory)

This project implements an inventory management system for a laptop store. It uses a CSV file (laptops.csv) as the data source for the inventory, and provides the following functionalities:

search function: Given a dictionary of search criteria (e.g. brand, price range, screen size), the function returns a list of laptops that satisfy the criteria.

get_manufacturers function: Returns a list of all the laptop manufacturers in the inventory.

get_prices function: Returns a list of all the laptop prices in the inventory.

check_promotion_dollars function: Given a dollar value, checks whether there are one or two laptops in the inventory whose prices add up to that dollar value. Returns True if such laptops exist, otherwise returns False.

check_promotion_dollars_fast function: Similar to check_promotion_dollars, but uses a set of unique prices in the inventory to perform the check more efficiently.

The project includes a test file (test_inventory.py) that tests the functionalities of the inventory system using the unittest module. It also includes a benchmarking file (benchmark_inventory.py) that compares the performance of check_promotion_dollars and check_promotion_dollars_fast on a list of random prices.

Usage
To use the inventory management system, create an instance of the Inventory class, passing the name of the CSV file that contains the inventory data:

inventory = Inventory('laptops.csv')

You can then use the various functions of the Inventory class to interact with the inventory.

CSV file format
The CSV file that contains the inventory data should have the following columns:

id (int): A unique identifier for each laptop.
company (str): The name of the laptop manufacturer.
product (str): The name of the laptop model.
type (str): The type of the laptop (e.g. Ultrabook, Gaming, Business).
inches (float): The size of the laptop screen in inches.
resolution (str): The screen resolution of the laptop.
cpu (str): The name of the CPU used in the laptop.
ram (str): The amount of RAM in the laptop.
memory (str): The amount of storage memory in the laptop.
gpu (str): The name of the GPU used in the laptop.
os (str): The operating system used in the laptop.
price (int): The price of the laptop in US dollars.
The CSV file should have a header row that specifies the column names.

Source data set: https://bit.ly/3G32iYj


Colab shareable notebook: https://colab.research.google.com/drive/1fdINhMTCXIoicL6bw22bkLAo7SZHIPJU?usp=sharing

We hope you find this project useful and informative. Happy coding!
