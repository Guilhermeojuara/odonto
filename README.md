<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultório Odontológico Dayse Nóbrega</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: url('https://www.toptal.com/designers/subtlepatterns/patterns/marble.png'); /* Efeito de mármore */
            background-size: cover;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #F8B7D4; /* Rosa Claro */
            color: white;
            padding: 30px;
            text-align: center;
            border-bottom: 5px solid #e5a3b1;
        }

        h1 {
            margin: 0;
        }

        .container {
            width: 80%;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .form-group {
            margin-bottom: 15px;
        }

        label {
            font-weight: bold;
            display: block;
            color: #F8B7D4; /* Rosa Claro */
        }

        input, select, button {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #e5a3b1;
            border-radius: 5px;
            font-size: 16px;
        }

        button {
            background-color: #F8B7D4; /* Rosa Claro */
            color: white;
            border: none;
            cursor: pointer;
            font-size: 18px;
        }

        button:hover {
            background-color: #e5a3b1; /* Tom de rosa mais escuro para o hover */
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #F8B7D4; /* Rosa Claro */
            color: white;
        }

        /* Estilo do formulário */
        input, select {
            background-color: #f9f9f9; /* Fundo claro para inputs e selects */
            border: 1px solid #ddd;
        }

        /* Efeito de Mármore Brilhante */
        body {
            background: url('https://www.toptal.com/designers/subtlepatterns/patterns/marble.png') repeat;
            background-size: cover;
            background-attachment: fixed;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho do site -->
    <header>
        <h1>Consultório Odontológico Dayse Nóbrega</h1>
        <p>Agende sua consulta agora!</p>
    </header>

    <!-- Formulário de agendamento -->
    <div class="container">
        <h2>Agendar Consulta</h2>
        <form action="submit_form.php" method="POST">
            <div class="form-group">
                <label for="nome">Nome Completo:</label>
                <input type="text" id="nome" name="nome" required>
            </div>

            <div class="form-group">
                <label for="telefone">Telefone:</label>
                <input type="tel" id="telefone" name="telefone" required pattern="[0-9]{10,11}">
            </div>

            <div class="form-group">
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div class="form-group">
                <label for="dia-consulta">Dia da Consulta:</label>
                <select id="dia-consulta" name="dia_consulta" required>
                    <option value="2024-11-14">14 de Novembro de 2024 (quinta-feira)</option>
                    <option value="2024-11-15">15 de Novembro de 2024 (sexta-feira)</option>
                    <option value="2024-11-16">16 de Novembro de 2024 (sábado)</option>
                    <option value="2024-11-18">18 de Novembro de 2024 (segunda-feira)</option>
                    <option value="2024-11-19">19 de Novembro de 2024 (terça-feira)</option>
                    <!-- Adicione ou remova dias conforme sua disponibilidade -->
                </select>
            </div>

            <div class="form-group">
                <label for="hora-consulta">Hora da Consulta:</label>
                <select id="hora-consulta" name="hora_consulta" required>
                    <option value="09:00">09:00</option>
                    <option value="10:00">10:00</option>
                    <option value="11:00">11:00</option>
                    <option value="14:00">14:00</option>
                    <option value="15:00">15:00</option>
                    <option value="16:00">16:00</option>
                    <!-- Adicione ou remova horários conforme sua disponibilidade -->
                </select>
            </div>

            <div class="form-group">
                <button type="submit">Agendar Consulta</button>
            </div>
        </form>
    </div>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Consultório Odontológico Dayse Nóbrega - Todos os direitos reservados.</p>
    </footer>

</body>
</html>
