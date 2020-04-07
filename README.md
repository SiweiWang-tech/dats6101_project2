# dats6101_project2
dats 6101 project2

Project SMART: What are factors that affect the liekability of songs.

Data:
Link at: https://www.kaggle.com/theoverman/the-spotify-hit-predictor-dataset (just the 2000's csv dataset - it has 5000+ songs)
Data presents a collection of song features (calculated from Spotify's own internal algorithms and distributed on their API).  All songs have a "target" variable; this variable can be either '0' or '1': '1' implies that this song has featured in the weekly list (Issued by Billboards) of Hot-100 tracks in that decade at least once and is therefore a 'hit'. '0' Implies that the track is a 'flop'.

Project Timeline and Tasking:
  Report:
    Introduction (Purpose, background, discussion of music features)
      Written by Rich
    Discussion (how data was collecting, when and from where, preprocessing)
      Written by Rich
    Tests (For each test, write down the following: What the test says/Why are we performing, the assumptions of test, the math behind (why I trust the results), and discussion of conclusion.  Another good method is for each of the tests below, conduct all of the indiviudal tests that were performed in each weekly Rstudio document for said test (e.g., logit - our point is to impress with the data discussion and fill out a 10-page report):
      KNN - Use Target variable (not genre like we discussed - in reviewing the Spotify API controls and the data, Spotify doesn't actually store genre information for indivudal tracks and albums and stores multiple genres for individual artists so using KNN for genre is not feasible)
        Written by Juhn
      Logit - (Linear Regression but with non-linear modeling - our target is binary so this is good)
        Written by Siwei
      Feature Selection/Model selection - (Discussion of why is the best with computing time)
        Written by Krystal
    Conclusion:
      Written by Rich
      
