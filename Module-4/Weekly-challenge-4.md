#### Weekly challenge 4

#### Q1. Which of the following tasks can you complete with ggplot2 features? Select all that apply. 
- [x] Customize the visual features of a plot
- [x] Add labels and annotations to a plot
- [x] Create many different types of plots
- [ ] Automatically clean data before creating a plot

#### Q2. In ggplot2, what symbol do you use to add layers to your plot?
- [ ] The ampersand symbol (&)
- [ ] The equals sign (=)
- [ ] The pipe operator (%>%)
- [x] The plus sign (+)

#### Q3. A data analyst creates a plot using the following code chunk: ggplot(data = penguins) + geom_jitter(mapping = aes(x = flipper_length_mm, y = body_mass_g)) Which of the following represents a function in the code chunk? Select all that apply.
- [x] The geom_point function
- [ ] The data function 
- [x] The aes function
- [x] The ggplot function

#### Q4. Which code snippet will make all of the bars in the plot purple?
- [ ] ggplot(data = buildings) + geom_bar(mapping = aes(x = construction_year, color=”purple”))
- [ ] ggplot(data = buildings) + geom_bar(mapping = aes(x = construction_year, color=height))
- [ ] ggplot(data = buildings) + geom_bar(mapping = aes(x = construction_year)) + color(“purple”)
- [x] ggplot(data = buildings) + geom_bar(mapping = aes(x = construction_year), color=”purple”)

#### Q5. A data analyst is working with the penguins data. The analyst creates a scatterplot with the following code: ggplot(data=penguins)+geom_point(mapping=aes(x=flipper_length_mm, y=body_mass_g, alphar=species)) What does the alpha aesthetic do to the appereance of the points on the plot?
- [ ] Makes the points on the plot smaller
- [ ] Makes the points on the plot larger 
- [ ] Makes the points on the plot more colorful 
- [x] Makes some points on the plot more transparent

#### Q6. You are working with the penguins dataset. You create a scatterplot with the following code: ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g)) You want to highlight the different penguin species on your plot. Add a code chunk to the second line of code to map the aesthetic shape to the variable species.
code: <b>geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species))</b>
#### Which penguin species does visualization display?
- [x] Adelie, Chinstrap, Gentoo
- [ ] Adelie, Emperor, Gentoo
- [ ] Adelie, Chinstrap, Macaroni
- [ ] Chinstrap, Emperor, Gentoo

#### Q7. Which aesthetic of the geom_smooth function can be used to change the style of the line?
- [ ] line
- [ ] linestyle
- [x] linetype
- [ ] linelook

#### Q8. Which of the following statements best describes a facet in ggplot?
- [ ] Facets are the text used in and around plots.
- [ ] Facets are the visual characteristics of geometry objects.
- [x] Facets are subplots that display data for each value of a variable.
- [ ] Facets are the ggplot terminology for a chart axis.

#### Q9. What argument of the label() function can a data analyst use to add text outside of the grid area of a plot?
- [x] note
- [ ] title
- [ ] text
- [ ] annotate

#### Q10. By default, what plot does the ggsve() function export?
- [ ] The plot define the plots.config file
- [x] The last displayed plot
- [ ] The plot defined in the Plots Tab of R Studio
- [ ] The first plot displayed
