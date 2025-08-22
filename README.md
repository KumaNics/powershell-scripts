# Powershell Scripts

Bem-vindo ao repositório de Scripts PowerShell!
Este espaço é dedicado a abrigar uma coleção de scripts úteis e prontos para uso, projetados para automatizar tarefas e simplificar processos no ambiente Windows.

## 📜 Sobre o Repositório

O objetivo principal deste repositório é fornecer soluções práticas através de scripts PowerShell para diversas necessidades, desde a administração de sistemas até a automação de tarefas do dia a dia.

## 📂 Conteúdo Atual

### Certificados A1 - Assinatura

Esta pasta contém scripts desenvolvidos para gerenciar e interagir com certificados digitais do tipo A1.

* **`VALIDA LICENÇAS A1`**: Um script para verificar a existencia de certificados A1, ideal para manutenção e gestão de ambientes que utilizam assinaturas digitais.
* **`COMPILA CERTIFICADO A1`**: Um script para compilar todos os ".CSV" gerados pelo **`VALIDA LICENÇAS A1`**, ideal para visualização dos resultados.
* **`COPIA RELATORIO`**: Um script para copiar o relatório gerado pelo script **`COMPILA CERTIFICADO A1`** e encaminha a cópia a outro diretório.
* **`COMPILA.BAT`**: Um script .BAT para execução do **`COMPILA CERTIFICADO A1`** via **`AGENDADOR DE TAREFAS`**.

## 🚀 Como Usar

1.  **Clone o repositório:**
    ```sh
    git clone [https://github.com/KumaNics/powershell-scripts.git](https://github.com/KumaNics/powershell-scripts.git)
    ```
2.  **Navegue até a pasta do script desejado:**
    ```sh
    cd powershell-scripts/"CERTIFICADOS A1 - ASSINATURA"
    ```
3.  **Execute o script:**
    Abra o PowerShell como administrador e execute o script desejado. Certifique-se de ler o conteúdo do script para entender seu funcionamento antes da execução.

    Exemplo:
    ```powershell
    .\seu-script.ps1
    ```

## 🤝 Contribuições

Contribuições são bem-vindas!
Se você tiver um script que gostaria de adicionar ou uma melhoria para um script existente, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
