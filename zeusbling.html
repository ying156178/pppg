<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tính phụ phí phí gói</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #f7f9fc;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
    }
    h1 {
      margin-bottom: 30px;
      text-align: center;
    }
    form {
      width: 100%;
      max-width: 480px;
      background: #fff;
      padding: 24px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.05);
    }
    label {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 6px;
      margin-bottom: 20px;
      font-weight: 600;
    }
    .input-group {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 10px;
    }
    .input-group button {
      padding: 4px 12px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
      width: 32px;
      height: 32px;
    }
    .input-group button:hover {
      background-color: #0056b3;
    }
    .input-group input[type="number"] {
      width: 40px;
      height: 28px;
      font-size: 15px;
      text-align: center;
      border: 1px solid #bbb;
      border-radius: 6px;
      -moz-appearance: textfield;
    }
    .input-group input[type=number]::-webkit-outer-spin-button,
    .input-group input[type=number]::-webkit-inner-spin-button {
      -webkit-appearance: none;
      margin: 0;
    }
    .submit {
      width: 100%;
      padding: 8px;
      font-size: 15px;
      font-weight: 600;
      border: none;
      border-radius: 6px;
      background-color: #28a745;
      color: white;
      cursor: pointer;
      transition: background-color 0.2s ease-in-out;
    }
    .submit:hover {
      background-color: #218838;
    }
    .result {
      margin-top: 24px;
      max-width: 480px;
      background: #e6f7e6;
      padding: 16px;
      border-left: 5px solid #28a745;
      font-weight: 600;
      border-radius: 8px;
      text-align: center;
    }
  </style>
</head>
<body>
  <h1>Tính phụ phí phí gói</h1>

  <form id="feeForm">
    <label>Note Peanut:
      <div class="input-group">
        <button type="button" onclick="changeValue('notePeanut', -1)">-</button>
        <input type="number" id="notePeanut" min="0">
        <button type="button" onclick="changeValue('notePeanut', 1)">+</button>
      </div>
    </label>
    <label>Note Zeus:
      <div class="input-group">
        <button type="button" onclick="changeValue('noteZeus', -1)">-</button>
        <input type="number" id="noteZeus" min="0">
        <button type="button" onclick="changeValue('noteZeus', 1)">+</button>
      </div>
    </label>
    <label>Key Zeus em bé được ban phước:
      <div class="input-group">
        <button type="button" onclick="changeValue('keyZeus', -1)">-</button>
        <input type="number" id="keyZeus" min="0">
        <button type="button" onclick="changeValue('keyZeus', 1)">+</button>
      </div>
    </label>
    <button type="button" class="submit" onclick="calculateFee()">Tính phí</button>
  </form>

  <div class="result" id="result" style="display:none;"></div>

  <script>
    function changeValue(id, delta) {
      const input = document.getElementById(id);
      let value = parseInt(input.value) || 0;
      value += delta;
      if (value < 0) value = 0;
      input.value = value;
    }

    function calculateFee() {
      const getValue = id => {
        const val = document.getElementById(id).value;
        return val === '' ? 0 : parseInt(val);
      };

      const notePeanut = getValue('notePeanut');
      const noteZeus = getValue('noteZeus');
      const keyZeus = getValue('keyZeus');

      const totalItems = notePeanut + noteZeus + keyZeus;

      if ([notePeanut, noteZeus, keyZeus].some(x => isNaN(x) || x < 0)) {
        alert("Vui lòng nhập số hợp lệ vào tất cả các ô input.");
        return;
      }

      if (totalItems === 0) {
        document.getElementById("result").style.display = 'block';
        document.getElementById("result").innerText = `Tổng phí gói: 0 VND`;
        return;
      }

      const baseFee = 500; // BBW, băng keo, mực
      const noteFee = 205 * (notePeanut + noteZeus);
      const keyFee = (205 + 50) * keyZeus; // phụ phí + túi bọc

      const boxFee = totalItems < 5 ? 1400 : 1900;

      const finalFee = baseFee + noteFee + keyFee + boxFee;

      document.getElementById("result").style.display = 'block';
      document.getElementById("result").innerText = `Tổng phụ phí phí gói: ${finalFee.toLocaleString()} VND`;
    }
  </script>
</body>
</html>
