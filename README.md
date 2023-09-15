# UCEPanalysis
Multinomial logistic regression analysis of the Utah Colleges Exit Poll

The Utah Colleges Exit Poll is a survey conducted in Utah and contains demographic information of Utah voters. In the academic literature on partisanship, party identification is often categorized as strong Republican, weak Republican, independent, weak Democrat, and strong Democrat. Dr. David Magleby had a theory that this categorization was insufficient. He hypothesized that there were voters who identified as independents but still were partial toward one party, and he supposed that these people would be more demographically similar and vote more similarly to those who weakly identify with the party to which they are partial than to impartial independents.

I performed this multinomial logistic regression analysis as a research assistant, the results of which support Dr. Magleby's hypothesis. I include in this repository the code I used to clean and bind the data into a cumulative file, and the code I used to perform the analysis. The UCEP data can be acquired from the Harvard Database. The data was quite messy because the surveys changed from year to year, so it took time to figure out what needed to be done to clean and bind the data. Because I learned about the data in small steps, the code for cleaning is not as streamlined as it could be. Regardless, it functions as it should.
