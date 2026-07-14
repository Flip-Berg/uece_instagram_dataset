# Descrição

este dataset reúne descrições e comentários de posts do instagram com tags relacionadas à Universidade Estadual do Ceará(UECE).

O dataset possui 48 hashtags, 6424 posts e 86365 comentários, sendo 808 deles
respostas a outros comentários.

# Construção

O dataset foi construído após longas execuções do programa https://github.com/Flip-Berg/selenium-parsel-instagram

# Estrutura

o dataset foi estruturado da seguinte forma:

```jsx
[
		{
        "tag": "<tag 1>",
        "posts": [
            {
                "descricao": "<descrição do post 1>",
                "comentarios": [
                    {
                        "comentario": "<comentário 1 do post 1>",
                        "respostas": [			"<resposta 1 ao comentário 1>",
			                    <próximas respostas ao comentário 1>
                    
                        ]
                    },
                    <próximos comentários do post 1>
                ]
            },
        <próximos posts da tag 1>
        ]
    },
    <próximas tags>
]

```
