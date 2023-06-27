# python_json_converter
This Python script demonstrates the functionality of handling employee information and writing it to a JSON file. It includes functions to create a dictionary with employee details, convert the dictionary to a JSON string, and write the JSON string to a file. The script utilizes the json package and imports specific variables and functions from an employee.py module.

By executing the script, the details of an employee are printed using the details() function. The create_dict function is then used to create a dictionary containing the employee's information, such as their name, age, and title. This dictionary is converted to a JSON string using the json.dumps() function and stored in a variable called json_object.

To persist the employee information, the write_json_to_file function is called to write the JSON string to a file specified by the output_file parameter. The file is created and the JSON string is written to it.

This script serves as a basic example of how to manage and store employee data in a JSON format. It can be used as a starting point for more complex employee management systems or as a reference for working with JSON files in Python
