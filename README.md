# BookBot

BookBot is a simple Python script that generates a report on the frequency of words and characters in a given text file. The report includes the total word count and the number of occurrences for each character in the text.

## Features

- **Word Count**: Counts the total number of words in the text.
- **Character Frequency**: Calculates how often each character appears in the text, sorted by frequency.

## Getting Started

### Prerequisites

Ensure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository or download the script:

   ```bash
   git clone https://github.com/your-username/bookbot.git
   
2. Navigate to the Project Directory

   
    Open your terminal or command prompt, then navigate to the project directory by running the following command:

  ```bash
  cd bookbot
  ```
## Usage

1. Replace the `book_path` variable in the `main()` function with the path to your text file. By default, it points to `books/frankenstein.txt`.

2. Run the script:

   ```bash
   python bookbot.py
    ```
The script will output a report in the terminal, displaying:

- The total number of words found in the document.
- The frequency of each alphabetic character, sorted from most to least frequent.

## Example Output

```plaintext
--- Begin report of books/frankenstein.txt
78552 words found in the document

The 'e' character was found 43005 times
The 't' character was found 32403 times
The 'a' character was found 31234 times

--- End report ---
```
## Customization

- **Text File**: You can analyze any text file by changing the `book_path` to point to the desired file.
- **Character Filtering**: The script currently filters non-alphabetic characters from the report. You can modify the script if you want to include these characters.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgments

Thanks to the developers of Python and the open-source community for their invaluable tools and resources.

Special thanks to Boot.dev Education for their guidance and resources that helped in the creation of this project.

