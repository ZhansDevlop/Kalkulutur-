<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Ilmiah Modern</title>
    <style>
        /* --- CSS: Desain Tampilan Modern --- */
        :root {
            --bg-color: #22252d;
            --calc-bg: #292d36;
            --display-bg: #22252d;
            --text-color: #ffffff;
            --btn-color: #323742;
            --btn-hover: #3e4451;
            --operator-color: #272b33;
            --accent-color: #f57f17; /* Orange untuk operator */
            --accent-hover: #ff9100;
            --equal-color: #27ae60; /* Hijau untuk sama dengan */
            --equal-hover: #2ecc71;
            --danger-color: #c0392b; /* Merah untuk hapus */
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1e1e2f, #2c3e50);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: var(--text-color);
        }

        .kalkulator {
            background-color: var(--calc-bg);
            padding: 20px;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.6);
            width: 360px;
            max-width: 95%;
        }

        #layar {
            width: 100%;
            height: 70px;
            background-color: var(--display-bg);
            border: none;
            border-radius: 10px;
            margin-bottom: 20px;
            text-align: right;
            padding: 10px 20px;
            font-size: 2.2rem;
            color: var(--text-color);
            box-sizing: border-box;
            box-shadow: inset 0 2px 5px rgba(0,0,0,0.2);
        }

        /* Placeholder styling */
        #layar::placeholder {
            color: #555;
        }

        .tombol {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 12px;
        }

        button {
            padding: 18px;
            font-size: 1.1rem;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            background-color: var(--btn-color);
            color: var(--text-color);
            transition: all 0.2s ease;
            font-weight: 500;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
        }

        button:hover {
            background-color: var(--btn-hover);
            transform: translateY(-2px);
        }

        button:active {
            transform: scale(0.95);
            box-shadow: 0 1px 2px rgba(0,0,0,0.2);
        }

        /* Warna khusus untuk jenis tombol */
        .operator {
            background-color: var(--operator-color);
            color: var(--accent-color);
            font-weight: bold;
        }

        .operator:hover {
            background-color: #323742;
            color: var(--accent-hover);
        }

        .fungsi {
            background-color: #3e4654;
            font-size: 1rem;
        }

        .fungsi:hover {
            background-color: #4b5563;
        }

        .sama-dengan {
            background-color: var(--equal-color);
            color: white;
            grid-column: span 2;
        }

        .sama-dengan:hover {
            background-color: var(--equal-hover);
        }

        .hapus {
            background-color: var(--danger-color);
            color: white;
        }

        .hapus:hover {
            background-color: #e74c3c;
        }

        /* Responsif untuk HP */
        @media (max-width: 400px) {
            .kalkulator {
                width: 100%;
                border-radius: 0;
                height: 100vh;
                display: flex;
                flex-direction: column;
                justify-content: flex-end;
            }
            #layar {
                font-size: 3rem;
            }
        }
    </style>
