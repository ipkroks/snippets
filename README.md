  **Поиск селектора/класса/идентификатора**
  
```javascript
$(".class").each(function( index ) {
	console.log( index + ": " + $( this ).text() ); 
});
```

**Подсчет количества повторяющихся значений в таблице MySql**

```sql
SELECT b_rid,COUNT(*) AS total FROM bc_rate GROUP BY b_rid ORDER BY total DESC LIMIT 1
```

**Поставить курсоры всем выбранным строкам**

```
ctrl+A - выделяем все строки
ctrl+shift+L - ставим выделенным строкам курсоры
```

**Путь до hosts в Linux**

```
/etc/hosts
```

**Путь до httpd-vhosts.conf в XAMPP (в Linux)**

```
/opt/lampp/etc/extra/httpd-vhosts.conf
```