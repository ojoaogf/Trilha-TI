# Guia de Comandos Git Atualizado

**Dev, versionar seu código com mais segurança, produtividade e confiança começa aqui.** 👉

## 🚀 Configurando seu projeto com Git

Seja iniciando um repositório do zero ou clonando um existente, estes comandos são essenciais para começar a versionar desde o primeiro commit:

```bash
git init                                    # Inicia um repositório Git
git clone <url>                             # Clona um repositório remoto
git config --global user.name "Seu Nome"   # Configura nome globalmente
git config --global user.email "seu@email.com"  # Configura email globalmente
```

## 📝 Registrando seu progresso com clareza

Mantenha um histórico limpo e fácil de rastrear. Saiba como adicionar, revisar e salvar alterações de forma organizada:

```bash
git status                          # Verifica arquivos modificados
git add .                           # Adiciona todos os arquivos à staging
git commit -m "mensagem"            # Salva o progresso com descrição
git restore <arquivo>               # Desfaz mudanças antes do commit
```

## 🌿 Trabalhando com branches sem misturar tudo

Isole features, teste ideias e corrija bugs sem quebrar o projeto principal. As branches são suas aliadas no fluxo de trabalho moderno:

```bash
git branch                          # Lista todas as branches
git checkout -b nova-feature        # Cria e entra em uma nova branch
git switch main                     # Troca para a branch 'main'
git merge feature                   # Une uma branch à atual
```

## 🌐 Conecte seu projeto ao mundo

Envie seu código para o GitHub, GitLab ou Bitbucket e comece a colaborar com times, ferramentas de CI/CD e muito mais:

```bash
git remote add origin <url>         # Conecta com repositório remoto
git push origin main                # Envia para a branch main
git pull origin main                # Atualiza com mudanças do remoto
```

## 🔍 Entenda o que mudou, quando e por quê

Tenha visibilidade total sobre o histórico do projeto, compare versões e identifique autores de cada linha de código:

```bash
git log                             # Histórico detalhado
git log --oneline                   # Versão simplificada
git diff                            # Vê o que mudou
git blame <arquivo>                 # Mostra quem alterou cada linha
```

## 🧹 Mantenha o repositório limpo e funcional

Evite acúmulo de arquivos inúteis, limpe o ambiente de trabalho e mantenha a produtividade com comandos que salvam o dia:

```bash
git stash                           # Guarda alterações temporariamente
git stash pop                       # Recupera alterações salvas
git clean -fd                       # Remove arquivos não rastreados
```

## 🚨 Cometeu um erro? Sem pânico!

Corrija mensagens, recupere alterações ou reescreva commits com confiança. O Git oferece controle total sobre o que vai pro histórico:

```bash
git commit --amend                  # Edita o último commit
git reset --soft HEAD~1             # Volta o commit, mantém mudanças
git reset --hard HEAD~1             # Volta o commit e descarta tudo
```

---

## 💡 Dicas Importantes

- **Sempre verifique o status** antes de fazer commits com `git status`
- **Use mensagens descritivas** nos commits para facilitar o rastreamento
- **Trabalhe com branches** para isolar funcionalidades e correções
- **Faça backups regulares** com `git push` para repositórios remotos
- **Não entre em pânico** - o Git permite reverter quase qualquer ação

## 🔗 Recursos Adicionais

- [Documentação oficial do Git](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [GitLab Documentation](https://docs.gitlab.com/)
- [Bitbucket Tutorials](https://www.atlassian.com/git/tutorials)

**Comece a versionar com confiança e transforme sua produtividade no desenvolvimento!** 🚀
