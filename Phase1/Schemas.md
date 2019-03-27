# Schemas Go Here
+ Platforms(__Name__:TEXT)
+ Games(__GameName__:TEXT, __PlatformName__:TEXT, ReleaseDate:DATE)
+ PokemonAppearance(__ID__:INTEGER, __GameName__:TEXT, __PokedexID__:INTEGER, BaseHP:INTEGER, BaseSpeed:INTEGER, BaseAttack:INTEGER, BaseDefence:INTEGER, BaseSpAttack:INTEGER, BaseSpDefence:INTEGER)
+ Pokemon(__PokedexID__:INTEGER, Name:TEXT, GenderDistribution:INTEGER, Legendary:BOOLEAN)
+ Media(__ID__:INTEGER, __PokedexID__:INTEGER, __MIMEString__:TEXT, Filename:TEXT, Data:BLOB)
+ MIMETypes(__MIMEString__:TEXT, FriendlyName:TEXT, Extension:TEXT)
+ Types(__Name__:TEXT)
+ Attacks(__Name__:TEXT, Priority:INTEGER, Accuracy:INTEGER, TMNumber:INTEGER?, PP:INTEGER, Power:INTEGER)

### Compatibility
+ AttackTypes(__AttackName__:TEXT, __TypeName__:TEXT)
+ PokemonEvolutions(__PokemonBaseID__:INTEGER, __PokemonEvolutionID_:INTEGER)
+ TypesMatchups(__SelfName__:TEXT, __OtherName__:TEXT , EffectivenessMultiplier:INTEGER)
+ PokemonCanLearn(__PokemonID__:INTEGER, __AttackName__:TEXT, AtLevel:INTEGER)
