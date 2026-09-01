# Decodificador de Texto

Aplicação web criada no primeiro desafio do programa Oracle Next Education com a Alura. Ela criptografa e descriptografa textos no navegador usando um conjunto simples de substituições.

## Como funciona

| Letra | Código |
|---|---|
| `a` | `ai` |
| `e` | `enter` |
| `i` | `imes` |
| `o` | `ober` |
| `u` | `ufat` |

A entrada deve conter somente letras minúsculas, sem acentos nem caracteres especiais.

## Executar localmente

Nenhuma instalação é necessária. Clone o projeto e abra `index.html` no navegador:

```bash
git clone https://github.com/EduardoQuero/challenge-alura-encriptador.git
cd challenge-alura-encriptador
```

Para evitar limitações do navegador, também é possível usar um servidor local:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Estrutura

```text
assets/       imagens e ícones
js/           lógica da aplicação
styles/       estilos
index.html    página principal
```

## Tecnologias

HTML5, CSS3 e JavaScript.