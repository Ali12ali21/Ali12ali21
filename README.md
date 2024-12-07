<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MCS Computer</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0f172a;
            margin: 0;
            padding: 0;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            color: #38bdf8;
            margin-bottom: 20px;
            animation: fadeIn 2s ease-in-out;
        }
        h2 {
            font-size: 1.5em;
            color: #38bdf8;
            margin-top: 10px;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2em;
            margin-bottom: 30px;
            color: #ccc;
            line-height: 1.6;
        }
        .button {
            background: #1e293b;
            color: #38bdf8;
            padding: 15px 30px;
            border-radius: 10px;
            font-size: 1.2em;
            text-transform: uppercase;
            margin: 10px;
            text-decoration: none;
            border: 2px solid #38bdf8;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transition: all 0.3s ease;
        }
        .button:hover {
            transform: scale(1.1);
            background-color: #38bdf8;
            color: #0f172a;
        }
        .button img {
            width: 20px;
            height: 20px;
            margin-right: 10px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <h1>MCS Computer</h1>
    <h2>MCS - Multi-class Solutions</h2>
    <p>مركز متخصص في بيع الحواسيب في العراق. نقدم مجموعة متنوعة من الأجهزة التي تناسب جميع الفئات السعرية، لضمان تلبية احتياجاتك الدراسية والعملية. نلتزم بتوفير حلول تقنية نظيفة وعالية الجودة مدعومة بضمان شامل، مما يضمن لك أفضل تجربة.</p>
    <div class="container">
        <a href="https://www.facebook.com/profile.php?id=61551830694352&mibextid=ZbWKwL" class="button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"> Facebook
        </a>
        <a href="https://www.instagram.com/mcs_computer?igsh=d3djdmU0eXR1Z25q" class="button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" alt="Instagram"> Instagram
        </a>
        <a href="https://wa.me/whatsapp_number" class="button" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"> WhatsApp
        </a>
    </div>
</body>
</html>
