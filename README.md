# bandcoapp
This is the repository used to publish my code for assignment 2 of the CSC422 Data Structures and Algorithms course.

This is a Java application that coordinates bands for different venues, with a specialization in 90s bands. The program allows you to manage and search for bands based on their names and the number of singles they have. This project was created as part of the CSC 420 assignment.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [File Format](#file-format)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with the Band Coordinator App, follow these instructions:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/BandCoordinatorApp.git

Open the project in your preferred Java development environment (e.g., IntelliJ IDEA, Eclipse).

Compile and run the BandCoordinator class to start the program.

Usage
The Band Coordinator App offers the following features:

Search for a band by name.
Search for a band based on the closest number of singles to a specified count.
Display the details of the found band, including their name and the number of singles they have.
Simply follow the on-screen instructions when running the program.

Features
Loading band information from a file.
Searching for bands by name using a binary search algorithm.
Searching for bands by the closest number of singles.
Sorting the band data by name using a bubble sort algorithm.
Implementation of the BandInfo class for storing band information.
Input validation and user-friendly prompts.
File Format
The program expects a text file in the following format for loading band information:
The Nixons|9
FAT|1
Black Lab|2
Our Lady Peace|28
Creed|18
Monster Magnet|26
Live|28
Sponge|18
Bush|29
Hootie and the Blowfish|17

Each line should contain the band name and the number of singles, separated by a pipe (|) delimiter.

Contributing
Contributions are welcome! If you have suggestions or improvements for this project, please open an issue or submit a pull request. Make sure to follow the project's coding standards and maintain clear commit messages.

License
This project is licensed under the MIT License.
