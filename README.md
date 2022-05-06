# Desafio Git/GitHub

## Markdown cheat sheet

https://www.markdownguide.org/basic-syntax

## Comandos Terminal OS

**Todos esses comando possuem flag (complementos) que modificam, acrescentam ou formatam que esses comando sao devolvidos**

- ls //lista de diretorios situados na pasta 
- cd // change directory - permite que navegue pelos diretorios
- cd / // vai para "pasta mãe"
- cd nome de uma pasta //vai para pasta desejada
- cd .. //retrocede 1 nivel
- sudo su // pega a permissao para realizar determinadas atividades (necessário antes de usar mkdir) 
- mkdir // cria uma pasta no diretorio que está aberto
- rm -rf // remove + -r deleta todas as pastas que pode ter dentro + f force (nao pergunta se tem ctz)
- crtl + l ou clear //limpa a pagina do terminal
- cmd + l // limpa ultima linha do terminal
- tab // autocompletar
- echo hello world // escreve hello world no teminal 
- echo hello world > hello.txt // cria arquivo de txt chamado hello no repositorio aberto com o texto hello world




## Tipos de objetos no Git
SHA1 - Metodologia de criptogrofia usada pelo git que gera um codigo de 40 caracteres(hexadecimal) unica para cada arquivo: se eu alterar o arquivo muda o codigo, se eu desfizer a mudanca em uma nova versao o mesmo codigo anterior é gerado 
Git ao usar SHA1 armazena metadados 

cada um tem seu proprio sha1

- Blobs - armazena o conteudo dos arquvos 
- Trees 
   - armazena as blobs
   - responsavel por organizar a estrutura dos arquivos 
   - apontam para blobs ou trees
- Commits
  - mais importante
  - junta tudo, dá sentido pra alteracao realizada
  - apontam para uma arvore, um parente (commit anterior), um autor, uma mensagem e um timestamp
