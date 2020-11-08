<div dir="rtl" align="center">

- [فهرست](/README.md)

##### index

|     | فهرست                          |
| --- | ------------------------------ |
| ۱   | [پستگرس postgres](#javascript) |
| ۲   | [نودجی اس nodejs](#Nodejs)     |
| ۲   | [ان پی ام npm](#NPM)           |
| ۲   | [گیت git](#git)                |
| ۲   | [لینوکس linux](#Linux)         |

</div>

---

---

### Postgres

---

---

<div dir="rtl">

### نحوه اجرای محیط پستگرس

</div>

<details><summary><b>جواب</b></summary>
<p>

```bash
sudo su - postgres
psql

or sudo -u postgres psql

```

</p>
</details>

**[⬆ برو بالا](#index)**

---

<div dir="rtl">

### نحوه وصل شدن به دیتابس و نمایش جداول آن

</div>

<details><summary><b>جواب</b></summary>
<p>

```bash
\c DATABASE-NAME
\dt
```

</p>
</details>

**[⬆ برو بالا](#index)**

---

<div dir="rtl">

### نحوه حذف یک دیتابیس

</div>
<details><summary><b>جواب</b></summary>
<p>

```sql
DROP DATABASE DATABASE-NAME;
```

</p>
</details>

**[⬆ برو بالا](#index)**

---

<div dir="rtl">

### نحوه ایجاد کاربر

</div>
<details><summary><b>جواب</b></summary>
<p>

```sql

CREATE USER DATABASE-NAME WITH PASSWORD 'PASSWORD';

```

</p>
</details>

**[⬆ برو بالا](#index)**

---

<div dir="rtl">

### نحوه ایجاد دیتابیس

</div>
<details><summary><b>جواب</b></summary>
<p>

```sql
create database DATABASE-NAME with owner USER-NAME encoding='UTF8' lc_collate='en_US.UTF-8' lc_ctype='en_US.UTF-8';

```

</p>
</details>

**[⬆ برو بالا](#index)**

---

<div dir="rtl">

### نحوه ایمپورت اسکما از فایل

</div>
<details><summary><b>جواب</b></summary>
<p>

```bash
psql -h localhost -U USER-NAME -d DATABASE-NAME -f sql/FILE-NAME.sql

```

</p>
</details>

**[⬆ برو بالا](#index)**

---

<div dir="rtl">

### دستورات پرکاربرد دیگر

</div>
<details><summary><b>جواب</b></summary>
<p>

```bash
\?  - list all the commands
\l  - list databases
\conninfo - display information about current connection
\c [DBNAME] - connect to new database, e.g., \c template1
\dt - list tables of the public schema
\dt - <schema-name>.* list tables of certain schema, e.g., \dt public.*
\dt *.* - list tables of all schemas
Then you can run SQL statements, e.g., SELECT * FROM my_table;(Note: a statement must be terminated with semicolon ;)
\q - quit psql

.env:

DATABASE_URL=postgresql://DATABASE-NAME:USER-NAME@localhost:5432/DATABASE-NAME
HASH_SALT=XXXX
```

</p>
</details>

**[⬆ برو بالا](#index)**

---

---

### Nodejs

---

---

<div dir="rtl">

###### ۱. سوال

</div>
<details><summary><b>جواب</b></summary>
<p>

<div dir="rtl">
توضیح
</div>
</p>
</details>

**[⬆ برو بالا](#index)**

---

---

### NPM

---

---

<div dir="rtl">

### نحوه مشارکت در در پروزه های گیت هاب

</div>
<details><summary><b>جواب</b></summary>
<p>

1. Fork the project & clone locally.
2. Create an upstream remote and sync your local copy before you branch.

```bash
 git remote add upstream git@xxxxxxx
 git pull upstream master && git push origin master
```

3. Branch for each separate piece of work.

```bash
 git checkout -b hotfix/readme-update
```

4. Do the work, write good commit messages, and read the CONTRIBUTING file if there is one.
5. Push to your origin repository.
6. Create a new PR in GitHub.
7. Respond to any code review feedback.

https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-

<div dir="rtl">
توضیح
</div>
</p>
</details>

**[⬆ برو بالا](#index)**

---

---

### git

---

---

<div dir="rtl">

###### ۱. سوال

</div>
<details><summary><b>جواب</b></summary>
<p>

<div dir="rtl">
توضیح
</div>
</p>
</details>

**[⬆ برو بالا](#index)**

---

---

### Linux

---

---

<div dir="rtl">

###### ۱. سوال

</div>
<details><summary><b>جواب</b></summary>
<p>

<div dir="rtl">
توضیح
</div>
</p>
</details>

**[⬆ برو بالا](#index)**

---

###### ادامه دارد و به مرور بروز رسانی خواهد شد ..........

```

```
