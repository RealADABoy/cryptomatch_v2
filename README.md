# Cryptomatch v2 feature list



# API TODO
1 v2 mysql EDR finailzation
2 `restapi_cryptomatch_v2` api spec and endpoint definitions
    * scoring instead of filters
    * timestamps
    * no deletions
    * supports client authentication
    * distributed, resillient
3 deploy `restapi_external_data_manager`
4 deploy `restapi_cryptomatch_v2`
5 deploy `datalake` (mongodb nreplacs 2)
6 deploy `ETL-recommender`
7 deploy model generating services
8 deploy `restapi_recommender`
9 deploy `restapi_alert_manager`



## app logic feature wishes
- intro survey for new users to gauge interest
- decoupling app logic from filters (perhaps, transition to a scoring system) 
- Improved UI design
- Improved UX design
- Improved Performance
- Option to login with Guest Account
- Proof of burn as listing criterion
- iOS, android, and web, watch, and TVoS apps
- alerts for users when new suitable project lists
- methods for project owners to contact users who like them
- can have "I am a developer" mode so projects can find workers
- production data service / aggregates api layer
- opt in cookies, emails etc. opt in PII
- Price tracking / Market Cap tracking
- Add top alts / cryptos
- Charts
- Buy now option / Swap
- opt in "find users like me"

DB wishlist
- addresses as unique indexes (where appropriate, i.e. CA for `post` table)
- auto inc. integers
- timestamps
- user presented info (we have isLiked, but what if the user was shown something and they did not take an action?)

Beyond DB
- admin config plane & API (so robots can control configs)
- user engagement metrics
- recommender systems


# Roadmap

- Complete v2 api specification by November 20, 2021
- Complete v2 backend by December 15, 2021
- Release iOS app, web, and at least one TV platform (roku, apple tv) by Jan 1, 2022.
