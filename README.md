# FIFA23-Card-Rating-Prediction

To view the user's portfolio blog on the anime recommendation system using collaborative filtering, please visit [My Blog](https://danielrs.systeme.io/fifa23-overall-rating-prediction) to see the explanation of the notebook.

Due to the use of `plotly.express` and `plotly.graph_objects`, the visualizations in this code cannot be displayed on GitHub. To view the visualizations, please download the code and run it on your local machine.

## FIFA23 Dataset
Here's a brief explanation of each column in the FIFA23 dataset:
| Column Name | Description |
| --- | --- |
| `Unnamed: 0` | An index column that contains a unique identifier for each row in the dataset. |
| `name` | The name of the player. |
| `rating` | The overall rating of the player. |
| `card_type` | The type of card that the player has (e.g. gold, silver, bronze). |
| `position` | The position that the player plays in. |
| `nation` | The nationality of the player. |
| `league` | The league that the player belongs to. |
| `team` | The team that the player belongs to. |
| `PAC` | The rating of the player's pace. |
| `SHO` | The rating of the player's shooting. |
| `PAS` | The rating of the player's passing. |
| `DRI` | The rating of the player's dribbling. |
| `DEF` | The rating of the player's defending. |
| `PHY` | The rating of the player's physicality. |

In summary, this dataset contains information about FIFA23 players, including their ratings and attributes in various categories such as pace, shooting, passing, dribbling, defending, and physicality. The dataset also includes information about the player's card type, position, nationality, league, and team.

## Usage
The project files for FIFA23 are as follows:
| File Name | Description |
| --- | --- |
| `FIFA23-EDA.ipynb` | This notebook contains Exploratory Data Analysis (EDA) for FIFA23. |
| `FIFA23-Model.ipynb` | This notebook focuses on model building for FIFA23. |
| `fifa_2023.csv` | This dataset is used for analysis and model training. |
| `sample_data.csv` | This dataset is used to test the model. |
| `world_map.html` | This file shows player distribution by nation. Download it and open it with your preferred browser. |

These files provide an overview of the EDA, model development, datasets used, and a visual representation of player distribution across nations.

## Acknowledgments

I would like to express my gratitude to the following sources for their contributions to this dataset:

- Kaggle: This dataset served as the basis for my analysis and model building. I would like to thank the contributors who originally collected and shared this dataset, as it provided valuable insights and data for my research.
  
## Dataset Source

The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/crxxom/fifa2023-all-cards), a popular dataset resource. This project is a simple model prediction that predicts the overall ratings of FIFA23 cards.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
