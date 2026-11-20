# TributoClaro — Canal Oficial de Releases (Windows Portátil)

Calculadora da Reforma Tributária do Consumo (**LC 214/2025**) para contadores e escritórios, construída sobre os motores de cálculo oficiais da **Receita Federal do Brasil**.

Edição portátil para **Windows 10 e 11 (64-bit)**: **sem Docker, sem Java e sem instalação**.

---

## 🚀 Como Iniciar em 4 Passos

1. **Baixe o pacote completo:**  
   Vá na aba [Releases](https://github.com/mailsonm/tributoclaro-releases/releases/latest) e baixe o arquivo **`TributoClaro-win-x64.zip`**.
2. **Extraia os arquivos:**  
   Descompacte toda a pasta em um local permanente do seu computador (recomendado: `C:\TributoClaro\`).
3. **Inicie o sistema:**  
   Dê um duplo-clique em **`Iniciar TributoClaro.bat`**.  
   *(Opcional: use `Criar Atalho na Area de Trabalho.bat` para ter o ícone na sua área de trabalho).*
4. **Navegador automático:**  
   Na primeira inicialização, os motores levam entre 10 e 20 segundos para carregar as tabelas da LC 214/2025. Assim que estiver pronto, seu navegador (Chrome/Edge) abrirá automaticamente.

> **💡 Aviso do Windows Defender / SmartScreen:**  
> Por ser um pacote portátil sem assinatura digital comercial cara da Microsoft, na primeira execução do componente `danfse-service.exe` o Windows pode exibir uma tela azul de aviso. Basta clicar em **"Mais informações"** ➔ **"Executar assim mesmo"**.

---

## 🔑 Ativação da Licença

Na primeira vez que você abrir o sistema no navegador:

1. A tela exibirá o seu **Código da Máquina** (exemplo: `TC-A1B2-C3D4-E5F6`).
2. Clique no botão **"Copiar Código da Máquina"** e envie para quem forneceu o software.
3. Cole a chave de ativação recebida (começando com `TC1...`) e clique em **"Ativar Licença"**.
4. Sua chave ativada fica salva em `%LOCALAPPDATA%\TributoClaro\license.key` e permanece válida mesmo após futuras atualizações.

---

## 💾 Onde ficam salvos seus dados (Backup & Segurança)

O cadastro de clientes, simulações salvas e perfil do escritório **não** ficam dentro da pasta do programa. Eles são gravados de forma isolada e segura em:
- **Banco de dados:** `%LOCALAPPDATA%\TributoClaro\tributoclaro.db`
- **Licença:** `%LOCALAPPDATA%\TributoClaro\license.key`

* **Como fazer backup:** Clique com o botão direito no ícone do TributoClaro perto do relógio (bandeja do sistema) ➔ **"Abrir Pasta de Dados (Backup)"** e guarde uma cópia do arquivo `tributoclaro.db`.
* **Atualizações:** Ao atualizar o TributoClaro, seus dados e sua licença **nunca** são sobrescritos.

---

## 🛑 Como Encerrar com Segurança

* **Pela bandeja:** Clique com o botão direito no ícone verde **TC** perto do relógio ➔ **"Encerrar TributoClaro"**.
* **Ou por atalho:** Dê um duplo-clique em **`Parar TributoClaro.bat`**.

---

## 📦 O que é cada arquivo das Releases?

| Arquivo | Descrição |
| :--- | :--- |
| **`TributoClaro-win-x64.zip`** | **Pacote Completo (Baixe este)**: JRE 21 embutida, motores oficiais RFB e aplicação pronta. |
| **`TributoClaro-win-x64-app-delta.zip`** | **Atualização Leve**: Utilizado exclusivamente pelo auto-updater interno do sistema. |
| **`latest.json`** | Manifesto consultado pelo TributoClaro para checar novas versões. |
| **`SHA256SUMS.txt`** | Checksums para verificação de integridade dos arquivos. |

---

### Licenças de Terceiros e Motores Oficiais
Os motores de cálculo da CBS, IBS e DANFSe são derivados dos repositórios oficiais da **Receita Federal do Brasil** sob licença **MIT**. Os créditos completos e termos de código aberto constam no arquivo `THIRD-PARTY-LICENSES.txt` dentro do pacote.
