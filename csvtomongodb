import pymongo
from pymongo import MongoClient

import pandas as pd
from datetime import date, datetime, timedelta
from dateutil.parser import parse

df = pd.read_csv("/whatever/yourrfolder/file.csv")
user,pw, host,db = 'root','```whatever your mongodb password is```','127.0.0.1','myDB'

client = MongoClient()
db = client.ca2
collection = db.ca2

for index, col in df.iterrows():
    ```column_name``` = col[0]
    ```column_name``` = col[1]
    ```column_name``` = col[2]
   
    
    collection.insert_one({```column_name```:col[0], ```column_name```:col[1], ```column_name```:col[2]})
    print("Adding row" + str(index))
