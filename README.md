# CSDB


## Development

### Flask App

```
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
flask run
```

### NextJS App

First you need to create an API KEY in https://developers.themoviedb.org/3/getting-started/introduction

Once you have the api key navigate to the .env.local file and paste it there

```
.env.local
NEXT_PUBLIC_THE_MOVIE_DB_API_KEY=API KEY GOES HERE
```

Then

```
cd frontend
yarn install
yarn run dev
```
