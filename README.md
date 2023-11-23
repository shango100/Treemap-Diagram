# D3.js Tree Map `Project`

This project uses D3.js to create an interactive tree map visualization representing Kickstarter pledges data. The tree map is designed to fulfill the following user stories:

1. **Title and Description:**
   - The tree map has a title with the corresponding id="title".
   - The tree map has a description with the corresponding id="description".
2. **Tree Map Tiles:**
   - The tree map has rect elements with a corresponding class="tile" that represent the data.
   - There are at least 2 different fill colors used for the tiles.
3. **Tile Properties:**
   - Each tile has the properties data-name, data-category, and data-value containing their corresponding name, category, and value.
4. **Tile Area Correspondence:**
   - The area of each tile corresponds to the data-value amount: tiles with a larger data-value have a bigger area.
5. **Legend:**
   - The tree map has a legend with the corresponding id="legend".
   - The legend has rect elements with a corresponding class="legend-item".
6. **Legend Colors:**
   - The rect elements in the legend use at least 2 different fill colors.
7. **Tooltip:**
   - Users can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
8. **Tooltip Data:**
   - The tooltip has a data-value property that corresponds to the data-value of the active area.

## Datasets

You can use any of the following datasets for this project:

- [Kickstarter Pledges](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/kickstarter-funding-data.json)
- [Movie Sales](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/movie-data.json)
- [Video Game Sales](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/video-game-sales-data.json)

## Getting Started

1. Clone or download the project repository.
2. Open the `index.html` file in a modern web browser.
3. Explore the interactive tree map visualization with tiles, legend, and tooltips.

## Technologies Used

- HTML
- CSS
- JavaScript
- D3.js (Data-Driven Documents)

## Author

shango100

## Acknowledgments

- This project is part of the [freeCodeCamp Data Visualization Certification](https://www.freecodecamp.org/learn/data-visualization/data-visualization-projects).
