## Minilab 08

This minilab will help you practice with `gawk`.

1. Run `wget https://raw.githubusercontent.com/fivethirtyeight/data/master/murder_2016/murder_2015_final.csv` to download a dataset.
2. Use an associative array in gawk to keep track of
   the overall change for each state
   (`change` is one of the columns in the data set),
   but there are some states with multiple cities.
3. Use the `END` block to print out the resulting overall
   computed change for each state.
