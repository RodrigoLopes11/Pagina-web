<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Produtos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            font-size: 24px;
        }
        h2 {
            font-size: 20px;
        }
        h3 {
            font-size: 18px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        img {
            max-width: 100px;
        }
        details {
            margin-top: 10px;
        }
        summary {
            cursor: pointer;
        }
        blockquote {
            border-left: 2px solid #333;
            margin: 10px 0;
            padding-left: 10px;
        }
    </style>
</head>
<body>
    <h1>Catálogo de Produtos</h1>
    <table>
        <tr>
            <th>Foto</th>
            <th>Código</th>
            <th>Descrição</th>
            <th>Qtde em estoque</th>
            <th>Valor Unitário</th>
        </tr>
        <tr>
            <td>
                <details>
                    <summary><input type="checkbox" id="produto1"> <img src="mouse_razer.png" alt="Mouse Laser com fio Dell"></summary>
                    <p>Mouse Laser com fio Dell</p>
                    <p>Descrição do produto:</p>
                    <ul>
                        <li>O mouse Razer com fio é um dispositivo de alta precisão projetado para gamers e entusiastas de computadores. </li>
                        <li>Oferece rastreamento preciso, design ergonômico, iluminação RGB personalizável, botões programáveis e construção durável</li>
                        <li>Preço promocional em comparação á concorrência.</li>
                        <li>Uma escolha para quem busca um desempenho premium.</li>
                    </ul>
                </details>
            </td>
            <td>1</td>
            <td>Mouse Razer com fio</td>
            <td>5</td>
            <td>R$ 149,00</td>
        </tr>
        <tr>
            <td>
                <details>
                    <summary><input type="checkbox" id="produto2"> <img src="mouse_bluetooth.png" alt="Mouse Bluetooth Dell"></summary>
                    <p>Mouse Bluetooth Dell</p>
                    <p>Descrição do produto:</p>
                    <ul>
                        <li>O mouse Bluetooth da Dell é um dispositivo sem fio que se conecta a computadores e dispositivos móveis via Bluetooth, eliminando fios. </li>
                        <li>Com um design confortável e ergonômico, é compatível com diversos sistemas operacionais, oferece rastreamento preciso e possui recursos como rolagem fácil e botões personalizáveis</li>
                        <li>É uma escolha conveniente para quem busca conectividade Bluetooth e qualidade da Dell.</li>
                    </ul>
                </details>
            </td>
            <td>2</td>
            <td>Mouse Bluetooth Dell</td>
            <td>6</td>
            <td>R$ 338,00</td>
        </tr>
        <tr>
            <td>
                <details>
                    <summary><input type="checkbox" id="produto3"> <img src="mouse_optico.png" alt="Mouse óptico USB preto"></summary>
                    <p>Mouse óptico USB preto</p>
                    <p>Descrição do produto:</p>
                    <ul>
                        <li>O mouse óptico USB preto é um dispositivo de entrada simples e acessível.</li>
                        <li>Ele se conecta ao computador por USB, possui funcionalidade básica, design simples e é compatível com a maioria dos sistemas.</li>
                        <li>É ideal para tarefas de navegação e uso geral, adequado para quem não necessita de recursos avançados.</li>
                    </ul>
                </details>
            </td>
            <td>3</td>
            <td>Mouse óptico USB preto</td>
            <td>100</td>
            <td>R$ 48,30</td>
        </tr>
    </table>
    
    <h2>Comentários de Clientes</h2>
    <blockquote>
        <p>José Aparecido</p>
        <p>Muito bom</p>
    </blockquote>
    <blockquote>
        <p>Joaquim Jorge</p>
        <p>Bom</p>
    </blockquote>
</body>
</html>
