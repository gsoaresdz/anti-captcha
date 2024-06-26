<h1 align="center">Projeto Anti-Captcha</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/anti-captcha?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/anti-captcha?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/anti-captcha?color=56BEB8">
  <!--<img alt="License" src="https://img.shields.io/github/license/seu-usuario/projeto-anti-captcha?color=56BEB8">-->
</p>
<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-recursos">Recursos</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execução">Execução</a> &#xa0; | &#xa0;
  <a href="#memo-observações-importantes">Observações Importantes</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/gsoaresdz" target="_blank">Autor</a>
</p>
<br>

## **:dart: Sobre**

O Projeto Anti-Captcha é uma aplicação Python desenvolvida para automatizar a quebra de captchas do tipo reCAPTCHA v2 em páginas web. Utiliza a biblioteca Selenium para interação com navegadores web e a API do Anti-Captcha para resolver os captchas.

## **:memo: Regra de Negócio**

O principal objetivo do projeto é demonstrar a capacidade de automatizar a solução de captchas reCAPTCHA v2 em um site de teste, usando a API do Anti-Captcha. Isso pode ser útil para testes de penetração, automação de testes ou estudos relacionados a captchas.

## **:sparkles: Recursos**

:heavy_check_mark: **Recurso 1**: Abertura do navegador e navegação até a página com reCAPTCHA v2.

:heavy_check_mark: **Recurso 2**: Utilização da API do Anti-Captcha para resolver o captcha.

:heavy_check_mark: **Recurso 3**: Captura de tela como evidência após resolver o captcha.

:heavy_check_mark: **Recurso 4**: Encerramento automático da sessão do navegador.

## **:rocket: Tecnologias**

As seguintes ferramentas foram usadas neste projeto:

- [Python](https://www.python.org/)
- [Selenium](https://www.selenium.dev/)
- [WebDriver Manager](https://pypi.org/project/webdriver-manager/)
- [Anti-Captcha API](https://anti-captcha.com/)
- [Pillow (Python Imaging Library)](https://pillow.readthedocs.io/en/stable/)

## **:white_check_mark: Requerimentos**

Antes de iniciar :checkered_flag:, você precisa ter [Python 3.6](https://www.python.org/downloads/release/python-360/) ou superior instalado.

## **:checkered_flag: Execução**

### Clonando o Repositório

Primeiramente, clone o repositório do projeto para sua máquina local.

```bash
$ git clone https://github.com/gsoaresdz/anti-captcha.git
```

### Instalação das Dependências

Para instalar as dependências do projeto, execute o seguinte comando no terminal:

```bash
$ pip install selenium webdriver-manager anticaptchaofficial pillow
```

### Configuração da API Key

Você deve adquirir uma chave API do Anti-Captcha. Após obter, substitua **`'SUA_CHAVE_API'`** pela sua chave real no script.

### Instalação do WebDriver

O WebDriver Manager cuidará automaticamente do download do driver necessário para o seu navegador. Certifique-se de ter o navegador correspondente instalado (por padrão, Chrome).

### Execução do Código

Para executar o projeto, abra o script no seu ambiente de desenvolvimento Python e execute-o. O script automatizará a abertura do navegador, acessará a página de teste do reCAPTCHA, resolverá o captcha e enviará a evidência da quebra do captcha.

### **Passos Executados pelo Código**

1. **Abertura do Navegador**: Inicia uma sessão do navegador Chrome.
2. **Acessando a Página Web**: Navega até a página com o reCAPTCHA v2.
3. **Quebrando o Captcha**: Utiliza a API do Anti-Captcha para resolver o captcha.
4. **Envio de Evidência**: Tira um screenshot como evidência após quebrar o captcha.
5. **Encerramento**: Fecha a sessão do navegador.

## **:memo: Observações Importantes**

- Este projeto é apenas para fins educacionais e de pesquisa.
- Quebrar captchas em sites sem permissão pode violar termos de serviço e leis locais.
- É importante usar este script de forma ética e responsável.

## **:memo: Licença**

Este projeto está sob licença do MIT. Para obter mais detalhes, consulte o arquivo [LICENSE](LICENSE).

Feito com :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

&#xa0;

<a href="#top">De volta ao topo</a>
