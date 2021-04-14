# Formulario-Varejo-Entrada-de-fornecedores-
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title> Recebimento Bellavia </title>
</head>

<body>

    <script src="script.js"></script>
    <div class=" img">
        <header>
            <img src=" imagens/bella.jpg" alt=" bella" height="75">
        </header>
    </div>

    <h2 class=" sub"> <strong> Controle de Notas Fiscais </strong> </h2>


    <div>
        <fieldset>
            <h4 class="nada"> Gral de prioridade para recebimento </h4>
            <ol>
                <li> Fornecedores de laticínios </li>
                <li> Fornecedores de Carnes , Peixes , Aves e Ovos </li>
                <li> Fornecedores de pães </li>
                <li> Fornecedores de carga Seca </li>
            </ol>
        </fieldset>
    </div>

    <p> <strong> Por gentileza prezado , preencher o formulario com os dados solicitados , para o recebimento.</strong>
    </p>


    <div>

        <form>

            <fieldset>
                <label for=" fornecedor"> Nome do Entregador </label>
                <input type="text" id=" entregador" name=" entregador" required> <br>
                <label for=" fornecedor">Fornecedor </label>
                <input type="text" id=" entregador" name=" entregador" required> <br>
                <label for=" data "> Data da entrega </label>
                <input type="date" id=" data" name=" data" required> <br>
                <label for=" horas "> Horario da chegada </label>
                <input type=" time" id=" Horas" name=" Horas " required>
            </fieldset>



            <br><br>

            <button class="botao" type="submit" onsubmit="">Concluído</button>

        </form>

    </div>

</body>



</html>
