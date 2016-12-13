PyData Atlanta Lightning Talk (December 2016)
=============================================

This repository contains a Jupyter Notebook and slides for a Lightning Talk given at the PyData Atlanta meeting on December 14, 2016.


Lifelines
---------

[Lifelines](http://lifelines.readthedocs.io) is a Python library that
dedicates itself to survival analysis. It calculates survival and hazard
curves of observational data that contains times to an event of interest
(e.g. birth, death, marriage, divorce, retirement, etc). It also
performs regression analysis to describe the relationship of a factor of
interest to the time to event.

This talk provides an overview of this library, with Soccermetrics'
research on the Major League Soccer draft serving as a use case.


MLS Draft Data
--------------

The `mls_draft_data.csv` file contains data used to illustrate the
capabilities of the `lifelines` package. A description of the fields is
listed below:

| Field       | Type    | Description                                           |
|:------------|:--------|:------------------------------------------------------|
| GA          | boolean | Player participated in Generation Adidas program      |
| draft       | string  | Type of MLS player draft                              |
| draft_pick  | float   | Normalized draft position, 0=first pick, 1=final pick |
| draft_round | integer | Round of draft in which player selected               |
| inactive    | boolean | Is player not active in 2016 MLS season?              |
| matches     | integer | Total league match appearances by player              |
| player      | string  | Name of drafted player                                |
| year        | integer | Draft year                                            |

Sources: Major League Soccer, MLS Players Union, Wikipedia