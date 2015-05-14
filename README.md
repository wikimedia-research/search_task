# S&D Data Analyst task

## The dataset
Included is a dataset of data from the logging of Wikimedia search requests - *search\_dataset.tsv*. It is tab-separated, and contains 1m rows, with the columns:

*`timestamp`: the timestamp of the request.
*`event_action` the type of action the requests represent. Options are `session-start` (the start of a search session),
`impression-results` (the display of a results page) and `click-result` (a user clicking on a particular result).
*`event_platformVersion`: the version of the site that the user was using. Options are `stable`, `alpha` and `beta`.
*`event_timeToDisplayResults`: the time taken to display a results page. This will be `NA` in the case of actions that did not
result in the display of a results page.

## The task

Using this dataset, eke out any insights you can about the users of search, the way they use the system, and the way the system responds to them. Present these insights through text and/or visualisations in a way understandable by non-scientific consumers and reproducible by other analysts or engineers. Obviously this is a very wide task; don't spend more than a couple of hours on it, and use whichever tools you want.

Once you've completed the task to your satisfaction, submit it through the Greenhouse tools that manage your application.
