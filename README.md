구동을 위하여 다음과 같은 별도의 파일을 구성하여야 합니다.
db = {
    'user': 'root',
    'password': 'YOUR DATABASE PASSWORD',
    'host': 'localhost',
    'port': 3306,
    'database': 'YOUR DATABASE NAME'
}

DB_URL = f"mysql+mysqlconnector://{db['user']}:{db['password']}@{db['host']}:{db['port']}/{db['database']}?charset=utf8"
