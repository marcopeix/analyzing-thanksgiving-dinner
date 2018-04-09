# Analyzing Thanksgiving Dinner

This project analyzes data from a survey conducted in 2015. It contains 1058 responses about what Americans eat for Thanksgiving dinner. Each respondent waht asked questions about what they typically eat for Thanksgiving, along with questions about their gender, age, income, and location. The dataset can be found [here](https://github.com/fivethirtyeight/data/tree/master/thanksgiving-2015).

The dataset has 65 columns and 1058 rows. The columns are the questions and their values are string responses to the questions. Most of the columns are categorical as most of the questions were multiple choice.

Here is a quick description of the most important columns from the dataset:

* `RespondentID` - A unique ID of the respondent
* `Do you celebrate Thanksgiving?` - A `Yes` / `No` answer to the question
* `How would you describe where you live?` - Responses can be:
    * `Suburban`
    * `Urban`
    * `Rural`
* `Age` - Reponses are one of several categories, such as `18-29` or `30-44`
* `How much total combined money did all members of your HOUSEHOLD earn last year?` - Responses are one of several categories, such as `$75,000 to $99,999`

**Objective**: The objective is to find regional and income-based patterns in what Americans eat for Thanksgiving.

**Techniques used**:
* Analysis using pandas
* Pivot tables
* Working with missing data
