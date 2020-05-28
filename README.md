# sql-memo

### 全てのカラムを取得
SELECT * FROM テーブル名　（「*」アスタリスク)は「すべてのカラム」と言う意味。）

### 指定したカラム名を基準に降順(descending order → 543210,edcba)に表示　逆はの昇順は, asc (ascending order)
mysql> select * from テーブル名 order by カラム名 desc;

### 指定したカラム名の中の特定のデータを表示
mysql> select * from テーブル名 where email='suzu@ki';　(例)

