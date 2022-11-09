# Chess.com games database scrapping
Games scrapping from chess.com public API.
## Requirement
    !pip install pychesscom
## How To

1. You can just change the `'GM'` part with another title you want to explore e.g. IM, WGM, FM.
2. You might want to leave the `pgn` column since it takes hours to scrap. Nevertheless, it's depends on what are you gonna explore.
3. You can also change the years and months. In this notebook, I only want the 2021 games.

## Download
You can download the dataset here: https://www.kaggle.com/datasets/farhadzamani/gm-chess-games-2021
PS: I dropped `game_id`, `game_url`, and `pgn` column.

## Reference

1. Thanks to: https://www.kaggle.com/code/rohanrao/wgm-chess-games-dataset-preparation/notebook
2. Read more: https://pychesscom.readthedocs.io/
