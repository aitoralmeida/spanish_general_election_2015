# Political party and candidate tweets for the campaign period of the 2015 Spanish general election
This dataset contains the political party and candidate tweets for the campaign period (4th to 18th of December) of the 2015 Spanish general election (https://en.wikipedia.org/wiki/Spanish_general_election,_2015).

The 2015 Spanish general election was held on Sunday, 20 December 2015, to elect the 11th Cortes Generales of Spain. All 350 seats in the Congress of Deputies were up for election, as well as 208 of 266 seats in the Senate.

The dataset contains 45,804 tweets with the following distribution:

| Screen_name   | Number of tweets  |
| ------------- | -----:|
| compromis     | 666   |
| sanchezcastejon |   626 |
| PPopular |    1406 |
|iunida|5903| 
|eajpnv|932| 
|tone_corunha|92| 
|coalicion|998| 
|ConvergenciaCAT|786| 
|CiudadanosCs|2356| 
|vox_es|487| 
|ForoAsturias|61| 
|marianbeitia|253| 
|komaur|842| 
|Nueva_Canarias|613| 
|Albert_Rivera|418| 
|geroabai|946| 
|obloque|563| 
|En_Marea|2101| 
|anioramas|128| 
|Esquerra_ERC|1612| 
|ehbildu|1918| 
|Herzogoff|577| 
|Unidadpopular__|5381| 
|ahoraencomun|10| 
|gabrielrufian|315| 
|UPYD|2329| 
|CatalunyaSi|5| 
|carloscallon|535| 
|Pablo_Iglesias_|212| 
|agarzon|380| 
|marianorajoy|651| 
|noscgalega|1896| 
|AITOR_ESTEBAN|53| 
|DuranLIeida|1| 
|unio_cat|904| 
|ahorapodemos|6211| 
|PSOE|2528| 
|franceschoms|109|
  


## Format

The file is formatted with a tweet per line, each line with the following fields separated by commas:

```
tweet_id, username, md5_hash
```

The tweet_id and the username can be used to recover the tweet content, and the md5 hex hash to validate the tweet text. To comply with the Twitter TOS we do not provide the content ourselves.

## Reference

Please, use the following reference if you use this dataset for your research:

Aitor Almeida, Pablo Orduña, Aritz Bilbao. 
Party and candidate tweets for the campaing period of the 2015 spanish general election. 
URL: https://github.com/aitoralmeida/spanish_general_election_2015/
