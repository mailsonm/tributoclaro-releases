# TributoClaro — Canal Oficial de Releases (Windows Portátil)

Este repositório público hospeda **exclusivamente** os pacotes compilados, atualizações em delta e manifestos verificados por assinatura **SHA-256** do **TributoClaro** (*Calculadora da Reforma Tributária — LC 214/2025*).

> **Importante:** Este canal não contém código-fonte; ele existe para permitir o download direto dos executáveis e a atualização automática com 1 clique no Windows dos escritórios de contabilidade, sem exigir tokens de autenticação na máquina do usuário.

## Artefatos publicados em cada versão

| Arquivo | Uso |
| :--- | :--- |
| `TributoClaro-win-x64.zip` | Pacote completo portátil para primeira instalação (JRE 21 `jlink`, motores oficiais RFB MIT, Node 24, BFF e SPA). |
| `TributoClaro-win-x64-app-delta.zip` | Atualização rápida (apenas aplicação/interface/lançador) quando os motores da Receita Federal e runtimes não mudam. |
| `latest.json` | Manifesto de versão consumido pelo atualizador automático do TributoClaro. |
| `SHA256SUMS.txt` | Assinaturas criptográficas SHA-256 para validação de integridade. |

## Como instalar (Windows 10/11 x64)

1. Baixe `TributoClaro-win-x64.zip` na aba **Releases**.
2. Descompacte em uma pasta fixa (por exemplo: `C:\TributoClaro\`).
3. Dê um duplo-clique em `Iniciar TributoClaro.bat`.

Seus cadastros de empresas, histórico de simulações e perfil do escritório são salvos com segurança fora da pasta do programa, em `%LOCALAPPDATA%\TributoClaro\tributoclaro.db`.
