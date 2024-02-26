# Flipkart Review Scraper

This is a web scraper built in Python using Flask that allows users to retrieve review data for products on Flipkart.com. The application provides a graphical and easy-to-use interface for users to input their search query and view the ratings and reviews for the corresponding product.

## Features

- **Graphical User Interface**: The application provides a user-friendly interface built using HTML and CSS.
- **Search Functionality**: Users can input their search query to find products on Flipkart.com.
- **MongoDB Connection in backend**:Connected to database.
- **Review Scraping**: The application scrapes review data including ratings and reviews for the searched product.
- **Display**: The retrieved review data is displayed to the user in an easy-to-understand format.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/kindo-tk/Web_Scrapper.git
```

2. Navigate to the project directory:

```bash
cd .\Web_Scrapper\
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```
## Note
- modify the MongoDB server details / comment out that part for smooth functioning of the program
## Usage

1. Start the Flask server:

```bash
python app.py
```

2. Open your web browser and go to http://localhost:5000.

3. Enter your search query in the provided input field and click the "Search" button.

4. View the retrieved review data including ratings and reviews for the product.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

<img src="https://github.com/kindo-tk/images/blob/main/Web_Scrapper/searchpage.png" >
<img src="https://github.com/kindo-tk/images/blob/main/Web_Scrapper/reviewpage.png" >
