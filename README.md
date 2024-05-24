# Editor-de-Texto
Editor de Texto - FCT Unesp, Estrutura de Dados I

Atividade: Implementação de um editor de texto

Desenvolver um editor de texto simples utilizando a linguagem de programação C, aplicando conceitos aprendidos na disciplina de Estrutura de Dados I, como listas encadeadas, pilhas, filas, árvores, e operações básicas de manipulação de arquivos. No editor, deve ser lido um único caractere por vez, para então realizar o tratamento das teclas pressionadas. Uma sugestão é utilizar a função getch() que lê um único caractere diretamente do teclado.

O editor de texto deve permitir que o usuário realizar as seguintes operações:
Criar um Novo Documento: O usuário deve ser capaz de criar um novo documento de texto. O documento deve ser armazenado em memória utilizando uma estrutura de dados adequada.
Abrir um Documento Existente: O usuário deve ser capaz de abrir um documento de texto existente. O conteúdo do documento deve ser carregado em memória para edição.
Editar o Documento: 
Inserir texto: O usuário deve ser capaz de inserir texto em qualquer posição do documento. 
Deletar texto: O usuário deve ser capaz de deletar texto de qualquer posição do documento.  
Se o cursor está no início de uma linha (por exemplo, "|Texto"), pressionar a tecla Backspace move o cursor para o final da linha anterior e apaga a quebra de linha.
Se o cursor está no final de uma linha e há uma linha seguinte (por exemplo, "Texto|"), pressionar a tecla Delete move o cursor para o início da próxima linha e apaga a quebra de linha.
Criação de Nova Linha:
Quando pressionada a tecla Enter move o cursor para a próxima linha, criando uma nova linha de texto.
Salvar o Documento: O usuário deve ser capaz de salvar as alterações feitas no documento. O documento deve ser salvo em um arquivo de texto.
Desfazer e Refazer Ações: Implementar funcionalidades de desfazer e refazer ações. Utilize pilhas para gerenciar as operações de desfazer e refazer.
Navegação pelo Documento: Permitir ao usuário navegar pelo documento linha por linha e palavra por palavra.
(Adicional) Procurar uma Palavra no Texto:  Permite procurar uma palavra ou frase no texto, destacando todas as ocorrências da palavra ou frase no texto. A busca pode ser sensível ou insensível a maiúsculas, dependendo das configurações ou opções selecionadas.

Colaboradores: Daniel Servejeira e Rennan Furlaneto
