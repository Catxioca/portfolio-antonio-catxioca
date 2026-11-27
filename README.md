# Portefólio — António Catxioca

Website estático (HTML, CSS e JavaScript num único ficheiro). **Não precisa de Node.js, de instalação de dependências, de build nem de ficheiros `.env`.**

## Conteúdo da pasta
| Ficheiro | Função |
|---|---|
| `index.html` | O website completo (páginas, estilos, scripts e fotografia incorporada) |
| `404.html` | Página de erro para endereços inexistentes |
| `robots.txt` | Permite a indexação pelos motores de busca |
| `_headers` | Cabeçalhos de segurança (Cloudflare Pages e Netlify) |
| `.gitignore` | Evita enviar ficheiros desnecessários ou segredos para o GitHub |
| `assets/documents/CV-Antonio-Catxioca-2027.pdf` | CV em PDF (botões «Descarregar CV» e «Visualizar CV») |
| `docs/` | Guias passo a passo |

## Começar (Windows, 2 minutos)
1. Extrai o ZIP. 2. Abre a pasta no VS Code (`code .`). 3. Faz duplo clique em `index.html`.

## Guias
1. `docs/01-windows-e-execucao.md` — preparar o PC, abrir e testar localmente
2. `docs/02-publicacao-github-cloudflare.md` — GitHub e publicação (com alternativas)
3. `docs/03-dominio.md` — domínio próprio, DNS e HTTPS
4. `docs/04-seo-e-configuracoes.md` — SEO, partilha, Google, CV, formulário
5. `docs/05-seguranca-manutencao.md` — segurança, backups, manutenção
6. `docs/06-checklist-testes.md` — checklist e resultados dos testes
7. `docs/07-variaveis-de-ambiente.md` — variáveis de ambiente (não há nenhuma)

## Como editar o conteúdo
Abre `index.html` no VS Code e usa Ctrl+F para encontrar o texto. Texto das secções fica em HTML; as competências (`var S`) e os projectos (`var P`) estão no bloco `<script>` no fim do ficheiro.

## Estado e limitações conhecidas
- O formulário abre o email ou o WhatsApp com a mensagem preenchida; não guarda mensagens num servidor.
- Os projectos de infraestrutura e de segurança e governança foram preenchidos com dados do CV e do LinkedIn. O projecto de Business Intelligence mostra só a descrição e as tecnologias.
- As páginas `#vendaja` e `#datatech` baseiam-se na descrição fornecida; os repositórios não foram verificados.

## Actualizar o CV
Substitui o ficheiro em `assets/documents/` mantendo o mesmo nome, e publica com `git add .`, `git commit` e `git push`.
