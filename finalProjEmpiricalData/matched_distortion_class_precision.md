# Matched-Distortion Class Precision

Each row estimates $P(y = g \mid \hat{y} = g)$, the probability that an image is truly class $g$ given that the model guessed class $g$.

| model_trained_on   | tested_on   |   class_index | class_name   |   precision_P_true_class_given_model_guessed_class |
|:-------------------|:------------|--------------:|:-------------|---------------------------------------------------:|
| clean              | clean       |             0 | airplane     |                                           0.809935 |
| clean              | clean       |             1 | automobile   |                                           0.835616 |
| clean              | clean       |             2 | bird         |                                           0.622815 |
| clean              | clean       |             3 | cat          |                                           0.582278 |
| clean              | clean       |             4 | deer         |                                           0.769634 |
| clean              | clean       |             5 | dog          |                                           0.580508 |
| clean              | clean       |             6 | frog         |                                           0.7173   |
| clean              | clean       |             7 | horse        |                                           0.819491 |
| clean              | clean       |             8 | ship         |                                           0.82     |
| clean              | clean       |             9 | truck        |                                           0.789941 |
| gaussian           | gaussian    |             0 | airplane     |                                           0.68323  |
| gaussian           | gaussian    |             1 | automobile   |                                           0.844057 |
| gaussian           | gaussian    |             2 | bird         |                                           0.602823 |
| gaussian           | gaussian    |             3 | cat          |                                           0.491324 |
| gaussian           | gaussian    |             4 | deer         |                                           0.719949 |
| gaussian           | gaussian    |             5 | dog          |                                           0.554585 |
| gaussian           | gaussian    |             6 | frog         |                                           0.758901 |
| gaussian           | gaussian    |             7 | horse        |                                           0.756642 |
| gaussian           | gaussian    |             8 | ship         |                                           0.842466 |
| gaussian           | gaussian    |             9 | truck        |                                           0.704028 |
| salt_pepper        | salt_pepper |             0 | airplane     |                                           0.741764 |
| salt_pepper        | salt_pepper |             1 | automobile   |                                           0.853009 |
| salt_pepper        | salt_pepper |             2 | bird         |                                           0.579251 |
| salt_pepper        | salt_pepper |             3 | cat          |                                           0.495403 |
| salt_pepper        | salt_pepper |             4 | deer         |                                           0.616323 |
| salt_pepper        | salt_pepper |             5 | dog          |                                           0.551754 |
| salt_pepper        | salt_pepper |             6 | frog         |                                           0.767196 |
| salt_pepper        | salt_pepper |             7 | horse        |                                           0.739264 |
| salt_pepper        | salt_pepper |             8 | ship         |                                           0.786275 |
| salt_pepper        | salt_pepper |             9 | truck        |                                           0.749513 |
| blur               | blur        |             0 | airplane     |                                           0.73051  |
| blur               | blur        |             1 | automobile   |                                           0.829764 |
| blur               | blur        |             2 | bird         |                                           0.611518 |
| blur               | blur        |             3 | cat          |                                           0.482243 |
| blur               | blur        |             4 | deer         |                                           0.6167   |
| blur               | blur        |             5 | dog          |                                           0.565297 |
| blur               | blur        |             6 | frog         |                                           0.725472 |
| blur               | blur        |             7 | horse        |                                           0.749734 |
| blur               | blur        |             8 | ship         |                                           0.832258 |
| blur               | blur        |             9 | truck        |                                           0.76626  |
| mixed              | mixed       |             0 | airplane     |                                           0.745829 |
| mixed              | mixed       |             1 | automobile   |                                           0.818785 |
| mixed              | mixed       |             2 | bird         |                                           0.586694 |
| mixed              | mixed       |             3 | cat          |                                           0.462661 |
| mixed              | mixed       |             4 | deer         |                                           0.605496 |
| mixed              | mixed       |             5 | dog          |                                           0.548673 |
| mixed              | mixed       |             6 | frog         |                                           0.722112 |
| mixed              | mixed       |             7 | horse        |                                           0.744931 |
| mixed              | mixed       |             8 | ship         |                                           0.829032 |
| mixed              | mixed       |             9 | truck        |                                           0.748024 |