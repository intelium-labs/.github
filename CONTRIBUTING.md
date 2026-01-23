# Contribuindo com o Intelium Labs

Obrigado pelo interesse em contribuir! 🎉

---

## 📋 Como Participar

### 🐛 Reportar Bugs

Encontrou um problema em algum lab?

1. Verifique se o bug já foi reportado nas [Issues](https://github.com/orgs/intelium-labs/repositories)
2. Abra uma nova Issue usando o template **"🐛 Bug Report"**
3. Inclua logs do `docker-compose logs`
4. Descreva seu ambiente (OS, Docker version)

### 💡 Sugerir Labs

Tem uma ideia para um novo lab?

1. Abra uma Issue usando o template **"💡 Sugestão de Lab"**
2. O lab deve utilizar nossa stack atual:
   - Apache Kafka, Confluent Platform, Apache Flink
   - Trino, Lenses.io, Schema Registry
   - Python, SQL, Docker

### 💬 Discussões

Para outros assuntos, use nossas [Discussions](https://github.com/orgs/intelium-labs/discussions):

- Dúvidas sobre os labs
- Sugestões de novas ferramentas (serão avaliadas pelo time)
- Compartilhar implementações
- Conversas gerais sobre streaming e dados

---

## 🔒 Pull Requests

> **Nota:** No momento, Pull Requests com novas features são desenvolvidos exclusivamente pelo time Intelium.

### PRs Aceitos da Comunidade

- ✅ Correções de typos e documentação
- ✅ Melhorias em READMEs
- ✅ Correções de bugs reportados

### PRs Exclusivos do Time Intelium

- 🔒 Novos labs
- 🔒 Novas features
- 🔒 Mudanças estruturais

---

## 📝 Padrões

### Commits

Usamos commits semânticos em português:
```
Add: nova funcionalidade
Fix: correção de bug
Docs: atualização de documentação
Refactor: refatoração de código
```

### Docker Compose

- Labs devem subir com `docker-compose up -d`
- Inclua healthchecks nos serviços
- Use versões fixas de imagens
- Documente portas e acessos no README

---

## ❓ Dúvidas?

- 📖 Leia a documentação do lab
- 💬 Abra uma [Discussion](https://github.com/orgs/intelium-labs/discussions)
- 🌐 Visite [intelium.ai](https://intelium.ai)

---

**Obrigado por fazer parte da comunidade Intelium Labs!** 🚀