# LeetCode Notion Table Template and Integration

This repository contains a template for recording LeetCode problems and a notebook that automates the process of inserting an entry into a Notion table based on a LeetCode link. The notebook extracts information such as problem title, number, link, difficulty, and problem description from the LeetCode website and inserts it into the specified Notion table.

## LeetCode Template
The template I have created and use is available [here](https://glacier-bell-9e7.notion.site/1ea48ceede1b4482b204f8053b036feb?v=e62ae37861394f3fbafbae51612eaf2d&pvs=4). Feel free to use it. If you prefer to use your own table, make sure the column names (Problem, Name, Link, Difficulty) are consistent with mine for the integration. If not, you may need to modify the script accordingly.

## Prerequisites
If you are using Google Colab (which I recommend), there are no prerequisites other than opening this [Google Colab notebook](https://colab.research.google.com/drive/1LSwHkBYbvZmieAkK7NABZdZ4iShFgpQR?usp=sharing), making a copy, and skipping to the "Setup" section.

If you prefer to run the notebook in Jupyter Notebook/VS code, make sure you have the following prerequisites installed:

- Python 3.6 or above
- Required Python libraries: requests, beautifulsoup4, pandas, notion (You can install them by running `pip3 install -r requirements.txt`)

## Setup
1. Follow the tutorial from the [official Notion API documentation](https://developers.notion.com/docs/create-a-notion-integration) from step 1 to step 3.

2. Make a copy of your **Notion integration token** and **database ID** of your table (copy the link of the table or just open it in the browser to view the link).

3. Open the `leetcode_to_notion.ipynb` notebook using Jupyter Notebook.

4. In the notebook, provide your Notion API token and database URL.

5. Run All, and make sure to provide the LeetCode link when prompted.

6. The notebook will extract the necessary information from the LeetCode page and insert it into the specified Notion table.


Please let me know if you have any further questions or need additional assistance.
