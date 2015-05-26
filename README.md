# S&D Data Analyst task

## Task
The first task is a sunoke test of data extraction (nothing fancy!) and visualisation.

## The dataset
Included is a dataset of data from the logging of Wikimedia search requests - *search\_dataset.tsv*. It is tab-separated, and contains 1m rows, with the columns:

* `timestamp`: the timestamp of the request.
* `event_action` the type of action the requests represent. Options are `start` (the start of a search session),
`results` (the display of a results page) and `click` (a user clicking on a particular result).
* `event_timeToDisplayResults`: the time taken to display a results page. This will be `NA` in the case of actions that did not
result in the display of a results page.

## The task

Using this dataset, eke out any insights you can about the users of search, the way they use the system, and the way the system responds to them, looking particularly at the seasonality and temporal patterns of user behaviour. Present these insights through text and/or visualisations in a way understandable by non-scientific consumers and reproducible by other analysts or engineers. Obviously this is a very wide task; don't spend more than a couple of hours on it, and use whichever tools you want.

The output could be visualisations, presentations, anything - this is more about the way you think and work than it is the format :).

Once you've completed the task to your satisfaction, submit the output and whatever code you used to produce it through the Greenhouse tools that manage your application. Do *not* submit it through a GitHub pull request or similar.
