..............................
<html lang="en">
<head>
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KMG</title>
    <link rel="shortcut icon" href="resim/icon.ico" type="icon">

</head>
<body>
    <center>
    <table border="1">
    <form>
        <tr>
        <th colspan="2">Başvuru formu <br></th>
        </tr>
    <tr>
        <td><label for="fname">Adınız :</label><br></td>
        <td><input type="text" name="fname" id="fname"><br></td>
    </tr>
    <tr>
        <td><label for="sname">Soyad :</label><br></td>
        <td><input type="text" name="sname" id="sname"></td>
    </tr>
    <tr>
         <td rowspan="2">Cinsiyet :</td>
         <td><input type="radio" name="r1" id="r2">
            <label for="kad">Kadın</label></td>
    </tr>
    <tr>
        <td><input type="radio" name="r1" id="r2">
         <label for="erk">Erkek</label></td>
    </tr>   
    <tr>
        <td rowspan="6">İlgi Alnı :</td>

        <td><input type="checkbox" name="spor" id="spor1">
        <label for="spor">spor</label></td><br>
    </tr>
    <tr>
        <td><input type="checkbox" name="oyun" id="oyun1">
        <label for="oyun">oyun</label></td><br>
    </tr>
    <tr>
        <td><input type="checkbox" name="Ders" id="Ders1">
        <label for="Ders">Ders</label></td><br>
    </tr>
    <tr</tr>
        <td><input type="checkbox" name="Para" id="Para1">
        <label for="Para">Para</label></td><br>
    </tr>
    <tr>
        <td><input type="checkbox" name="Sağlık" id="Sağlık1">
        <label for="Sağlık">Sağlık</label></td><br>
            
    </tr>
    <tr>
        <td><input type="checkbox" name="Masa" id="Masa">
        <label for="Masa">Masa</label></td><br>
    </tr>
    <tr>
        <td rowspan="2">Adres girin :</td>
    </tr>
    <tr>
        <td><textarea name="message" rows="10" cols="40" id="">
        </textarea></td><br>
    </tr>
    <tr>
        <td rowspan="2">Şehirler</td>
    </tr>
    <tr>
       <td><label for="Şehirler"></label>
       <select name="Şehirler" id="Şehirler">
        <option value="Ankara">Ankara</option>
        <option value="İstanbul">İstanbul</option>
        <option value="Van">Van</option>
        <option value="İzmir">İzmir</option>
        <option value="Maltya">Malatya</option>
        <option value="Rize">Rize</option>
       </select></td>
    </tr>
    <tr>
        <td colspan="2" >
            <input type="submit" name="Gönder" id="Gönder" value="Gönder"></td>
    </tr>
    </form>
</table>
</center>
</body>
</html>
