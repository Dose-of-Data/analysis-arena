# Pokémon Dataset Information

## Source
This dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/rounakbanik/pokemon?select=pokemon.csv) and is available under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).

## License
The dataset is released under the CC0 1.0 Universal license, which allows you to use, modify, and distribute the data without restrictions.

## Dataset Description
The Pokémon dataset includes various attributes for each Pokémon, such as:
- **Name**: The English name of the Pokémon.
- **Type**: Primary and secondary types of the Pokémon.
- **Base Stats**: Attributes such as HP, Attack, Defense, Special Attack, Special Defense, and Speed.
- **Other Features**: Additional features like abilities, weight, height, and generation.

## Data Structure
The dataset is structured as follows:

| Column            | Description                                                                                   |
|-------------------|-----------------------------------------------------------------------------------------------|
| `name`            | The English name of the Pokémon.                                                              |
| `japanese_name`   | The Original Japanese name of the Pokémon.                                                    |
| `pokedex_number`  | The entry number of the Pokémon in the National Pokedex.                                       |
| `percentage_male` | The percentage of the species that are male. Blank if the Pokémon is genderless.              |
| `type1`           | The Primary Type of the Pokémon.                                                              |
| `type2`           | The Secondary Type of the Pokémon.                                                            |
| `classification`  | The Classification of the Pokémon as described by the Sun and Moon Pokedex.                   |
| `height_m`        | Height of the Pokémon in meters.                                                              |
| `weight_kg`       | The Weight of the Pokémon in kilograms.                                                       |
| `capture_rate`    | Capture Rate of the Pokémon.                                                                  |
| `base_egg_steps`  | The number of steps required to hatch an egg of the Pokémon.                                  |
| `abilities`       | A stringified list of abilities that the Pokémon is capable of having.                        |
| `experience_growth`| The Experience Growth of the Pokémon.                                                       |
| `base_happiness`  | Base Happiness of the Pokémon.                                                                |
| `against_*`       | Eighteen features that denote the amount of damage taken against an attack of a particular type.|
| `hp`              | The Base HP of the Pokémon.                                                                   |
| `attack`          | The Base Attack of the Pokémon.                                                               |
| `defense`         | The Base Defense of the Pokémon.                                                              |
| `sp_attack`       | The Base Special Attack of the Pokémon.                                                       |
| `sp_defense`      | The Base Special Defense of the Pokémon.                                                      |
| `speed`           | The Base Speed of the Pokémon.                                                                |
| `generation`      | The numbered generation which the Pokémon was first introduced.                               |
| `is_legendary`    | Denotes if the Pokémon is legendary.                                                          |

Each row represents a different Pokémon.

## Usage
Participants are encouraged to explore the dataset to understand the relationships between different attributes. You can use this dataset for various analyses, such as:
- Exploratory Data Analysis (EDA)
- Predictive Modeling
- Optimization Tasks (e.g., Pokémon Team Optimization)

### Beginner Problem
- **Exploratory Data Analysis (EDA)**:
  - Perform EDA to uncover interesting insights about Pokémon attributes and relationships.
  - Create visualizations to illustrate distributions, correlations, and trends.

- **Predictive Modeling**:
  - Develop a basic predictive model to classify Pokémon as legendary or non-legendary using base stats and types.
  - Evaluate model performance using appropriate metrics.

### Advanced Problem
- **Team Composition Optimization**:
  - Develop a system to optimize a Pokémon team for battles based on various attributes, including types, base stats, and effectiveness against other types.
  - Use predictive models and optimization algorithms to create balanced and effective teams.

### Using Pokémon Abilities Data
Abilities in Pokémon games are passive effects that provide various benefits during battles. Each Pokémon can have one or more possible abilities, and these abilities can significantly influence a Pokémon's performance in battle. To effectively use the data related to abilities, participants are encouraged to research and gather more detailed information about each ability. This mimics real-world data science scenarios where additional data must be sourced to enrich primary datasets.

#### Suggested Resources for Abilities Data:
- **Bulbapedia**:
  - **URL**: [Bulbapedia Abilities](https://bulbapedia.bulbagarden.net/wiki/Ability)
  - **Description**: Comprehensive details about each Pokémon ability, including what it does, which Pokémon can have it, and how it affects battles.
- **Pokémon Database**:
  - **URL**: [Pokémon Database Abilities](https://pokemondb.net/ability)
  - **Description**: Lists all abilities along with their effects and the Pokémon that can possess them.
- **Serebii**:
  - **URL**: [Serebii Abilities](https://www.serebii.net/abilitydex/)
  - **Description**: Detailed descriptions of abilities, their effects, and other related data.
- **PokeAPI**:
  - **URL**: [PokeAPI](https://pokeapi.co/)
  - **Description**: Provides programmatic access to detailed Pokémon data, including abilities.

#### Why This Matters:
- **General**: Understanding abilities and their effects is essential for comprehensive analysis.
- **Beginner Problem**: Enhances EDA and predictive modeling by incorporating additional meaningful features.
- **Advanced Problem**: Critical for optimizing team composition and understanding battle dynamics.

### Damage Calculation Reference
For detailed information on how damage is calculated in Pokémon battles, refer to the [Damage article on Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Damage). This resource explains the various factors involved in damage calculation across different Pokémon game generations.

## Preprocessing Steps
Any preprocessing steps taken to clean and prepare the data for analysis should be documented here. This might include handling missing values, encoding categorical variables, and normalizing numerical features.

## Acknowledgments
The data was scraped from [Serebii.net](http://serebii.net/).

## Additional Information
This dataset contains information on all 802 Pokémon from all Seven Generations of Pokémon. The information contained in this dataset includes Base Stats, Performance against Other Types, Height, Weight, Classification, Egg Steps, Experience Points, Abilities, etc.

### Inspiration
With this dataset, you can explore and answer various questions such as:
- Is it possible to build a classifier to identify legendary Pokémon?
- How does height and weight of a Pokémon correlate with its various base stats?
- What factors influence the Experience Growth and Egg Steps? Are these quantities correlated?
- Which type is the strongest overall? Which is the weakest?
- Which type is the most likely to be a legendary Pokémon?
- Can you build a Pokémon dream team? A team of 6 Pokémon that inflicts the most damage while remaining relatively impervious to any other team of 6 Pokémon.

## Contact
For any questions or support, please reach out on the Discord #analysis-arena channel.

For more details and instructions, please refer to the [main README](README.md).
