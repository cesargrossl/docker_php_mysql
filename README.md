# :whale: Docker Image com ambiente PHP, PDO, MySQL, PhpMyAdmin, Nginx

Estando dentro da pasta raíz ou via terminar do vscode, execute o comando abaixo:
-> docker-compose up 

## Conectar MySQL com ferramenta de manipulação como (Workbench, Dbeaver...)

```bash
    # Host (Nesse caso deve ser localhost, pois o software não consegue se conectar direto com o container)
    localhost

    # Port
    3306

    # User
    root

    # Password
    5020@1223
```

## PhpMyAdmin
* Para Acessar **localhost:8080** no navegador e ele já estará disponível. Para fazer login é só digitar as seguintes credenciais:
```bash
    # Host (deve ser o nome do container do MySQL e não localhost)
    mysql

    # User
    root

    # Password
    5020@1223
```




