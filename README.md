```markdown
# Names Frequency Simulation

This repository contains an R-based simulation that explores the distribution of female names in the Gospels and Acts. The goal is to statistically test how name distributions change \n under blended conditions, using k-means clustering for adaptive binning and p-value analysis. This work was developed in collaboration with Jason Wilson (Department of Math and Computer \nScience, Biola University) and builds on prior studies published in the *Journal for the Study of the Historical Jesus*.



````

## How to Run

Before running: install all necessary dependencies/libraries in R.

1. Load Required Data  
   Load the RData file into your R environment:
   ```r
   load("data/Gospel-Acts-Female02.RData")
````

2. Run the Script
   Open `names_simulation.R` and run all cells from top to bottom after loading the data.

3. Adjust Simulation Repetitions
   To change the number of simulation repetitions, go to line 901 and modify the loop value.

4. Using Pre-Generated Results
   If you'd like to explore the result of 1000 simulations, load:

   ```r
   load("results/final_1000.RData")
   ```

   Then, run from line 962 to the end of `names_simulation.R` to calculate:

   * p-values
   * Kendall's Tau
   * Goodman-Kruskal Gamma
   * A graph of p-value vs. blend level

## Reference

This simulation builds upon:
"The Historical Jesus and the Names of Women"
Published in the *Journal for the Study of the Historical Jesus*, Vol. 22 (2024)
[https://brill.com/view/journals/jshj/22/2/article-p184\_005.xml](https://brill.com/view/journals/jshj/22/2/article-p184_005.xml)

This version includes significant improvements developed with Jason Wilson.

## Author

Abel T. Yilma
Los Angeles, CA
Email: [abel.tewodros14@gmail.com](mailto:abel.tewodros14@gmail.com)
LinkedIn: [https://linkedin.com/in/abel-t-yilma-5841311aa](https://linkedin.com/in/abel-t-yilma-5841311aa)


