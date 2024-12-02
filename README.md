passo a passo:

Criando o Arquivo Fonte
Abra um Editor de Texto:

Você pode usar um editor simples como o Bloco de Notas ou um editor de código como o Visual Studio Code.
Copie o Código:

Copie o código do programa de gerenciamento de estoque fornecido anteriormente.
Salvar o Arquivo:

Salve o arquivo com o nome estoque.c. Certifique-se de selecionar "Todos os Arquivos" na opção de tipo de arquivo, caso use o Bloco de Notas, para evitar que o arquivo seja salvo como estoque.c.txt.
Compilando o Programa
Abrir o Prompt de Comando:

Pressione Win + R, digite cmd e pressione Enter.
Navegar até o Diretório:

Use o comando cd para navegar até o diretório onde você salvou o arquivo estoque.c. Por exemplo:
Copiar
cd C:\caminho\para\seu\diretorio
Compilar o Programa:

Execute o seguinte comando para compilar o programa:
Copiar
gcc -o estoque estoque.c
Explicação do Comando:
gcc: chama o compilador GCC.
-o estoque: especifica o nome do arquivo executável que será gerado (neste caso, estoque).
estoque.c: é o nome do arquivo fonte que você criou.
Executando o Programa
Executar o Programa:

Após a compilação bem-sucedida, execute o programa com o seguinte comando:
Copiar
estoque.exe
Interagir com o Programa:

O menu principal será exibido. Siga as instruções na tela para adicionar produtos, consultar o estoque, vender produtos ou sair do programa.
