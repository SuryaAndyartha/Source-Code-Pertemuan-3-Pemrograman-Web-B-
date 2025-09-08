# Source-Code-Pertemuan-3-Pemrograman-Web-B-

### Source Code Membuat Tabel ###

```
<!DOCTYPE html>
<html>

<head>
    <title>Belajar Membuat Tabel</title>
</head>

<body>
    <font size = "3" face = "arial">

    <table border="1" cellpadding="10" bgcolor = "0C342C" align = "center">
    <caption align = "top"> <b> Daftar Nilai Mahasiswa </b> </caption>

    <tr bgcolor = "#69a75c">
        <th rowspan = "2">No</th>
        <th rowspan = "2">NRP</th>
        <th rowspan = "2">Nama</th>
        <th rowspan = "2">Kelas</th>
        <th colspan = "2">Nilai</th>
    </tr>

    <tr bgcolor = "#69a75c">
        <th> UTS </th>
        <th> UAS </th>
    </tr>

    <tr bgcolor = #b4ccac>
        <td align = "center" width = "20"> 1. </td>
        <td align = "left" valign = "middle" width = "80" height = "40"> 5025241093 </td>
        <td align = "left" valign = "middle" width = "250" height = "40"> Nyoman Surya Hutama Andyartha </td>
        <td align = "center" width = "20"> B2 </td>
        <td align = "center" valign = "middle"> 88 </td>
        <td align = "center" valign = "middle"> 92 </td>
    </tr>

    <tr bgcolor = #b4ccac>
        <td align = "center" width = "20"> 2. </td>
        <td align = "left" valign = "middle" width = "80" height = "40"> 5025241090 </td>
        <td align = "left" valign = "middle" width = "250" height = "40"> Willy Dava Nugraha </td>
        <td align = "center" width = "20"> B2 </td>
        <td align = "center" valign = "middle"> 98 </td>
        <td align = "center" valign = "middle"> 99 </td>
    </tr>

    <tr bgcolor = #b4ccac>
        <td align = "center" width = "20"> 3. </td>
        <td align = "left" valign = "middle" width = "80" height = "40"> 5025241400 </td>
        <td align = "left" valign = "middle" width = "250" height = "40"> Argus Tob Tobi </td>
        <td align = "center" width = "20"> A2 </td>
        <td align = "center" valign = "middle"> 58 </td>
        <td align = "center" valign = "middle"> 40 </td>
    </tr>


</body>

</html>
```

### Source Code Membuat Form ###

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Belajar Membuat Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #69a75c;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .form-container {
      background: #b4ccac;
      padding: 40px;
      border-radius: 40px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      width: 350px;
    }

    .form-container h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }

    .form-group {
      margin-bottom: 15px;
    }

    .form-group label {
      display: block;
      margin-bottom: 6px;
      font-size: 14px;
      color: #555;
    }

    .form-group input {
      width: 94%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 14px;
    }

    .form-group input:focus {
      outline: none;
      border-color: #4a90e2;
      box-shadow: 0 0 4px rgba(74,144,226,0.5);
    }

    .form-group select {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 14px;
    }

    .form-group select:focus {
      outline: none;
      border-color: #4a90e2;
      box-shadow: 0 0 4px rgba(74,144,226,0.5);
    }

    .btn-submit {
      width: 100%;
      padding: 12px;
      background: #0C342C;
      color: white;
      font-size: 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .btn-submit:hover {
      background: #357abd;
    }
  </style>
</head>
<body>

  <div class="form-container">
    <h2>Form Registrasi</h2>
    <form>
      <div class="form-group">
        <label for="fullname">First Name:</label>
        <input type="text" id="fullname" name="fullname" required>
      </div>
      <div class="form-group">
        <label for="fullname">Last Name:</label>
        <input type="text" id="fullname" name="fullname" required>
      </div>
      <div class="form-group">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
      </div>
      <div class="form-group">
        <label for="confirm-password">Re-type Password:</label>
        <input type="password" id="confirm-password" name="confirm-password" required>
      </div>
      <div class="form-group">
        <label for="confirm-password">Contact:</label>
        <input type="tel" id="contact" name="contact" required>
      </div>
      <div class="form-group">
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value = "male"> Laki-laki </option> 
            <option value = "female"> Perempuan </option> 
        </select>
      </div>
      <button type="submit" class="btn-submit">Submit</button>
    </form>
  </div>

</body>
</html>
```
