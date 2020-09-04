###### [<< Instalação e configuração](instalacao.md) | Comandos básicos | [Trabalhando com valores numéricos>>]() 

## Comandos básicos
Para começar a desenvolver o seu primeiro programa em Python é necessário criar um arquivo com a extensão **.py**  
Crie um arquivo chamado `hello.py`, com o conteúdo:

```python
print("Hello, World")
```


Se ao executar o arquivo `hello.py` a mensagem for exibida corretamente:
```bat
Hello, World
```

Tudo está funcionando corretamente e você pode seguir para as próximas etapas.  
Caso algum erro inesperado tenha aparecido, ou você não conseguiu executar o arquivo, confira se digitou o conteúdo exatamente como o exemplo. Se mesmo assim não resolveu, confira a seção de [Erros comuns e como resolvê-los]().



### print()
Embora o primeiro código seja muito simples e apenas exiba uma mensagem na tela, podemos destacar várias coisas importantes para dar continuidade com os estudos:

1. Python é case sensitive. Isso significa que python interpreta de forma diferente letras maiúsculas e minúsculas. A função **print()** é definida com todas as letras minúsculas. Se ao invés de `print("Hello World")`, você tivesse escrito, por exemplo `Print("Hello World")`, você veria uma mensagem de erro parecida com essa:

```python
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'Print' is not defined
```

2. Textos devem ser escritos entre aspas duplas `"` ou aspas simples `'` 