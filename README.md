# GroupDNA – WhatsApp Group Behaviour Analyzer

## Project Description

GroupDNA is a Python-based WhatsApp Group Behaviour Analyzer that studies group conversations and presents useful statistics about messaging patterns. It analyzes a WhatsApp chat export and generates a report showing group activity, individual messaging behaviour, frequently used words, response times, silent streaks, and personality archetypes.

The project uses Python fundamentals and NumPy to perform data analysis without relying on libraries such as pandas or matplotlib.

## Features

- **Chat Parser:** Reads the WhatsApp chat export and extracts timestamps, sender names, and messages.
- **Group Overview:** Displays total messages, participants, date range, and individual message counts.
- **Activity Analysis:** Identifies the busiest day and busiest hour.
- **Word Frequency:** Finds the most frequently used words in the group.
- **Activity Heatmap:** Uses a NumPy matrix to represent messaging activity by hour.
- **Response Time Analysis:** Calculates response times and identifies silent streaks.
- **Personality Archetypes:** Assigns behavioural archetypes based on messaging patterns.

## Technologies Used

- Python
- NumPy
- Google Colab
- GitHub

## Project Constraints

The project follows the restrictions mentioned in the assignment:

- No pandas.
- No matplotlib.
- No `collections.Counter`.
- No regular expressions (regex).
- Python fundamentals such as loops, dictionaries, lists, strings, and functions are used.
- NumPy is used for the activity heatmap.

## Dataset

The project uses the provided `hostel_bois.txt` dataset, a synthetic WhatsApp group conversation created for this assignment.

The dataset contains six participants and covers conversations from 1 April 2024 to 30 May 2024.

## How to Run the Project

1. Open the `.ipynb` notebook using Google Colab.
2. Upload the `hostel_bois.txt` dataset to the Colab session.
3. Make sure NumPy is available.
4. Select **Runtime → Run all**.
5. Wait for all cells to execute.
6. View the generated GroupDNA report.

## Project Structure

- `GroupDNA_YourName_YourRollNumber.ipynb` – Main project notebook.
- `hostel_bois.txt` – Dataset used for analysis.
- `README.md` – Project documentation.
- `screenshot.png` – Screenshot of the final output.

## Learning Outcomes

Through this project, I practised Python programming, file handling, string manipulation, dictionaries, lists, loops, functions, date and time operations, and NumPy. I also learned how to organize a data analysis project and present its results in a readable report.

## Acknowledgement

This project was completed as part of the GroupDNA Minor Project assignment by The Unlox Academy.
