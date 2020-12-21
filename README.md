# othello
An othello simulator, in a notebook, with pretty printouts.

Open this notebook in Google Colab with this link: https://colab.research.google.com/github/mayhewsw/othello/blob/main/othello.ipynb

Some example outputs:

```Counter({<Place.BLACK: 'X'>: 53, <Place.WHITE: 'O'>: 47})
White win percentage: 47.00%
Black win percentage: 53.00%
```

<table style='border-collapse: collapse;'><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: #FF6347; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: #90ee90; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: #90ee90; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: #90ee90; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: #90ee90; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: #90ee90; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td></tr><tr><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>O</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td><td style='padding: 0; background-color: white; width: 17px; height: 17px; border: 1px solid gray; text-align: center; vertical-align: middle;'>X</td></tr></table>
