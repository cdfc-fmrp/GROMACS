# 🧬 Pipeline Interativo - Gromacs com GPU e Containers

Interface web interativa que apresentar as etapas para configurar e executar simulações de dinâmica molecular com **GROMACS**, utilizando containers Docker em difeentes ambientes computacionais.


## 🌐 Acesse a interface interativa

### 🚀 [CLIQUE AQUI PARA ABRIR A INTERFACE](https://cdfc-fmrp.github.io/GROMACS/)

Acesse diretamente pelo navegador, sem necessidade de instalação.

## 📋 Objetivo

Demonstrar uma solução reprodutível e portátil para executar simulações em diferentes infraestruturas:

- **Google Cloud L4:** testes e validação.
- **Google Cloud A100**: processamento de produção.
- **Servidor local (on-premises)**: execução em GPU NVIDIA Blackwell.

O uso de containers facilita a portabilidade do ambiente, reduzindo problemas de compatibilidade entre sistemas. Cada plataforma requer validação de drivers, CUDA e suporte à GPU.


## 📂 Estrutura do repositório

```text
GROMACS/
├── index.html
└── README.md
```
---

**Centro de Desenvolvimento e Formação Continuada em Informática Biomédica (CDFC IBm-FMRP)**

Faculdade de Medicina de Ribeirão Preto — Universidade de São Paulo (USP)
