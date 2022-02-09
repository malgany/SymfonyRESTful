
# SymfonyRESTful
![RESTful](https://user-images.githubusercontent.com/4349392/153139399-0d5af985-9a57-4c59-8c98-f1e220921761.PNG)

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

Desenvolvi uma API que gerencia um consultório médico utilizando o padrão arquitetural Rest, que utiliza HTTP. Nessa API, é possivel acessar médicos e suas especialidades, fazer consultas, além de inserir, alterar ou remover médicos e suas especialidades.


## Instalação

* Baixar o PHP e instalar
* Baixar o Composer e instalar
* Criar o projeto SymfonyRESTful baseado no Symfony 4.2 com o seguinte comando:
```bash
composer create-project symfony/skeleton consultorio-alura "^4.2"
```
* Instalar o componente annotation do Symfony. Dentro da pasta do projeto, execute:
```bash
composer require annotation
```
## Uso/Exemplos

Subir o servidor na porta 8080, com a pasta public como target:
```bash
php -S localhost:8080 -t public
```


## Licença

[MIT](https://choosealicense.com/licenses/mit/)

