# Stack-Database

Initial database values for the Stack services

# IDM

IDM has `three` scripts that can be inserted in any order:
 - `idm_role.sql`
 - `idm_token_status.sql` 
 - `idm_user_status.sql`

# Movies

Movies has `five` scripts that should be inserted in this order:
 1. `movies_genre.sql`
 2. `movies_person.sql`
 3. `movies_movie.sql`
 4. `movies_movie_genre.sql`
 5. `movies_movie_person.sql`

#### TMDb

All the data for the database is sourced from TMDb: [The Movie Database](https://www.themoviedb.org/) and has been formatted to conform to our database.

<img src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_square_1-5bdc75aaebeb75dc7ae79426ddd9be3b2be1e342510f8202baf6bffa71d7f5c4.svg" alt="The Movie Database" width="200"/>
 
# Billing

Billing contains only `one` script:
 - `billing_movie_price.sql`
