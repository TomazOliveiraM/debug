Onde estava o erro:
Arquivo usuarios.json com formato JSON incorreto
Ausência de aspas nas chaves e strings
Objetos não estavam dentro de um array []
altavam vírgulas entre os objetos

Como resolvi os problemas
Corrigi o JSON, colocando os objetos dentro de um array, com todas as aspas e vírgulas necessárias
Declarei a variável mensagem dentro da função exibirMensagem().
Modifiquei o código para que a função que exibe a mensagem seja chamada após a leitura do arquivo, usando callback para garantir a ordem correta.
Criei o arquivo usuarios.json na mesma pasta que o script .js.
Ajustei a estrutura do código para fechar todas as chaves {} corretamente.

Ferramenta usada:
VSCode 
