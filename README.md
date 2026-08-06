# Roadmap de Estudos — Programação

Repositório pessoal com meu plano de estudos, painel de progresso interativo e uma coleção de recursos gratuitos de programação (livros, cursos e trilhas).

## Conteúdo

- **`trilha-estudos.html`** — painel interativo com checklist de cursos por trilha (Web, Mobile, Dados/IA, DevOps, Sistemas, Java, etc). Progresso salvo automaticamente. Basta abrir o arquivo no navegador.
- **`plano-de-estudos-programacao.md`** — plano de estudos completo, organizado em fases e trilhas, com ordem sugerida de cursos e cronograma de referência.

## Recursos externos (submodules)

A pasta `recursos/` contém repositórios de terceiros com listas de livros e cursos gratuitos, vinculados como Git submodules:

| Pasta | Repositório original | Conteúdo |
|---|---|---|
| `recursos/free-programming-books` | [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | Maior coleção de livros de programação gratuitos, em dezenas de idiomas (incluindo português) |
| `recursos/free-livros` | [free-educa/free-livros](https://github.com/free-educa/free-livros) | Livros gratuitos de programação e educação em geral |
| `recursos/programming-books` | [CodesdaLu/Programming-Books](https://github.com/CodesdaLu/Programming-Books) | Coleção de livros de programação em português |

### Como clonar este repositório (com os submodules)

Como os recursos externos são submodules, é preciso um comando especial ao clonar:

```bash
git clone --recurse-submodules https://github.com/MauroMuguivizaDev/Roadmap_Mauro.git
```

Se você já clonou sem essa flag, rode:

```bash
git submodule update --init --recursive
```

### Atualizando os submodules

Os repositórios externos são mantidos por outras pessoas e recebem atualizações constantes. Para puxar a versão mais recente de cada um:

```bash
git submodule update --remote --merge
```

## Como usar

1. Abra `plano-de-estudos-programacao.md` para ver a trilha de estudos organizada.
2. Abra `trilha-estudos.html` no navegador para acompanhar seu progresso marcando os cursos concluídos.
3. Use os materiais em `recursos/` como fonte de livros e cursos complementares.

## Licença

Este repositório reúne conteúdo próprio (plano de estudos e painel) e referências a repositórios de terceiros, cada um com sua própria licença — consulte o repositório original de cada submodule.