# DJANGO 課程介紹

## 主旨

### 1.一次學習到網頁前端開發的三種工具(HTML/CSS/JavaScript)，並應用在網頁前端的畫面整合跟配置。

### 2.藉由[Python](https://www.python.org/)簡潔的語法及 web 框架套件開發出一個實用的多功能網站，在過程中將學習到一個網站的建立流程及如何撰寫出會員機制及後端產品上架等實用功能。

### 3.課程中包含 SQL 資料庫應用及熱門的 Git 的版本控管。

### 4.學習結束後能擁有作品並孰悉業界需要的技術，成為炙手可熱的全端工程師。

![markdown](https://miro.medium.com/max/1200/1*xJCYi2kk1HXBBJJVItq31w.png "markdown")

> [Django](https://zh.wikipedia.org/zh-tw/Django)是一個開放原始碼的 Web 應用框架，由 Python 寫成。採用了 MTV 的軟體設計模式，即模型，視圖和模板。它在開發初期用於管理勞倫斯出版集團旗下的一些以新聞為主的網站

---

Email : 17app001@gmail.com

# 課程細節(第一階段)

> ## GIT

### - _課堂數 x2_

- 安裝 VSCODE
- GIT 基礎語法
- GIT 實際運用
- [GITHUB](https://github.com/)  
  執行命令： `git init `

> ## HTML

### - _課堂數 x2_

- 基礎語法
- 列表/表格
- FORM 表單

```html
<!DOCTYPE html>
<html>
  <form method="post">.......</form>
</html>
```

> ## CSS

### - _課堂數 x2_

- 樣式設定
- 外部連結
- 響應式網頁設計

```css
<style>
    background:red;
    font-size:24px;
</style>
```

> ## JAVASCRIPT

### - _課堂數 x3_

- 基礎語法
- 流程控制
- 網站互動

```javascript
function helloWord() {
  console.log("Hello world!");
}
```

> ## MYSQL

### - _課堂數 x1_

- MySQL 語法介紹
  - 安裝 XAMPP
- Python 物件導向設計
- Python 連結 MySQL 方式

---

# 課程細節(第二階段)

!["FLASK"](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSAIr_3OAGDH2ELxQ10m6eNp9fYzl40BoGudA_grit7p9naUSrXoFdEdFaH41BcI0vs8nw&usqp=CAU "FLASK")

> Flask 是一個使用 Python 編寫的輕量級 Web 應用框架。基於 Werkzeug WSGI 工具箱和 Jinja2 模板引擎。Flask 使用 BSD 授權。 Flask 被稱為「微框架」，因為它使用簡單的核心，用擴充增加其他功能。Flask 沒有預設使用的資料庫、表單驗證工具。

> ## FLASK - 課堂數 x4

    - 基礎語法
    - 結合爬蟲
    - 結合視覺化

```javascript
from flask import Flask, escape, request
app = Flask(__name__)

@app.route('/')
def hello():
    name = request.args.get("name", "World")
    return f'Hello, {escape(name)}!'
```

![django](https://miro.medium.com/max/1200/1*xJCYi2kk1HXBBJJVItq31w.png)

> ## DJANGO - 課堂數 x6

    - 基礎語法
    - ORM資料庫
    - 註冊功能
    - 後臺功能
    - AWSMySQL介接
    - 網站上架測試

```javascript
INSTALLED_APPS = [
  "django.contrib.admin",
  "django.contrib.auth",
  "django.contrib.contenttypes",
  "django.contrib.sessions",
  "django.contrib.messages",
  "django.contrib.staticfiles",
];
```

# 總時數:20 個小時

---

範例作品

- https://flask-pm25-bulma.herokuapp.com/
- https://flask-todolistapp.herokuapp.com/
- https://epid-hotels.herokuapp.com/
- https://django-todolistapp.herokuapp.com/list/
- https://django-jcases.herokuapp.com/
- https://stepntw.herokuapp.com/
-

參考資料

- [MKEDITOR](https://www.mdeditor.tw/)
-

| 課程名稱   | 時數 |    備註 |
| :--------- | :--: | ------: | --- | --- |
| GIT        |  2   |         |
| HTML       |  2   |         |
| CSS        |  2   |         |
| JAVASCRIPT |  3   | 作品 x1 |
| MYSQL      |  1   |         |     |     |
| FLASK      |  4   | 作品 x1 |
| DJANGO     |  6   | 作品 x1 |
| 總時數     |  20  |         |

|
