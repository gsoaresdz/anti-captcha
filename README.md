# Projeto Anti-Captcha

Este projeto utiliza a biblioteca Selenium e a API do Anti-Captcha para quebrar captchas do tipo reCAPTCHA v2 em uma página web de demonstração.

# Dependências

Para executar este projeto, você precisará instalar as seguintes bibliotecas:

- selenium
- webdriver-manager
- anticaptchaofficial
- pillow

Você pode instalá-las utilizando o seguinte comando:

```
pip install selenium webdriver-manager anticaptchaofficial pillow
```

# Configuração

Para executar o projeto, você precisará obter uma chave de API do Anti-Captcha. Substitua 'SUA_CHAVE_API' pela sua chave de API no arquivo `main.py`:

```
chave_api = 'SUA_CHAVE_API'
```

# Execução

Execute o script com o seguinte comando:

```
python quebrandoCaptcha.ipynb
```

# Funcionamento

O script seguirá os seguintes passos:

1. Importar as bibliotecas necessárias.
2. Inicializar o navegador web (Google Chrome) utilizando o Selenium.
3. Acessar a página web de demonstração do reCAPTCHA.
4. Quebrar o captcha utilizando a API do Anti-Captcha.
5. Inserir a resposta do captcha no campo apropriado.
6. Enviar o formulário com o captcha resolvido.
7. Salvar uma captura de tela como evidência da quebra do captcha.
8. Encerrar o navegador.

# Arquivo de código

O código completo está disponível em quebrandoCaptcha.ipynb.
