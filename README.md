# 🤖 Repositório de Automações (n8n)

Este repositório atua como um cofre de versionamento contínuo mantido de forma **100% autônoma**. Ele é alimentado por um fluxo interno do meu próprio servidor [n8n](https://n8n.io/) que faz a extração e o commit automático das automações diretamente via API.

## ⚙️ Propósito e Evolução
O objetivo principal deste repositório é documentar e criar um backup dinâmico do meu ambiente de automações. 

Os fluxos presentes aqui atualmente representam a estrutura fundacional do servidor (como o próprio fluxo que alimenta este backup e os monitores de estabilidade). O repositório servirá como um registro vivo, e automações mais robustas, complexas e integradas com Inteligência Artificial serão versionadas aqui naturalmente com o tempo.

## 🏗️ Ambiente de Execução
Os fluxos versionados aqui são construídos e executados em um ambiente self-hosted estruturado da seguinte forma:
* **Hospedagem:** Instância na Oracle Cloud Infrastructure (OCI).
* **Plataforma:** n8n rodando em container Docker.

## 📂 Como utilizar
Os arquivos dentro da pasta `workflows/` estão no formato padrão do n8n. Para utilizá-los na sua própria instância:
1. Abra o arquivo `.json` desejado no GitHub e copie o seu conteúdo bruto (Raw).
2. Vá para a tela em branco de um novo workflow no seu n8n.
3. Simplesmente cole (Ctrl+V ou Cmd+V) na tela, ou utilize a opção "Import from File".
4. Reconfigure os nós que exigem credenciais selecionando as contas correspondentes no seu próprio ambiente.
