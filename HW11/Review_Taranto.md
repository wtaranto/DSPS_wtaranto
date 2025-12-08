***Reviews***

**TJ Tomaszewski**

**Improved Plot Review**

TJ was able to improve greatly on the ambiguity attribute which was the main issue with the original plot. Originally, the lack of transparency makes the cluster density unreadable at high point densities. The transparency added nearly resolves this issue, however, I think a slightly higher transparency would be a little better. The colors have been adjusted to be more colorblind friendly, but as a someone who's severely colorblind, the two rightmost columns are difficult to parse from one another. However, this isn't too much of an issue due to the data being spacially separated. For improvements, I would recommend overlaying box and whisker plots. With so many data points, the statistics can be difficult to approximate visually which box and whisker plots would help with.

**Bad Plot Review**

TJ's bad literature plot is pretty straightforwardly problamatic. First, it is a pie chart which are inappropriate for representing time, a quantity which should scale linearly with intensity not quadratically. Second, the phase A and B slices of the plot use colors indistinguishable to me (colorblind). There is also ambiguity in the length of time for phases. This would be helped by extra labels, however this would further clutter the plot. The plot is likely irrecoverable without major reinvention. I would use a horizontal stacked bar plot as this is natural for sequential temporal durations.

**Alex Bruce**

**Improved Plot Review**

Alex chose to remake their plots of confusion matrices and replaced the colorscheme from "bones" to "blues". I do agree with Alex that the plot's readability benefits from the change in color. There are several things which I would still improve. First, the plot does distort the number of false negatives by starting the color bar above 0 value. This can distort the color to be near white which would signify perfect performance which is not actually true. This same issue is present in the max of the color bar which should be 1 for the normalized confusion matrices.

**Bad Plot Review**

This plot doesn't really utilize the small multiples paradigm very well. The main reason is that it conveys too much information. Although it has a high data to ink ratio, this is mainly offset by the lack of insight the data provides. I would only include a plot like this if each (or trends) of the small plots are specifically mentioned in the paper or possibly in an appendix/supplement. I would try to solve the problems with this plot by first just cutting any of the plots which aren't specifically mentioned in the paper. If no specific plots are mentioned but rather a trend is mentioned. Then, I would plot a satistic representative of the trend vs wavelength as a line graph. In fact, multiple statistics could be plotted on the same axes if two statistics need to be related.