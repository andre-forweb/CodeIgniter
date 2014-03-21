# Esqueleto de aplicação com CodeIgniter

Esqueleto para projetos em codeigniter, com:

 - Suporte a Testes.
 - Deploy com PHING.
 - Framework Bootstrap.

Versões:

 - CodeIgniter 2.1.3
 - Bootstrap 3.0.1
 - Phing 2.7.0+
 - PHPUnit 3.7+
 - PHPMD 1.5.0+
 - PHP CodeSniffer 1.5.2+
 - Uglifyjs 2.4.12+

## Como usar:

 1. Clone este repositório
    1. Caso queira pode apagar a pasta .git e iniciar um novo git
 1. No arquivo _deploy/build.xml_:
    1. em _<project name="nomeProjeto" default="sincronizarAplicacao" basedir="diretorioBase">_ alterar o nomeProjeto com o nome do projeto e diretorioBase com o caminho (absoluto) para a raiz do projeto

 1. Alterar as configurações conforme o ambiente em _application/config/production_, _application/config/development_ e _application/config/testing_

# Considerações

 - Os suporte a testes é feito com o [ my-unit ]( https://bitbucket.org/kenjis/my-ciunit ), para mais informações sobre como usar a biblioteca é só acessar o link!
 - O [ Uglifyjs ]( https://github.com/mishoo/UglifyJS ) é uma ferramenta de minificação do javascript.
