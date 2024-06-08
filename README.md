# ToJ-IkI-StO-N-BA-PesH
Normal day 

<html>
<head>
    <title>Örnek Sayfa</title>
    
    <style>
        body {
            color: black;
        }
        a:link {
            color: green;
        }
        a:visited {
            color: blue;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        .columns {
            column-count: 2;
            column-gap: 20px;
        }
        .paragraph {
            line-height: 2;
            word-spacing: 10px;
        }
        .rounded-box {
            background-color: green;
            border: 2px solid black;
            border-radius: 30px;
            padding: 10px;
            color: white;
            text-align: center;
        }
        .framed-text {
            border: 5px solid green;
            border-radius: 20px;
            padding: 10px;
        }
    </style>
</head>
<body>

<h1>Örnek Sayfa</h1>

<!-- 1. Tablo -->
<table border="1">
    <tr>
        <td>
            <ol>
                <li>Madde 1</li>
                <li>Madde 2</li>
                <li>Madde 3</li>
                <li>Madde 4</li>
            </ol>
        </td>
        <td><a href="https://gelisim.edu.tr">üniversite</a></td>
        <td><a href="https://www.google.com"><img src="image.jpg" alt="Google" width="100"></a></td>
    </tr>
</table>

<!-- 2. Image -->
<img src="split-image.jpg" usemap="#image-map" width="300" height="200">
<map name="image-map">
    <area shape="rect" coords="0,0,150,200" href="https://www.mgm.gov.tr/">
    <area shape="rect" coords="150,0,300,200" href="https://iklim.gov.tr/">
</map>

<!-- 3. Form -->
<form action="server_url" method="POST">
    Ad: <input type="text" name="ad" required><br>
    Soyad: <input type="text" name="soyad" required><br>
    Meslek: <input type="text" name="meslek" required><br>
    Yaş: <input type="number" name="yas" required><br>
    İlçe: <input type="text" name="ilce" required><br>
    Maaş: <input type="number" name="maas" required><br>
    Evli mi: <input type="text" name="evlimi" required><br>
    Çocuk Sayısı: <input type="number" name="cocuk_sayisi" required><br>
    <input type="submit" value="Gönder">
</form>

<!-- 4. Paragraf (2 sütun) -->
<div class="columns">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<!-- 5. Paragraf (satır arası ve kelime arası boşluk) -->
<p class="paragraph">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</p>

<!-- 6. 2x2 Tablo (Dikdörtgen ve Çerçeve) -->
<table border="1">
    <tr>
        <td><div class="rounded-box">ilk şekil</div></td>
        <td><div class="framed-text">Bu cümlede çerçeve var.</div></td>
    </tr>
</table>

<!-- 7. Giriş Formu -->
<form action="acilis.asp" method="POST">
    Kullanıcı Adı: <input type="text" name="kullanici_adi" required><br>
    Şifre: <input type="password" name="sifre" pattern="\d{4}" required><br>
    <input type="submit" value="Giriş Yap">
</form>

<!-- 8. Dikey Bölünmüş Sayfa -->
<div style="display: flex;">
    <div style="width: 50%;">
        <h2>Ders Hakkında Bilgiler</h2>
        <p>Adı: Örnek Ders</p>
        <p>İçerik: Ders içeriği burada yer alacaktır.</p>
        <p>Kredi: 3</p>
    </div>
    <div style="width: 50%;">
        <h2>Kaynak Kitap ve Ders Notları</h2>
        <ul>
            <li><a href="kaynak1.pdf">Kaynak Kitap 1</a></li>
            <li><a href="kaynak2.pdf">Kaynak Kitap 2</a></li>
            <li><a href="ders_notlari.pdf">Ders Notları</a></li>
        </ul>
    </div>
</div>

</body>
</html>

