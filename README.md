# Assignment-2: U.S. Population Graph

This repository hosts an assignment showcasing the census population of the United States over the last decade. The information is presented through an aesthetically formatted graph.

## Styling Section

![Styling Screenshot](https://github.com/arjoseven/Assignment-2/assets/158103825/7a7c692e-1cad-4254-b592-2bd261373593)

The provided CSS code defines styling rules for an HTML table. It sets a 2px solid black border for the table and its cells (`th` and `td`). Additionally, it establishes a padding of 8px and centers the text within both header cells (`th`) and data cells (`td`). These styles contribute to a visually organized and structured presentation of U.S. population data in the associated HTML table.

## HTML Table Structure

![Table Screenshot](https://github.com/arjoseven/Assignment-2/assets/158103825/a28c6bcc-a27c-4991-8711-9bcc82b0ec33)

This HTML code represents the structure of an HTML table designed to display U.S. population data. The table includes a title row with `colspan="2"` for "U.S. Population," followed by a header row containing "Year" and "Population" column headers. The table body is initially empty, awaiting dynamic population through JavaScript.

## API Data Retrieval

![API Code Screenshot](https://github.com/arjoseven/Assignment-2/assets/158103825/85fdf581-0743-4d3b-a61e-a24e3ba287bb)

The included JavaScript code, embedded in the HTML document, asynchronously fetches U.S. population data from the datausa.io API. It sorts the retrieved information by year and dynamically populates the HTML table with formatted year and population values. The script is set to execute when the webpage loads, providing an automatically updated display of census data. Error handling is implemented to log any issues during the data-fetching process.