</head>
<body>

    <div class="kalkulator">
        <!-- Layar Tampilan -->
        <input type="text" id="layar" placeholder="0" readonly>

        <!-- Tombol-Tombol -->
        <div class="tombol">
            <!-- Baris 1: Fungsi Trigonometri & Hapus -->
            <button class="fungsi" onclick="tambahFungsi('sin')">sin</button>
            <button class="fungsi" onclick="tambahFungsi('cos')">cos</button>
            <button class="fungsi" onclick="tambahFungsi('tan')">tan</button>
            <button class="hapus" onclick="hapusSemua()">AC</button>

            <!-- Baris 2: Logaritma & Hapus 1 Karakter -->
            <button class="fungsi" onclick="tambahFungsi('log')">log</button>
            <button class="fungsi" onclick="tambahFungsi('ln')">ln</button>
            <button class="fungsi" onclick="tambahFungsi('sqrt')">√</button>
            <button class="hapus" onclick="hapusSatu()">DEL</button>

            <!-- Baris 3: Kurung, Pangkat, Konstanta -->
            <button class="operator" onclick="tambahAngka('(')">(</button>
            <button class="operator" onclick="tambahAngka(')')">)</button>
            <button class="operator" onclick="tambahOperator('**')">x^y</button>
            <button class="operator" onclick="tambahAngka('π')">π</button>

            <!-- Baris 4: Angka 7-9 & Bagi -->
            <button onclick="tambahAngka('7')">7</button>
            <button onclick="tambahAngka('8')">8</button>
            <button onclick="tambahAngka('9')">9</button>
            <button class="operator" onclick="tambahOperator('/')">÷</button>

            <!-- Baris 5 -->
            <button onclick="tambahAngka('4')">4</button>
            <button onclick="tambahAngka('5')">5</button>
            <button onclick="tambahAngka('6')">6</button>
            <button class="operator" onclick="tambahOperator('*')">×</button>

            <!-- Baris 6 -->
            <button onclick="tambahAngka('1')">1</button>
            <button onclick="tambahAngka('2')">2</button>
            <button onclick="tambahAngka('3')">3</button>
            <button class="operator" onclick="tambahOperator('-')">-</button>

            <!-- Baris 7 -->
            <button onclick="tambahAngka('.')">.</button>
            <button onclick="tambahAngka('0')">0</button>
            <button class="operator" onclick="tambahAngka('e')">e</button>
            <button class="operator" onclick="tambahOperator('+')">+</button>

            <!-- Baris 8: Sama Dengan -->
            <button class="sama-dengan" onclick="hitung()">=</button>
        </div>
    </div>

    <script>
        /* --- JavaScript: Logika Kalkulator --- */
        const layar = document.getElementById('layar');

        // Fungsi untuk menambahkan angka atau karakter
        function tambahAngka(nilai) {
            // Mencegah koma ganda
            if (nilai === '.' && layar.value.includes('.')) return;
            // Mengganti koma input user dengan titik untuk kalkulator
            const valToAdd = nilai === ',' ? '.' : nilai;
            
            if (layar.value === '0' || layar.value === 'Error') {
                layar.value = valToAdd;
            } else {
                layar.value += valToAdd;
            }
        }

        // Fungsi untuk menambahkan operator
        function tambahOperator(operator) {
            const lastChar = layar.value.slice(-1);
            const operators = ['+', '-', '*', '/', '.', '(', '**'];
            
            // Cegah operator ganda berurutan (kecuali kurung)
            if (operators.includes(lastChar) && operator !== '**') {
                // Ganti operator lama dengan yang baru
                layar.value = layar.value.slice(0, -1) + operator;
            } else {
                layar.value += operator;
            }
        }

        // Fungsi untuk menambahkan fungsi ilmiah
        function tambahFungsi(func) {
            layar.value += func + '(';
        }

        // Fungsi Hapus Semua (AC)
        function hapusSemua() {
            layar.value = '';
        }

        // Fungsi Hapus 1 Karakter (DEL)
        function hapusSatu() {
            if (layar.value === 'Error') {
                layar.value = '';
            } else {
                layar.value = layar.value.toString().slice(0, -1);
            }
        }

        // Fungsi Hitung (=)
        function hitung() {
            try {
                let expression = layar.value;

                // Validasi dasar: Jika kosong, jangan hitung
                if (!expression) return;

                // 1. Ganti Konstanta
                expression = expression.replace(/π/g, 'Math.PI');
                expression = expression.replace(/e/g, 'Math.E');

                // 2. Ganti Fungsi Ilmiah menjadi Sintaks JavaScript
                // Catatan: Math.sin/cos/tan di JS menggunakan radian
                expression = expression.replace(/sqrt/g, 'Math.sqrt');
                expression = expression.replace(/sin/g, 'Math.sin');
                expression = expression.replace(/cos/g, 'Math.cos');
                expression = expression.replace(/tan/g, 'Math.tan');
                expression = expression.replace(/log/g, 'Math.log10'); // Log basis 10
                expression = expression.replace(/ln/g, 'Math.log');   // Log naturalis (basis e)

                // 3. Evaluasi menggunakan Function (lebih aman dari eval standar)
                // Kita buat function sementara untuk menghitung
                const result = new Function('return ' + expression)();

                // Format hasil: Jika bilangan bulat, tampilkan bulat. Jika desimal, maksimal 8 angka di belakang koma
                if (Number.isInteger(result)) {
                    layar.value = result;
                } else {
                    layar.value = parseFloat(result.toFixed(8));
                }

            } catch (error) {
                layar.value = 'Error';
                // Otomatis hapus error setelah 1.5 detik agar bisa input lagi
                setTimeout(() => {
                    if (layar.value === 'Error') layar.value = '';
                }, 1500);
            }
        }

        // --- Dukungan Keyboard ---
        document.addEventListener('keydown', function(event) {
            const key = event.key;
            const validKeys = '0123456789+-*/().';
            
            // Angka dan Operator Dasar
            if (validKeys.includes(key)) {
                if ('+-*/'.includes(key)) {
                    tambahOperator(key);
                } else {
                    tambahAngka(key);
                }
            }
            
            // Enter untuk Hitung
            else if (key === 'Enter') {
                hitung();
                event.preventDefault(); // Mencegah form submit jika ada
            }
            
            // Backspace untuk Hapus 1
            else if (key === 'Backspace') {
                hapusSatu();
            }
            
            // Escape untuk Hapus Semua
            else if (key === 'Escape') {
                hapusSemua();
            }
            
            // Keyboard tidak memiliki ^ atau sqrt, jadi kita abaikan atau bisa dipetakan
            // Misal: Shift+6 untuk ^
            else if (key === '^') {
                tambahOperator('**');
            }
        });
    </script>
</body>
</html>