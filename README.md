# HSG — Hyper Script Generator

**Repositório oficial do projeto HSG**

## 📋 Sobre

O **HSG (Hyper Script Generator)** é uma ferramenta avançada para geração e gestão de scripts HMP (Hyper Meta Programming) no ecossistema OPENBOT. Permite criar, organizar e executar scripts de forma eficiente.

## 🚀 Funcionalidades

- **Geração de Scripts HMP** — Cria scripts HMP automaticamente
- **Gestão de Scripts** — Organiza, lista e elimina scripts
- **Execução Segura** — Executa scripts com ledger auditável
- **Integração com HVM** — Compatível com Hyper Virtual Machine
- **Pipeline B4** — Suporte para pipeline cognitivo de 3 camadas

## 📁 Estrutura do Projeto

```
HSG/
├── README.md          # Este ficheiro
├── docs/              # Documentação completa
│   ├── index.md       # Índice da documentação
│   ├── instalacao.md  # Guia de instalação
│   ├── uso.md         # Guia de utilização
│   ├── api.md         # Referência da API
│   └── exemplos.md    # Exemplos práticos
├── scripts/           # Scripts HMP de exemplo
└── src/               # Código fonte
```

## ⚡ Instalação Rápida

```bash
# Clonar o repositório
git clone https://github.com/RokoOfficial/HSG.git
cd HSG

# Instalar dependências (se aplicável)
# npm install  ou  pip install -r requirements.txt
```

## 🛠️ Como Usar

### Gerar um script HMP

```hmp
HSG.GENERATE(
  name: "meu-script",
  description: "Script de exemplo",
  code: """
    SET mensagem = "Olá, HSG!"
    PRINT mensagem
  """
)
```

### Executar um script

```hmp
HSG.RUN(
  script: "meu-script",
  mode: "secure"
)
```

## 📚 Documentação

A documentação completa está disponível na pasta `docs/`:

| Documento | Descrição |
|-----------|-----------|
| [docs/index.md](docs/index.md) | Índice geral |
| [docs/instalacao.md](docs/instalacao.md) | Guia de instalação detalhado |
| [docs/uso.md](docs/uso.md) | Guia de utilização |
| [docs/api.md](docs/api.md) | Referência completa da API |
| [docs/exemplos.md](docs/exemplos.md) | Exemplos práticos |

## 🔗 Integrações

- **OPENBOT** — Plataforma principal
- **HVM** — Hyper Virtual Machine
- **AgenteB4** — Agente cognitivo HMP
- **AutoFlux** — Motor de paralelismo

## 📄 Licença

Este projeto está sob a licença MIT.

---

**HSG v2.0** — Desenvolvido para o ecossistema OPENBOT
