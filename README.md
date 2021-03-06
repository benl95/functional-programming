# functional programming

## What does this project do?

In this project I'm converting the answers that are given to the question: 'What is your favorite day of the week'. The answers are given in numbers and I'm
converting these numbers to actual days. For the survey participants that didn't answer this question a 'No input' answer will be given.

## Which features have I used?

Right now I'm using a 'hack' given by Robert and Laurens I retrieve the data using a JSON file and store that JSON into a function to return the data.
Eventually I will use the map and filter object to search through the data. I will be searching through the data using a variable where the 'search action' will
be stored. The data will eventually be pushed into an array using a for loop and a push method.

To convert the values to actual days I'm using a switch case in where the cases are tested and converted.

## Which data am I using?

In the first week we will be experiment with functional patterns using the CMD students dataset. I've chose to clean up the favorite day of the week column.

## Installation guide

Navigate to the desired directory in your terminal:

`cd desktop`

Once you've reached the desired directory paste the following code in your terminal:

`git clone https://github.com/benl95/functional-programming.git`

You can now open index.html and open the console to check the array in which the survey answers are stored.

## Sources

People that helped:

-   Jonah Meijers and Vincent van Leeuwen (switch case)
-   Laurens Aarnoudse and Robert Spier (Importing JSON data and searching through the data)

-   [switch - Javascript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)
-   [#10 Javascript Tutorial | switch case](https://www.youtube.com/watch?v=OWQUBfWaxBw&t=94s&ab_channel=Telusko)

# RDW Dataset

## Research question

How sustainable is the population of the Netherlands driving?

### Subquestions

-   What is the composition of the dutch vehicle fleet?
-   How sustainable are the fossil fuel vehicles in the Netherlands?
-   What is the most common car driven in the Netherlands and is this car sustainable?

## Which dataset and variables am I going to use?

-   Dataset: [Open Data RDW: Gekentekende_voertuigen_brandstof](https://opendata.rdw.nl/Voertuigen/Open-Data-RDW-Gekentekende_voertuigen_brandstof/8ys7-d773)
-   Variables: Fuel used, emission class, vehicle type, vehicle brand, trade name vehicle, CO2 emission combined.

## Assumptions

How sustainable are the population of the Netherlands driving?

-   My assumption is that 2/3 of the registered vehicles in the Netherlands still run on fossil fuel.

What is the compositon of the dutch fleet?

-   My assumption is that benzine is the most used fuel among the vehicles in the Netherlands

How sustainable are the fossil fuel vehicles in The Netherlands?

-   My assumption is that the majority of the vehicles in the Netherlands aren't sustainable.

What is the most common car in the Netherlands and is this car sustainable?

-   My assumption is that the most common car in the Netherlands is a Volkswagen Polo. The majority of these cars still run on fossil fuel so they aren't
    sustainable.

## Sketches

[Sketches](https://github.com/benl95/functional-programming/wiki/6.-RDW-Concept)

## License

[MIT](https://choosealicense.com/licenses/mit/)
