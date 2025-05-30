# 🚀 Beta Launcher VSD

**Automatização de Manutenção de Totens de Autoatendimento – VideoSoft**

![Badge](https://img.shields.io/badge/Shell--Script-Automation-blue)  
![Badge](https://img.shields.io/badge/Status-Em%20Produção-success)  
![Badge](https://img.shields.io/badge/Linux-Debian%2FUbuntu-important)

---

## 📜 Descrição

O **Beta Launcher VSD** é uma ferramenta de automação desenvolvida em Shell Script para manutenção e gestão de totens de autoatendimento. Através de uma interface interativa no terminal Linux, permite executar as principais rotinas operacionais de forma rápida, segura e padronizada.

---

## 🚀 Funcionalidades

- ✔️ **Atualização do próprio launcher via GitHub**
- ✔️ **Backup automático da pasta `/opt/videosoft` antes de alterações**
- ✔️ **Atualização de URL de ambiente (Produção ou Homologação)**
- ✔️ **Limpeza de cache do Google Chrome**
- ✔️ **Limpeza de tokens e arquivos temporários**
- ✔️ **Verificação de status dos módulos:**
  - `vs-os-interface`
  - `vs-autopag-se`
- ✔️ **Reinício dos módulos diretamente via menu**
- ✔️ **Instalação e atualização dos módulos:**
  - `vs-autopag`
  - `vs-os-interface`
  - `iFood` (inclui `vsd-payment` e `pinpad-server`)
- ✔️ **Gestão de logs (visualizar e apagar)**
- ✔️ **Desinstalação do launcher**
- ✔️ **Validação automática de dependências**
- ✔️ **Interface aprimorada com UX para terminal:**
  - Cabeçalho informativo
  - Spinner de carregamento
  - Logs coloridos (verde, amarelo, vermelho, azul)

---

## 🖥️ Interface no Terminal

### 🎯 Menu Principal:

```

\========= 🎯 Ações Rápidas =========
1 - Atualizar beta-launcher
2 - Atualizar URL
3 - Limpar cache do Chrome

\========= 🔧 Manutenção =========
4 - Limpar token + cache
5 - Gerenciar módulos
6 - Verificar status dos módulos
7 - Reiniciar módulos

\========= 🗂️ Logs e Sistema =========
8 - Ver logs
9 - Apagar logs
10 - Info

\========= 🚪 =========
11 - Desinstalar launcher
12 - Sair

````

---

## 📦 Instalação

### 🔧 Pré-requisitos:

- Distribuições Linux Debian, Ubuntu ou derivados.
- Permissões de superusuário (sudo).

### 🚀 Instalar:

```bash
sudo wget -O /usr/bin/beta-launcher https://raw.githubusercontent.com/CarloseOldenburg/Beta-Laucher/refs/heads/main/beta-launcher
sudo chmod +x /usr/bin/beta-launcher
````

### ▶️ Executar:

```bash
sudo beta-launcher
```

---

## 📂 Logs

Todos os registros ficam armazenados em:

```
/var/log/beta-launcher.log
```

---

## 💡 Benefícios

* 🚀 **Agilidade nas manutenções**
* 📦 **Padronização dos processos**
* 🔐 **Segurança com backups automáticos**
* 💻 **Fácil utilização com interface amigável no terminal**
* ⚙️ **Ferramenta leve, rápida e escalável**

---

## 🤝 Contribuições

Sinta-se à vontade para abrir issues, enviar pull requests ou sugerir melhorias.

---

## 🧠 Licença

Este projeto está sob licença **MIT**.

---

## 👤 Autor

Desenvolvido por [Carlos Eduardo Oldenburg](https://github.com/CarloseOldenburg)
Colaboração e fonte do launcher por [Wilker Santos](https://github.com/wilker-santos)

---

## 📜 Licença

Distribuído sob licença livre para uso interno corporativo e manutenção de terminais com sistemas VideoSoft.

