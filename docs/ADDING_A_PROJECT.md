# Como adicionar um novo projeto à capa

Use este checklist sempre que uma nova landing page entrar no índice público.

## 1. Dados mínimos

Preencha e adicione uma linha na tabela **Resumo** do [README.md](../README.md):

| Campo | Exemplo |
|-------|---------|
| Projeto | Nome comercial |
| Stack | 3–5 tecnologias principais |
| Status | Produção / Em evolução |
| Última alteração | Data do último commit relevante (`DD/MM/AAAA`) |
| Site | URL pública https |

## 2. Bloco de case

No README, crie uma seção `### Nome do Projeto` com:

1. Screenshot em `docs/previews/nome-do-projeto.png`
2. Uma frase sobre o problema/entrega
3. Bullet **Stack**
4. Bullet **Entrega**
5. Bullet **Destaques técnicos** (até 3)
6. Bullet **Repositório** (`lMazer/lp-....` — privado, se aplicável)
7. Bullet **Site** (link clicável)

## 3. Screenshot

- Capturar a home em desktop (viewport largo)
- Salvar PNG em `docs/previews/`
- Referenciar no README com caminho relativo

## 4. Commit

Sugestão de mensagem:

```text
docs: adiciona [Nome do Projeto] ao índice de landing pages
```

## Modelo rápido (copiar/colar)

```markdown
### Nome do Projeto

![Preview Nome](docs/previews/nome.png)

Uma frase sobre a entrega.

- **Stack:** ...
- **Entrega:** ...
- **Destaques técnicos:** ...
- **Repositório:** `lMazer/lp-exemplo.com.br` *(privado)*
- **Site:** [exemplo.com.br](https://exemplo.com.br)
```
