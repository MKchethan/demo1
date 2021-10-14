```bash
requirements file 

touch requirements.txt
pip intsall -r requirementrs.txt
```


touch README.md

```bash
creating directiories and files
touch template.py
python template.py
```


mkdir data_given

```bash 
intializing git and dvc
git init
dvc init
dvc add data_given/BankNote_Authentication.csv
```

```bash 
To keep track of our code
git add .
git commit -m "first commit"
```

```bash
Adding origin
git remote add origin https://github.com/MKchethan/demo1.git
git branch -M main
git push -u origin main
```

```bash 
git add . && git commit -m "parameters added" && git push origin main
```

```bash 
touch src/get_data.py
dvc repro
git add . && git commit -m "get_data added" && git push origin main
```

```bash
touch src/load_data.py
dvc repro
git add . && git commit -m "load_data added" && git push origin main
```

```bash
touch src/split_data.py
python src/split_data.py
dvc repro
git add . && git commit -m "load_data added" && git push origin main
```