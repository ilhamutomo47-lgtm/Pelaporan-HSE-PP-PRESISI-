<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Pelaporan Insiden HSE - PT PP Presisi</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #f1f4f8;
    margin: 0;
}
.container {
    max-width: 800px;
    margin: 30px auto;
    background: #ffffff;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}
.header {
    text-align: center;
    border-bottom: 3px solid #0b4da2;
    padding-bottom: 15px;
}
.header h2 {
    margin: 5px 0;
    color: #0b4da2;
}
.header p {
    margin: 0;
    font-weight: bold;
}
label {
    font-weight: bold;
    display: block;
    margin-top: 15px;
}
input, select, textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border-radius: 5px;
    border: 1px solid #ccc;
}
textarea {
    resize: vertical;
}
button {
    margin-top: 25px;
    width: 100%;
    padding: 12px;
    background-color: #0b4da2;
    color: #ffffff;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}
button:hover {
    background-color: #083b7d;
}
.footer {
    text-align: center;
    margin-top: 25px;
    font-size: 13px;
    font-weight: bold;
}
</style>
</head>

<body>

<div class="container">

<div class="header">
    <h2>FORM PELAPORAN INSIDEN HSE</h2>
    <p>PT PP PRESISI Tbk</p>
</div>

<form>

<label>Tanggal Kejadian</label>
<input type="date" required>

<label>Jam Kejadian</label>
<input type="time" required>

<label>Lokasi Kejadian</label>
<input type="text" placeholder="Contoh: Area Loading / Hauling Road" required>

<label>Kategori Insiden</label>
<select required>
    <option value="">-- Pilih Kategori --</option>
    <option>Incident</option>
    <option>Accident</option>
    <option>Near Miss</option>
    <option>Unsafe Condition</option>
    <option>Unsafe Action</option>
</select>

<label>Nama Pekerja / Driver</label>
<input type="text" required>

<label>Unit / Alat</label>
<input type="text" placeholder="Contoh: Dump Truck 424">

<label>Kronologi Kejadian</label>
<textarea rows="4" required></textarea>

<label>Dampak Insiden</label>
<select>
    <option>Tidak ada cedera</option>
    <option>Cedera ringan</option>
    <option>Cedera berat</option>
    <option>Kerusakan alat</option>
</select>

<label>Tindakan Sementara</label>
<textarea rows="3"></textarea>

<label>Nama Pelapor (HSE / Pengawas)</label>
<input type="text" required>

<button type="submit">KIRIM LAPORAN</button>

</form>

<div class="footer">
    SAFETY FIRST<br>
    HSE PT PP PRESISI
</div>

</div>

</body>
</html>
