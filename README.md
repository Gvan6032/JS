# JS
<!DOCTYPE html>
<html lang = "ru">
<head>
   <meta http-equiv="content-type" content="text/html; charset=win-1251">
   <title> Задание 1</title>
</head>
<body>
 <script>
    var        Age = 18,
               userName,
               userAge;
    function NameAge()
{
    do{
        userName = prompt('Введите ваше имя', '');
      }
    while (!userName);
    do {
         userAge=prompt('Введите свой возразст','');
         userAge = parseInt(userAge, 10);
       } while (isNaN(userAge));
    if (userAge<Age)
       {
         alert ('Здарова, '+userName+'. Как твои '+userAge+' ?');
         return;
       }
    alert ('Приветствую, '+userName+'. Уж '+userAge +' лет прошло');
}
NameAge();
</script>
</body>
</html>
