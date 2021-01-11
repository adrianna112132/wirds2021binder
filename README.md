# wirds2021binder

Aby repozytorium stało się obrazem, ktory będzie zawierał R wraz z określonymi pakietami należy utworzyc 2 pliki:
+ `runtime.txt` - plik powinien zawierac wersje R wraz z datą np. `r-3,6-YYYY-MM-DD` lub `r-YYYY-MM-DD`
+ `install.R` -skrypt w R zawierający liste pakietów do instalacji np. install.packages('tidyverse')
