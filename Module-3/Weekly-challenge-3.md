#### Weekly challenge 3

#### Q1. What is an advantage of using data frames instead of tibbles?
- [ ] Data frames store never change variable names
- [ ] Data frames allow you to use column names
- [ ] Data frames make printing easier
- [x] Data frames allow you to create row names

#### Q2. A data analyst is checking a script for one of their peers. They want to learn more about a specific data frame. What function(s) will allow them to see a subset of data values in the data frame? Sekect all that apply.
- [ ] colnames()
- [x] str()
- [ ] library()
- [x] head()

#### Q3. You are working with the ToothGrowth dataset. You want to use the glimpse() function to get a quick summary of the dataset. Write the code chunk that will give you this summary.
code: <b>glimpse(ToothGrowth)<b/>
#### How many different data types are used for the column data types?
- [x] 2
- [ ] 3
- [ ] 60
- [ ] 1

#### Q4. You have a data frame named employees with a column named Last_NAME. What will the name of the employees column be in the results of the function rename_with(employees, tolower)?
- [ ] Last_NAME
- [x] last_name
- [ ] last_nAME
- [ ] lAST_nAME

#### Q5. A data analyst is working with the penguins dataset in R. What code chunk will allow them to sort the penguins data by the variable bill_length_mm?
- [x] arrange(penguins, bill_length_mm)
- [ ] arrange(bill_length_mm, penguins)
- [ ] arrange(=bill_length_mm)
- [ ] arrange(penguins)

#### Q6. You are working with the penguins dataset. You want to use the summarize() and mean() functions to find the mean value for the variable bill_mass_g. At this point, the following code has already been written in your script:
code: <b>summarize(body_mass_g_m = mean(body_mass_g))<b/>
#### What is the mean body mass in g for the Adelie species?
- [ ] 5092.437
- [x] 3706.164
- [ ] 4207.433
- [ ] 3733.088

#### Q7. A data analyst is working with a data frame called zoo_records. They want to create a new column named is_large_animal that signifies if an animal has a weight of more than 199 kilograms. What code chunk lets the analyst create the is_large_animal column?
- [ ] zoo_records %>% mutate(weight > 199 = is_large_animal)
- [ ] zoo_records %>% mutate(weight > 199 <- is_large_animal)
- [ ] zoo_records %>% mutate(is_large_animal == weight > 199)
- [x] zoo_records %>% mutate(is_large_animal = weight > 199)

#### Q8. A data analyst is working with a data frame named weather. It has separate columns for temperatures (temp) and measurment units (unit). The analyst wants to combine into a single column called display_temp, with the temperature and unit separated by the string "Degrees". What code chunk lets the analyst create the display_temp column?
- [ ] weather %>% unite(" Degrees ", weather, temp, "display_temp")
- [ ] unite(" Degrees ", weather, temp, "display_temp")
- [x] unite(weather, "display_temp", temp, unit, sep = " Degrees ")
- [ ] weather %>% unite(weather, "display_temp", weather, temp, delim = " Degrees ")

#### Q9. A data analyst writes the following code chunk to return a statistical summary of their dataset: quartet %>% group_by(set) %>% summarize(mean(x), sd(x), mean(y), sd(y), cor(x, y))
- [ ] mean(x)
- [ ] sd(x)
- [x] mean(y)
- [ ] cor(x, y)

#### Q10. A data analyst wants to check the average difference between the actual and predicted values of a model. What single function can they use to calculate this statistic?
- [x] bias()
- [ ] mean()
- [ ] cor()
- [ ] sd()
