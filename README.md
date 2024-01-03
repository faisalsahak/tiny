readme_content = """
# Folder Report Generator

Folder Report Generator is a Python script that generates a directory tree and saves it as a text file and PDF. It also provides information about the number of JPEG, DNG, and other files in each folder.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/folder-report-generator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd folder-report-generator
    ```

3. Install dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the script with the following command:

```bash
python generate_folder_report.py -f /path/to/your/folder -s [optional: show files] -o [optional: output directory]


Options:
-f, --folder: Specify the folder path for generating the directory tree.
-s, --show-files: Include file names in the directory tree (optional, default is False).
-o, --outputdir: Directory to save the output (optional).
Generate a directory tree for the folder /path/to/your/folder without showing file names:

Examples:
Generate a directory tree for the folder /path/to/your/folder without showing file names:
python generate_folder_report.py -f /path/to/your/folder

Generate a directory tree for the folder /path/to/your/folder, including file names, and save the output to a specific directory:
python generate_folder_report.py -f /path/to/your/folder -s -o /path/to/output/directory

Help
For help on using the script, run:
python generate_folder_report.py -h
This will display the available options and usage information.

Output
The script generates two output files:

folder_report.txt: Text file containing the directory tree.
folder_report.pdf: PDF file containing the visual representation of the directory tree.
Output files are saved to the specified output directory or the current working directory if not provided.

Feel free to contribute or report issues!
"""

with open("README.md", "w") as readme_file:
readme_file.write(readme_content)

print("README.md file created.")
