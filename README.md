## Heroku-Demo Steps

1. Create the model [model.py]
2. Store the model  [model.pickle]
3. Create the app   [app.py:flask app that loads the pickled model, starts server, loads index.html ]
4. Create requirements.txt
5. Create ProcFile  [web: gunicorn app(mainfile):app(mainfunction)]
6. Create an account in heroku
7. Create new deployment with inputs - deployment region, git-hub URL
8. Wait...
9. Check the model deployed at"
https://dashboard.heroku.com/apps/app-predict-salary/deploy/github
10.Make Predictions