# Schemas Go Here
+ Platforms(__TEXT Name__)
+ Games(__TEXT Name__, DATE ReleaseDate)
+ PokemonAppearance(__INTEGER ID__, INTEGER BaseHP, INTEGER BaseSpeed, INTEGER BaseAttack, INTEGER BaseDefence, INTEGER BaseSpAttack, INTEGER BaseSpDefence)
+ Pokemon(__INTEGER PokedexID__, TEXT Name, INTEGER GenderDistribution, BOOLEAN Legendary)
+ Media(__INTEGER ID__, TEXT Filename, BLOB Data)
+ MIMETypes(__TEXT MIMEString__, TEXT FriendlyName, TEXT Extension)
+ Types(__TEXT Name__)
+ Attacks(__TEXT Name__, INTEGER Priority, INTEGER Accuracy, INTEGER? TMNumber, INTEGER PP, INTEGER Power)

### Compatibility
+ AttackTypes()
+ PokemonEvolutions()
+ TypesMatchups(INTEGER EffectivenessMultiplier)
+ PokemonCanLearn(INTEGER AtLevel)
