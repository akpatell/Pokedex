# Pokedex Database
## Project Summary
<p> Create a database of Pokemon characters with “biological” data, as well as competitive data (such as popular moves, held items, etc), in order to please both the casual enjoyer as well as the competitive player, and even to help those looking to break into the metagame in team building. This will be done by creating a set of tables with information on the relevant Pokemon.</p>

## System Requirements
* jupyter notebook dictionaries
    - sqlalchemy
    - psycopg2
    - db_pw
    - pandas

## Resources
* <p><a href="https://github.com/akpatell/project_2_poke_decks.git ">GitHub Repository:</a></p>
* Database: PostgreSQL/pgAdmin
* Datasets:
	- <a href="https://www.kaggle.com/datasets/notgibs/smogon-6v6-pokemon-tiers">Smogon 6v6 Pokemon Tiers 29122016</a>
	- <a href="https://www.kaggle.com/datasets/giorgiocarbone/complete-competitive-pokmon-datasets-may-2022?select=df_items.csv">Complete Competitive Pokémon Database (May 2022) 08072022</a>
	- <a href="https://www.kaggle.com/datasets/rounakbanik/pokemon">The Complete Pokemon Dataset 2017</a>

## Group Members
* Kelly Brown
* Subodh Chintawar
* Gautam Iyer
* Leon Lee
* Ami Patel
* Aimee Vu
* William Tecchio

## Tasks
* Extract - Transform - Load
	- 2 CSV files were extracted in the jupyter notebook
    - 1 CSV file was imported directly into postgres
* Transform 
	- Data Cleaning and Normalization
        
	- Build relationship within different datasets
    - Primary keys used to build relationships were nationalDexNumber and name
      
	- Define and build key statistics 
      
	- See Tables section below
* Load
	- PostgreSQL

## Tables
<p>Tables created are: </p>

1. Table 1 - Pokedex (Biological Information)
2. Table 2 - Stats
3. Table 3 - Abilities



