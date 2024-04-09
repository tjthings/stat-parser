# Minecraft Stat Parser

1. Put all your stats json files into the stats_jsons folder
2. Run the python script
3. Take the stats.csv and do whatever you want with it


## Adding new stats:
1. Find the stats that interest you within a json file
2. Note the path you must take through the json file to reach there
3. Copy that path into `interesting_stats` of the python script
4. Add the column name to the `columns` variable (order matters)


## Future Additions
- [ ] Add something that queries the Mojang API to convert UUID -> IGN
- [ ] Refactor and reorganize the code to be easier to work with
- [ ] Link the stat to their column name so you don't have to update two places at once
- [ ] Add some preset assortments of interesting stats
