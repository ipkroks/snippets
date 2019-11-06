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
