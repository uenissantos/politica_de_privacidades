# Como adicionar a política de outro app

1. Crie uma pasta com o nome do app em letras minúsculas e sem espaço, por exemplo `meu-outro-app`.
2. Copie `_modelo/politica.html` para dentro dela com o nome `index.html` e troque os textos em MAIÚSCULAS.
3. Inclua o app em `apps.json`, separando por vírgula:
```
  {
    "nome": "Meu Outro App",
    "descricao": "Uma frase sobre o app.",
    "pasta": "meu-outro-app"
  }
```
4. Faça o commit. Em 1 a 2 minutos o endereço fica:
`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/meu-outro-app/`

Use esse endereço na Play Console (Conteúdo do app > Política de privacidade). A pasta `_modelo` não é publicada.
