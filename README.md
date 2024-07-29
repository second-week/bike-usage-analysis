

# Bike Usage Analysis Case Study From Google Data Analysis Certificate Capstone Project

## Overview 

This is my attempt at the capstone case study from the [Google data
analyst certificate on
Coursera](https://www.coursera.org/professional-certificates/google-data-analytics).
In the case study (that's based on a fictional bike sharing company), I
focus on analyzing bike usage patterns for the company's user groups
(annual members and casual riders), using data from the first 4 months
of 2024. The data used in this case comes from the usage records of an
actual bike sharing company.

In the analysis, we (by we, I mean ChatGPT and I) focus on answering
questions related to trip frequencies and duration, usage patterns by
time of day and day of the week, and popular stations. These questions
play a part in helping us find differences in the usage patterns of the
two user groups.

The main goal behind me doing this case study is twofold:

Firstly, it's about learning to interact with real world data that's
often different from already cleaned data sets often found in other
places.

Secondly, and more importantly, it's about learning to think and ask
questions, prioritizing which areas of the analysis to focus on, as well
as how to have a structure or plan for approaching a case study.

This type of case study might be banal and easy to do, and yes, I do
know this. I'll very likely think the same in the future as I develop my
skills even more. But it plays a part in stretching my current
understanding. And that's worth a lot, even if it seems easy to do. But
it sure wasn't easy for me to do at my current skill level.

## Table of Contents

1.  [Overview](#overview)
2.  [Installation](#installation)
3.  [Usage](#usage)
4.  [Contributing](#contributing)

## Installation

To run the analysis, you'll need the following: - R (version 4.0.0 or
higher) - The `tidyverse` package

You can install the package using:

```{r}
install.packages("tidyverse")
```

Use this [link](https://divvy-tripdata.s3.amazonaws.com/index.html) to
download more recent data sets.

Here's a
[PDF](https://d3c33hcgiwev3.cloudfront.net/1XKhm37HS9iPXHfAIEBaRQ_ec9ad22caf394fec9608b08e556eb1f1_Case-Study-1_How-does-a-bike-shared-navigate-speedy-success_.pdf?Expires=1722384000&Signature=fmkIpEfRpYno7yebTYyBhsf9msabPMOpJ6hDYP0Cm1RFeoRdmKXG4lwYw2YYJPvCfvx0wVsv8k3O6iBBMLq3St6lCV0mbFeSwsQz7M3gOngkZqSJ4iXEYFbCG7r2OGZ2gmvaECs3dGPqyrOEo8aJPLb62scqoHVBBRDXIM-XEtE_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
concerning the project.

## Usage

1.  Clone the Repository:

```{bash}
    git clone https://github.com/second-week/bike-usage-analysis.git
    cd bike-usage-analysis
```

2.  Unzip the Data:

Place the data sets in the data directory.

3.  Run the Analysis:

Open the R script `bike_share3.R` and run the script.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request
for any improvements. I appreciate any feedback and corrections.




## License
This project is licensed under the MIT License.
