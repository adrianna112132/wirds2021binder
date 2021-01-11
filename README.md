# wirds2021binder

Aby repozytorium stało się obrazem, ktory będzie zaqierał R wraz z określonymi pakietami należy utworzyc 2pliki:
+ `runtime.txt` - plik powinien zawierac wersje R wraz z datą np. 'r-,6-YYYY-MM-DD' lub 'r-YYYY-MM-DD'
+ i `install.R` -skrypt w R zawierający liste pakietów do instalacji no. install.packages('tidyverse')
