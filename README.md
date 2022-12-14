# favorite-pokémon-table 
| This is my first table built using the `gt` package in `R`. | <img src="https://raw.githubusercontent.com/rstudio/hex-stickers/7ddd8ddf5a034eb9beb7c2c8b8112f68205694df/SVG/gt.svg" width="75px"> |
|-------------------------------------------------------------|----------------------------------------------------------------------------------------------------:|
---
![](images/pokemon-table.png)
---
## Table Building Process
> - Found and collected the Pokémon data from the [Pokémon Database site](https://pokemondb.net/)  
> 
> > |  | Collecting Data |  |
> > |---|---|---|
> > | a. | **Web scraped** the Pokémon types from this [page](https://pokemondb.net/pokedex/national) | [`view R script`](https://github.com/bradfordjohnson/favorite-pokemon-table/blob/main/rvest-scripts/pokemon-types-script.R) |
> > | b. | **Web scraped** the Pokémon heights and weights from this [page](https://pokemondb.net/pokedex/stats/height-weight) | [`view R script`](https://github.com/bradfordjohnson/favorite-pokemon-table/blob/main/rvest-scripts/pokemon-info-script.R) |
> > | c. | **Web scraped** the Pokémon stats from this [page](https://pokemondb.net/pokedex/all) | [`view R script`](https://github.com/bradfordjohnson/favorite-pokemon-table/blob/main/rvest-scripts/pokemon-data-script.R) |
> - Cleaned and wrangled data
> > |  | Cleaning / Wrangling Data |  |
> > |---|---|---|
> > | a. | **Hand cleaned** some data in excel, such as removing megas, and duplicates |  |
> > | b. | **Used `R`** to clean data up, such as formatting column names, removing symbols, filters etc. | [`view R script`](https://github.com/bradfordjohnson/favorite-pokemon-table/blob/main/table-script.R) |
> > | c. | **Used `R`** to wrangle and join all data sets with `inner_join()` functions | [`view R script`](https://github.com/bradfordjohnson/favorite-pokemon-table/blob/main/table-script.R) |
> - Creating the table
> > |  | Creating the Table |  |
> > |---|---|---|
> > | a. | **Used `R`** and **`gt`** to create a table of my favorite Pokémon | [`view R script`](https://github.com/bradfordjohnson/favorite-pokemon-table/blob/main/table-script.R) |
