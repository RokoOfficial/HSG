# ⚙️ Guia de Instalação — HSG

## Pré-requisitos

- **OPENBOT** v6.0 ou superior
- **HVM** (Hyper Virtual Machine) instalado
- Acesso ao **GitHub** (opcional, para clonar)

## Método 1: Instalação via OPENBOT Store

1. Abra o OPENBOT
2. Vá para **Store** → **Dev Tools**
3. Procure por **HSG**
4. Clique em **Instalar**

## Método 2: Instalação Manual

### Clonar o Repositório

```bash
git clone https://github.com/RokoOfficial/HSG.git
cd HSG
```

### Configurar Variáveis de Ambiente

```bash
export HSG_HOME="$(pwd)"
export PATH="$PATH:$HSG_HOME/bin"
```

### Verificar Instalação

```bash
hsg --version
# Output esperado: HSG v2.0.0
```

## Método 3: Integração com OPENBOT

Se já tem o OPENBOT em execução:

```hmp
HSG.INSTALL(
  source: "github",
  repo: "RokoOfficial/HSG",
  branch: "main"
)
```

## Verificação Pós-Instalação

```bash
# Listar scripts disponíveis
hsg list

# Verificar dependências
hsg check
```

## Resolução de Problemas

| Problema | Solução |
|----------|---------|
| `hsg: command not found` | Verifique o PATH |
| Erro de permissão | Use `chmod +x` nos binários |
| Dependências em falta | Execute `hsg setup` |

---

*Documentação gerada automaticamente pelo OPENBOT*
