# 📜 Gerador de Hashes de Arquivos (MD5, SHA1, SHA256)

Este é um **script Bash** que gera os **hashes** MD5, SHA1 e SHA256 de qualquer arquivo, incluindo imagens, documentos e binários. Ele é útil para **verificar a integridade** de arquivos e detectar alterações.

## 📌 Como funciona?
O script recebe um arquivo como argumento e retorna os seguintes hashes:
- **MD5** 🔹 (`md5sum`)
- **SHA1** 🔹 (`sha1sum`)
- **SHA256** 🔹 (`sha256sum`)

## 📥 Instalação
Nenhuma instalação é necessária, pois o script usa comandos nativos do Linux. Apenas **clone o repositório** e conceda permissão de execução ao script:

```bash
# Clone o repositório
git clone https://github.com/Jugolino/gerador-de-hashes.git

# Entre na pasta do projeto
cd gerador-de-hashes

# Dê permissão de execução ao script
chmod +x calcular_hashes.sh
