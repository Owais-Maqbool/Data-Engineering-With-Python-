# Data-Engineering-With-Python-
This repsitory contains "XML-to-CSV conversion scripts for 'sample.xml' and 'complex.xml'. Pandas DataFrames capture key attributes, saved as 'sample.csv' and 'complex_output.csv.' Facilitates structured data integration into analysis workflows. #Python #DataProcessing #XMLtoCSV"
Description of the tasks performed in the provided Python script:

1. **Load XML Data:**
   - The script starts by loading the XML data from the specified file (`complex.xml`) using the `xml.etree.ElementTree` module.

2. **Extract Data and Create List of Dictionaries:**
   - The script then iterates through the XML elements to extract relevant information about products, catalog items, sizes, and color swatches.
   - For each product and catalog item, it creates a dictionary containing attributes such as description, product image, gender, item number, price, size, and color swatch.

3. **Convert to Pandas DataFrame:**
   - The extracted data is then converted into a list of dictionaries, where each dictionary represents a row of the future DataFrame.

4. **Pandas DataFrame Creation:**
   - The list of dictionaries is used to create a Pandas DataFrame (`df`), which is a tabular representation of the structured data.

5. **Save DataFrame to CSV:**
   - The Pandas DataFrame is saved to a CSV file (`complex_output.csv`). This file contains the structured data in a format suitable for analysis or further processing.

6. **Print Confirmation Message:**
   - Finally, the script prints a message confirming the successful saving of the DataFrame to the CSV file, along with the file path.
