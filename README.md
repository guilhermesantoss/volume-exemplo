# volume-exemplo

Exemplo usando volumes com Docker

- Para utilizar o $(pwd) é necessário estar no diretório onde estão os arquivos do projeto

```sh
  docker run -d -p 8080:3000 -v $(pwd):/var/www -w /var/www node npm start
```
