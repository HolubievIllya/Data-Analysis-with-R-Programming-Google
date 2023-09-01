#### Course challenge

Scenario 1, questions 1-7

As part of the data science team at Gourmet Analytics, you use data analytics to advise companies in the food industry. You clean, organize, and visualize data to arrive at insights that will benefit your clients. As a member of a collaborative team, sharing your analysis with others is an important part of your job.

Your current client is Chocolate and Tea, an up-and-coming chain of cafes.
The eatery combines an extensive menu of fine teas with chocolate bars from around the world. Their diverse selection includes everything from plantain milk chocolate, to tangerine white chocolate, to dark chocolate with pistachio and fig. The encyclopedic list of chocolate bars is the basis of Chocolate and Tea’s brand appeal. Chocolate bar sales are the main driver of revenue.

Chocolate and Tea aims to serve chocolate bars that are highly rated by professional critics. They also continually adjust the menu to make sure it reflects the global diversity of chocolate production. The management team regularly updates the chocolate bar list in order to align with the latest ratings and to ensure that the list contains bars from a variety of countries.

They’ve asked you to collect and analyze data on the latest chocolate ratings. In particular, they’d like to know which countries produce the highest-rated bars of super dark chocolate (a high percentage of cocoa). This data will help them create their next chocolate bar menu.

Your team has received a dataset that features the latest ratings for thousands of chocolates from around the world. Click here to access the dataset. Given the data and the nature of the work you will do for your client, your team agrees to use R for this project.

#### Q1. Your supervisor asks you to write a short summary of the benefits of using R for the project. Which of the following benefits would you include in your summary? Select all that apply.
- [x] Easily reproduce and share the analysis 
- [ ] Define a problem and ask the right questions
- [x] Create high-quality data visualizations 
- [x] Quickly process lots of data

#### Q2. You use the read_csv() function to import the data from the .csv file. Assume that the name of the data frame is flavors_df and the .csv file is in the working directory. What code chunk lets you create the data frame?
- [x] flavors_df <- read_csv("flavors_of_cacao.csv")
- [ ] flavors_df + read_csv("flavors_of_cacao.csv")
- [ ] read_csv("flavors_of_cacao.csv") <- flavors_df
- [ ] read_csv(flavors_df <- "flavors_of_cacao.csv")

#### Q3. Assume the name of your data frame is flavors_df. What code chunk lets you review the column names in the data frame?
- [x] colnames(flavors_df)
- [ ] arrange(flavors_df)
- [ ] col(flavors_df)
- [ ] rename(flavors_df)

#### Q4. Assume the first part of your code chunk is: flavors_df %>% What code chunk do you add to change the column name?
- [ ] rename(Company...Maker.if.known %<% Maker)
- [ ] rename(Maker %<% Company...Maker.if.known.)
- [x] rename(Maker = Company...Maker.if.known.)
- [ ] rename(Company...Maker.if.known. = Maker)

#### Q5. Assume the first part of your code is: trimmed_flavors_df <- flavors_df %>% Add the code chunk that lets you select the three variables.
Code: __select(Rating, Cocoa.Percent, Company)__
- [ ] Rogue
- [ ] Videri
- [x] A. Morin
- [ ] Soma


#### Q6. Next, you select the basic statistics that can help your team better understand the ratings system in your data. Assume the first part of your code is: trimmed_flavors_df %>% You want to use the summarize() and sd() functions to find the standard deviation of the rating for your data. Add the code chunk that lets you find the standard deviation for the variable Rating.
Code: __summarize(sd(Rating))__
- [ ] 0.3720475
- [ ] 0.2951794
- [x] 0.4780624
- [ ] 0.4458434

#### Q7. Assume the first part of your code is: best_trimmed_flavors_df <- trimmed_flavors_df %>% You want to apply the filter() function to the variables Cocoa.Percent and Rating. Add the code chunk that lets you filter the data frame for chocolate bars that contain at least 75% cocoa and have a rating of at least 3.9 points.
- [x] 75%
- [ ] 88%
- [ ] 80%
- [ ] 78%


#### Q8. Assume your first line of code is: ggplot(data = best_trimmed_flavors_df) + You want to use the geom_bar() function to create a bar chart. Add the code chunk that lets you create a bar chart with the variable Rating on the x-axis.
- [x] 2
- [ ] 5
- [ ] 6
- [ ] 3

#### Q9. Assume that you are working with the following code: ggplot(data = best_trimmed_flavors_df) + geom_bar(mapping = aes(x = Company.Location)) Add a code chunk to the second line of code to map the aesthetic fill to the variable Rating.
- [x] Canada and France
- [ ] Scotland and U.S.A
- [ ] Scotland and Canada
- [ ] Amsterdam and France

#### Q10. Assume your teammate shares the following code chunk: ggplot(data = best_trimmed_flavors_df) + geom_bar(mapping = aes(x = Cocoa.Percent)) + What code chunk do you add to the third line to create wrap around facets of the variable Cocoa.Percent?
- [ ] facet_wrap(Cocoa.Percent~)
- [x] facet_wrap(~Cocoa.Percent)
- [ ] facet(=Cocoa.Percent)
- [ ] facet_wrap(%>%Cocoa.Percent)

#### Q11. Assume the first part of your code chunk is: ggplot(data = trimmed_flavors_df) + geom_point(mapping = aes(x = Cocoa.Percent, y = Rating)) + What code chunk do you add to the third line to add the title Recommended Bars to your plot?
- [x] labs(title = “Recommended Bars”)
- [ ] labs(title = Recommended Bars)
- [ ] labs(“Recommended Bars”)
- [ ] labs(title + “Recommended Bars”)

#### Q12. Assume your first two lines of code are: ggplot(data = trimmed_flavors_df) + geom_point(mapping = aes(x = Cocoa.Percent, y = Rating)) + What code chunk do you add to the third line to save your plot as a jpeg file with chocolate as the file name?
- [x] ggsave(“chocolate.jpeg”)
- [ ] ggsave(“chocolate.png”)
- [ ] ggsave(“jpeg.chocolate”)
- [ ] ggsave(chocolate.jpeg)'

#### Q12. You decide to create an R Markdown notebook to document your work. What are your reasons for choosing an R Markdown notebook? Select all that apply.
- [x] It lets you record and share every step of your analysis
- [x] It allows users to run your code
- [x] It automatically creates a website to show your work
- [ ] It displays your data visualizations


