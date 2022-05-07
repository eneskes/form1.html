# form1.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Çalışmam </title>
</head>
<body>
   <form action="bu benim form çalışmam"> 
       <p>
       <label for="name"> name:</label>
        <input type="text" id="name"> </p>
        <p><label for="yas"> Yaşınız:</label>
        <input type="number" id="yas"></p>
        <p><label for="password">Şifre:</label>
        <input type="password" id="password" ></p>
        <p><label for="mail">Email:</label>
        <input type="email" id="mail"></p>
        <p><label for="onay">Confirm:</label>
        <input type="checkbox" id="onay"></p>
        <select 
        name="cities"> 
        <option value="01">Bilecik</option>
        <option value="02">İstanbul</option>
        <option value="03">Yalova</option>
        </select>
        <p><label for="">Adres</label>
        <textarea name="adres"  cols="30" rows="10"></textarea>
        </p>
        <p><input type="button" value="Kaydet"></p>
        <input type="submit" value="Gönderme">
        <input type="reset" value="Reset">
</form> 
</body>
</html>
