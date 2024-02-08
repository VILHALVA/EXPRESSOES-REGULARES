# MINICURSO:
## O QUE É EXPRESSÕES REGULARES?
Expressões regulares, também conhecidas como regex ou regexp, são padrões de busca utilizados para identificar determinados padrões em strings de texto. Elas são extremamente úteis em tarefas relacionadas ao processamento de texto, como validação de formulários, análise de dados, manipulação de strings e pesquisa em grandes conjuntos de dados.

As expressões regulares consistem em uma sequência de caracteres que definem um padrão de busca. Esses padrões podem incluir caracteres literais (como letras e números), caracteres especiais (como *, +, ?), classes de caracteres (como \d para dígitos numéricos) e metacaracteres (como ^ para o início de uma linha e $ para o final de uma linha).

Por exemplo, a expressão regular `\b\d{3}-\d{3}-\d{4}\b` pode ser usada para validar números de telefone no formato (123) 456-7890. Nesta expressão regular:
- `\b` representa uma fronteira de palavra.
- `\d{3}` corresponde a três dígitos.
- `-` corresponde ao caractere de hífen.
- `\b` representa outra fronteira de palavra.

## TABELA PARA EXPRESSÕES REGULARES:
| Símbolo | Descrição                             |
| ------- | ------------------------------------- |
| `.`     | Corresponde a qualquer caractere exceto uma nova linha.                           |
| `^`     | Corresponde ao início de uma linha.                       |
| `$`     | Corresponde ao final de uma linha.                          |
| `\d`    | Corresponde a um dígito numérico (0-9).                    |
| `\D`    | Corresponde a qualquer caractere que não seja um dígito numérico.         |
| `\w`    | Corresponde a qualquer caractere alfanumérico (A-Z, a-z, 0-9, _).         |
| `\W`    | Corresponde a qualquer caractere que não seja alfanumérico.              |
| `\s`    | Corresponde a qualquer caractere de espaço em branco (espaço, tabulação, nova linha). |
| `\S`    | Corresponde a qualquer caractere que não seja um espaço em branco.           |
| `[abc]` | Corresponde a qualquer caractere dentro dos colchetes (a, b ou c).           |
| `[^abc]`| Corresponde a qualquer caractere que não esteja dentro dos colchetes.          |
| `a|b`   | Corresponde a `a` ou `b`.                            |
| `()`    | Define um grupo de captura.                          |
| `*`     | Corresponde a zero ou mais ocorrências do caractere anterior.                 |
| `+`     | Corresponde a uma ou mais ocorrências do caractere anterior.                 |
| `?`     | Corresponde a zero ou uma ocorrência do caractere anterior.                 |
| `{n}`   | Corresponde exatamente a `n` ocorrências do caractere anterior.               |
| `{n,}`  | Corresponde a pelo menos `n` ocorrências do caractere anterior.             |
| `{n,m}` | Corresponde a pelo menos `n` e no máximo `m` ocorrências do caractere anterior. |

## TABELA PARA CARACTERES ESPECIAIS:
| Símbolo | Descrição                             |
| ------- | ------------------------------------- |
| `\`     | Escape - usado para escapar caracteres especiais.                 |
| `.`     | Ponto - corresponde a qualquer caractere exceto uma nova linha.                  |
| `^`     | Acento circunflexo - corresponde ao início de uma linha.                       |
| `$`     | Símbolo de dólar - corresponde ao final de uma linha.                          |
| `*`     | Asterisco - corresponde a zero ou mais ocorrências do caractere anterior.       |
| `+`     | Sinal de adição - corresponde a uma ou mais ocorrências do caractere anterior.  |
| `?`     | Ponto de interrogação - corresponde a zero ou uma ocorrência do caractere anterior. |
| `()`    | Parênteses - usado para definir grupos de captura.                           |
| `[]`    | Colchetes - usados para definir uma classe de caracteres.                      |
| `{}`    | Chaves - usadas para especificar o número exato ou o intervalo de repetições.  |
| `\|`    | Barra vertical - usado para alternância (OU) entre padrões.                    |
