# Acessibilidade
Tornar um site acessível em Libras (Língua Brasileira de Sinais)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Site com Acessibilidade em Libras</title>
</head>
<body>
    <h1>Bem-vindo ao Meu Site</h1>
    <p>Este é um exemplo de site com acessibilidade em Libras.</p>

    <!-- Botão para ativar a tradução em Libras -->
    <button id="librasButton">Traduzir para Libras</button>

    <!-- Área onde a tradução em Libras será exibida -->
    <div id="librasTranslation"></div>

    <script src="libras.js"></script>
</body>
</html>

// Função para traduzir o conteúdo para Libras
function traduzirParaLibras() {
    const librasTranslation = document.getElementById('librasTranslation');
    
    // Você pode adicionar aqui o código para exibir um vídeo ou animação com intérprete de Libras.
    // Também pode fornecer uma transcrição em texto para a tradução.

    // Exemplo de exibição de texto de exemplo
    librasTranslation.innerHTML = '<p>Tradução em Libras do conteúdo aqui.</p>';
}

// Adiciona um ouvinte de evento para o botão
const librasButton = document.getElementById('librasButton');
librasButton.addEventListener('click', traduzirParaLibras);

