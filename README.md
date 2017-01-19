# Media Platform & News Trust Survey — January 2017

This repository contains data and analysis supporting the BuzzFeed News article, "[Most American Adults Get News From Facebook — But They Don’t Really Trust It, A New Survey Says](https://www.buzzfeed.com/craigsilverman/people-be-reading-but-not-trusting-news-on-facebook)," published January 19, 2017.

## Data

This repository contains the following data from the survey:

- Ipsos's [topline calculations](data/ipsos-toplines.pdf?raw=true), as a PDF.

- Ipsos's [spreadsheet of cross-tabulations](data/ipsos-crosstabs.xlsx?raw=true).

- The [raw, response-level data](data/survey-responses.csv).

## Additional analysis

BuzzFeed News performed additional analysis, to calculate trust __among respondents who said they had gotten news from a given platform__. You can find the Python code for the analysis [in this notebook](notebooks/platform-trust-additional-analysis.ipynb), which produces these numbers:

| Platform                      | % Mostly/Always Trust* |
|-------------------------------|------------------------|
| Print newspapers              | 74%                    |
| Newspapers’ websites          | 69%                    |
| News radio                    | 68%                    |
| Broadcast TV news             | 66%                    |
| Cable news                    | 65%                    |
| Talk radio                    | 57%                    |
| Online-only news publications | 55%                    |
| YouTube                       | 53%                    |
| Twitter                       | 49%                    |
| Snapchat                      | 47%                    |
| Facebook                      | 27%                    |
| Social media (generally)      | 25%                    |

\* "All of the time" or "Most of the time"

## Questions / Comments?

Please contact Jeremy Singer-Vine at jeremy.singer-vine@buzzfeed.com.

Looking for more from BuzzFeed News? [Click here for a list of our open-sourced projects, data, and code](https://github.com/BuzzFeedNews/everything).

