## **Projeto Anti-Captcha**

O Projeto Anti-Captcha é uma aplicação Python desenvolvida para automatizar a quebra de captchas do tipo reCAPTCHA v2 em páginas web. Utiliza a biblioteca Selenium para interação com navegadores web e a API do Anti-Captcha para resolver os captchas.

## **Regra de Negócio**

O principal objetivo do projeto é demonstrar a capacidade de automatizar a solução de captchas reCAPTCHA v2 em um site de teste, usando a API do Anti-Captcha. Isso pode ser útil para testes de penetração, automação de testes ou estudos relacionados a captchas.

## **Tecnologias Utilizadas**

- **Python**: Linguagem de programação
- **Selenium**: Biblioteca para automação de navegadores web
- **WebDriver Manager**: Gerenciador de drivers para navegadores
- **Anti-Captcha API**: Serviço de resolução de captchas
- **PIL (Python Imaging Library)**: Biblioteca para manipulação de imagens
    
    ```bash
    pip install selenium
    pip install anticaptchaofficial
    pip install time
    pip install Pillow
    ```
    

## **Versão do Python**

Este projeto é compatível com **Python 3.6** ou versões superiores.

## **IDE Recomendada**

Qualquer IDE que suporte desenvolvimento Python pode ser usada, como:

- PyCharm
- Visual Studio Code
- Jupyter Notebook
- Atom

## **Instalação e Configuração**

### **Clonando o Repositório**

Primeiramente, clone o repositório do projeto para sua máquina local.

### **Instalação das Dependências**

Para instalar as dependências do projeto, execute o seguinte comando no terminal:

```bash
pip install selenium webdriver-manager anticaptchaofficial pillow
```

### **Configuração da API Key**

Você deve adquirir uma chave API do Anti-Captcha. Após obter, substitua **`'SUA_CHAVE_API'`** pela sua chave real no script.

### **Instalação do WebDriver**

O WebDriver Manager cuidará automaticamente do download do driver necessário para o seu navegador. Certifique-se de ter o navegador correspondente instalado (por padrão, Chrome).

## **Execução do Código**

Para executar o projeto, abra o script no seu ambiente de desenvolvimento Python e execute-o. O script automatizará a abertura do navegador, acessará a página de teste do reCAPTCHA, resolverá o captcha e enviará a evidência da quebra do captcha.

### **Passos Executados pelo Código**

1. **Abertura do Navegador**: Inicia uma sessão do navegador Chrome.
2. **Acessando a Página Web**: Navega até a página com o reCAPTCHA v2.
3. **Quebrando o Captcha**: Utiliza a API do Anti-Captcha para resolver o captcha.
4. **Envio de Evidência**: Tira um screenshot como evidência após quebrar o captcha.
5. **Encerramento**: Fecha a sessão do navegador.

## **Observações Importantes**

- Este projeto é apenas para fins educacionais e de pesquisa.
- Quebrar captchas em sites sem permissão pode violar termos de serviço e leis locais.
- É importante usar este script de forma ética e responsável.
