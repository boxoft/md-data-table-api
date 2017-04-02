# md-data-table-api
Clone the RESTful API Using Node.js for the Live Demo of the "Material Design Data Table" at http://danielnagy.me/md-data-table/.

## Prepare the Data

1. Get all the data from https://infinite-earth-4803.herokuapp.com/nutrition/desserts/.

2. Save the data as "desserts.json".

3. Remove the characters before "[" and the last character "}".

4. Make sure the MongoDB service has been running.

5. Run the following command:

    `
    $ mongoimport --db nutrition --collection desserts --file desserts.json --jsonArray
    `

