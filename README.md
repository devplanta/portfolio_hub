# 📁 Portfolio Hub

Repositório do **Bootcamp I – Etapa Final**, criado para reunir, organizar e versionar os projetos e materiais acadêmicos da minha formação.

🌐 **Site (GitHub Pages):** https://devplanta.github.io/portfolio_hub/

---

## 📌 Sobre o projeto

O Portfolio Hub é um repositório público no GitHub com uma página web estática que dá acesso aos materiais de cada matéria. Ele foi desenvolvido para praticar:

- versionamento de código com **Git**;
- hospedagem e compartilhamento com **GitHub**;
- publicação de site estático com **GitHub Pages**;
- documentação com **README.md**.

## 🗂️ Estrutura do repositório

```
portfolio_hub/
├── index.html                  # Página principal (GitHub Pages)
├── css/
│   └── style.css               # Estilos da página
├── Engenharia de Software/     # Aulas, Socrative e resumo
├── Lógica de programação/      # Aulas e listas de exercícios
├── .gitignore
└── README.md
```

## 📚 Conteúdo por matéria

### Engenharia de Software
| Material | Quantidade |
|---|---|
| Aulas (01 a 03) | 3 PDFs |
| Questionários Socrative (aulas 1 a 3) | 3 PDFs |
| Resumo da disciplina | 1 PDF |

### Lógica de Programação
| Material | Quantidade |
|---|---|
| Aulas (01 a 06) | 6 PDFs |
| 1ª lista de exercícios | 1 PDF |
| 1ª lista de exercícios (Portugol WebStudio) | 1 PDF |

## 🛠️ Tecnologias utilizadas

- **HTML5** – estrutura da página
- **CSS3** – layout responsivo (Grid e Flexbox)
- **Git** e **GitHub** – versionamento e hospedagem
- **GitHub Pages** – publicação do site

## ▶️ Como visualizar

**Online:** acesse o link do site no topo deste arquivo.

**Localmente:**

```bash
git clone https://github.com/devplanta/portfolio_hub.git
cd portfolio_hub
# abra o arquivo index.html no navegador
```

## 🔖 Versões

| Versão | Descrição |
|---|---|
| **v1.0** | Primeira versão do site, com as matérias de Engenharia de Software e Lógica de Programação |

## 👩‍💻 Autora

**Maria Fernanda Melo**
GitHub: [@devplanta](https://github.com/devplanta)

## Planejamento da implantação

A etapa final evolui a versão existente, mantendo HTML e CSS e os 15 materiais.

1. Revisar a estrutura e preparar os ajustes na branch `feature/etapa-final`.
2. Corrigir a largura da grade em telas pequenas e melhorar o acesso por teclado.
3. Documentar publicação, acesso e práticas de segurança.
4. Abrir um pull request para `main` e conferir as alterações antes do merge.
5. Aguardar a publicação e executar os testes abaixo.
6. Reunir evidências no relatório e apresentar o resultado em vídeo.

## Publicação e controle de acesso

As capturas fornecidas em 24/10/2026 mostram o Pages configurado para publicar
pela branch `main`, pasta `/ (root)`, no endereço informado acima, com HTTPS
obrigatório no domínio padrão. Mostram também repositório público e nenhum
colaborador convidado, com escrita direta restrita à proprietária.

O site é público. A permissão para alterar o repositório é diferente da permissão
para consultar o site. O projeto não implementa login nem área privada.
Mudanças na configuração devem ser registradas com novas evidências.

## Segurança

- Manter autenticação de dois fatores na conta e guardar os códigos de recuperação em local privado. A ativação ainda precisa ser verificada; não publicar os códigos.
- Não incluir senhas, tokens, arquivos de ambiente ou dados pessoais nos commits.
- Revisar o conteúdo dos PDFs e a autorização para compartilhá-los antes de publicar.
- Conceder escrita somente a pessoas que realmente precisem colaborar e revisar os acessos periodicamente.
- Conferir os arquivos alterados antes de integrar na branch principal.
- Os links que abrem novas abas utilizam `rel="noopener"`.

Essas orientações são políticas do projeto; não comprovam, por si só, que todas
as configurações de segurança da conta estejam ativadas.

## Fluxo de contribuição

Criar uma branch a partir de `main`, fazer alterações com commits descritivos e
abrir um pull request explicando o problema, a solução e a validação. Conferir o
diff antes de integrar. Em trabalho individual, a conferência pela própria autora
não equivale à aprovação independente de outro colaborador.

Exemplo de mensagem de commit:

`feat: prepara etapa final com acessibilidade e documentação da implantação`

Se houver falha após uma atualização, reverter o commit responsável e acompanhar
a nova publicação. Não é necessário apagar o histórico.

## Plano de testes e evidências

Os itens abaixo estão pendentes de execução; preencher o resultado real.

| Verificação | Procedimento | Situação |
|---|---|---|
| Página publicada | Abrir a URL pública após o deploy | Pendente |
| Materiais | Abrir cada um dos 15 PDFs e conferir o conteúdo | Pendente |
| Navegação | Usar Sobre, Matérias, Contato e a logo | Pendente |
| Teclado | Usar Tab, verificar o foco e ativar Pular para o conteúdo | Pendente |
| Telas pequenas | Conferir 320, 375 e 768 px, sem rolagem horizontal | Pendente |
| Desktop | Conferir o layout em 1280 px | Pendente |
| Movimento reduzido | Ativar a preferência do sistema e verificar a navegação | Pendente |
| Publicação | Conferir execução bem-sucedida em Actions após o merge | Pendente |

Guardar capturas do site, Pages, acessos, commits, pull request e testes, além
das conversas relevantes com o Gemini. Não capturar segredos ou códigos de recuperação.

## Apoio de inteligência artificial

O Google Gemini foi consultado para propor o planejamento da implantação,
segurança, colaboração e testes. A resposta foi revisada criticamente: uma versão
no rodapé não comprova o histórico do Git, e a tag viewport não comprova a
responsividade. O ChatGPT auxiliou na análise do código e preparação dos ajustes
e da documentação. As decisões e a validação final cabem à autora.

## Evolução v1.1

Preparação da etapa final: grade adaptável a telas estreitas, foco visível,
atalho para o conteúdo, respeito à preferência por movimento reduzido e
documentação de implantação, segurança e testes. A publicação desta versão
somente estará concluída após o merge e a execução bem-sucedida do Pages.
