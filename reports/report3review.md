# Report 3 Review
### Data Science
##### Review by Joey Maalouf
##### Report by Radmer van der Heyde

[This report](https://github.com/rvanderheyde/ThinkStats2/blob/master/reports/report3.md) aims to explore the driving cause behind a news story's word count, which the author believes is representative of the media's interest in the topic. He uses data collected by the Pew Research Center, in their [2012 News Coverage Index dataset](http://www.journalism.org/datasets/2012-news-coverage-index-data-set/).

There are placeholders in the report for eight figures, but the images themselves are nowhere to be found; this somewhat detracts from the report, but the descriptive paragraphs immediately after each one do a decent enough job of explaining what the figures would show.

For the actual analysis, the author seems to focus on finding potential Weibull distribution parameters and comparing them across different predicting variables (topic, source, etc.) to see which one best matches the actual distribution. It's particularly non-specific, however; sentences like `The distance between contours is small meaning that it is highly likely that the value of the parameters are contained in that spot on the chart` hint at the existence of some way to mathematically quantify this likelihood, but all the readers get is that sort of vague description. Additionally, I have to question if this is really the best method to compare the predictive ability of different variables, compared to, say, looking at the normalized coefficients (or just the output accuracy, if testing one feature at a time) of a regression model.

Overall, we don't really get a satisfying answer to the motivating question. The later paragraphs talk about how the source and topic don't seem to have much predictive power for an article's word count, but we never find out what actually does.
