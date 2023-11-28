# belly-button-challenge

Overview of the Project
The primary objective of this project is to develop a dynamic web-based representation of the Belly Button Biodiversity dataset, accessible at the specified URL: Belly Button Biodiversity Dataset. The visualization encompasses the following functionalities:

1. Horizontal Bar Chart: Presents the top 10 Operational Taxonomic Units (OTUs) discovered in a chosen individual. It utilizes sample values as bar heights, OTU IDs as bar labels, and OTU labels as hover text for additional details.

2. Bubble Chart: Illustrates the entire sample dataset. It employs OTU IDs for the x-axis, sample values for the y-axis, sample values for marker size, OTU IDs for marker colors, and OTU labels for text values.

3. Sample Metadata Display: Exhibits demographic information for the selected individual, showcasing each key-value pair from the metadata JSON object.

4. Dropdown Menu: Enables the selection of different individuals for exploration. All visualizations automatically update when a new sample is chosen.

Getting Started
To navigate the Belly Button Biodiversity Dashboard, follow these steps:

1. Clone or download this repository to your local machine.

2. Open your terminal and navigate to the project directory using the cd command, for example:

```
cd path/to/belly-button-challenge
```

3. Once inside the project folder, initiate a Python HTTP server with the following command:

```
python -m http.server
```

4. After starting the server, open your web browser (preferably Google Chrome) and enter the provided URL in the address bar.

5. Select an individual from the dropdown menu to explore their microbial data and demographic information.

Technologies Employed
This project leverages the following technologies and libraries:

- D3.js: Utilized for reading the dataset and crafting interactive visualizations.
- HTML and CSS: Employed for constructing the webpage layout and styling.
- JavaScript: Used for managing data manipulation, dynamic updates, and interactivity.
- JSON: The dataset is supplied in JSON format for convenient access and utilization.
