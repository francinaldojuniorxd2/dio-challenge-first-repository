> # GIT
>
> 

- É um sistema de controle de versão distribuído

  **GitHub** 

  - Repositório de arquivos;

- O git utiliza o sistema de encriptação sah1 para identificar alterações nos arquivos. 

- Os hash gerados pelo openssl são diferentes devido que os arquivos do git ficam guardados dentro de um objeto chamado blob, esse objeto contem meta dados como tipo, tamanho, \0 e  conteúdo do arquivo.

- As tree são objetos que aponta para blobs ou outras tree que serve para identificar a localização e alterações de blobs ou outras árvores . 