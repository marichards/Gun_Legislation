# Gun_Legislation
A hackathon project to show senator support for gun legislation by state


## Tips for loading data

For getting the NRA rating data, simply load the pickle file:

```
nra_ratings = pd.read_pickle('./nra_all_years.pickle')

```

For getting the gun violence data, grab the included csv:

```
gun_deaths = pd.read_table("./Underlying_Cause_of_Death_1999-2016.txt")
```