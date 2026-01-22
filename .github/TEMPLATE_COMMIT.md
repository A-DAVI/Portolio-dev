# Template de Commit

Este projeto segue o padrao [Conventional Commits](https://www.conventionalcommits.org/).

## Formato

```
<tipo>(<escopo>): <descricao curta>

<corpo opcional>

<rodape opcional>
```

## Tipos

| Tipo       | Descricao                                          |
|------------|---------------------------------------------------|
| `feat`     | Nova funcionalidade                               |
| `fix`      | Correcao de bug                                   |
| `docs`     | Alteracoes na documentacao                        |
| `style`    | Formatacao, ponto-e-virgula, etc (sem mudanca de codigo) |
| `refactor` | Refatoracao de codigo (sem nova feature ou fix)   |
| `perf`     | Melhorias de performance                          |
| `test`     | Adicao ou correcao de testes                      |
| `chore`    | Tarefas de build, configs, etc                    |
| `ci`       | Mudancas em CI/CD                                 |

## Escopos (opcionais)

- `html` - Alteracoes no index.html
- `css` - Alteracoes em estilos
- `js` - Alteracoes em JavaScript
- `assets` - Imagens e recursos
- `docs` - Documentacao

## Exemplos

```bash
# Nova funcionalidade
feat(html): adiciona secao de certificacoes

# Correcao de bug
fix(css): corrige responsividade do menu mobile

# Documentacao
docs: atualiza README com instrucoes de deploy

# Estilo
style(css): ajusta espacamento entre secoes

# Refatoracao
refactor(js): simplifica logica de animacoes

# Performance
perf(assets): otimiza imagens do portfolio

# Chore
chore: adiciona .gitignore
```

## Boas Praticas

1. Use o imperativo: "adiciona" em vez de "adicionado" ou "adicionando"
2. Primeira linha com no maximo 72 caracteres
3. Separe o titulo do corpo com uma linha em branco
4. Use o corpo para explicar "o que" e "por que", nao "como"

## Exemplo Completo

```
feat(html): adiciona secao de projetos com cards interativos

- Implementa layout alternado para os cards
- Adiciona animacoes de entrada com Intersection Observer
- Inclui links para repositorios no GitHub

Closes #12
```
