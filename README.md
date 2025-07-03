# API Estática de Dados de Redes Sociais

Este repositório serve como uma API estática (backend-less) para fornecer dados sobre interações em redes sociais. O projeto foi desenvolvido para ser a fonte de dados de um [site de relatórios de redes sociais](https://sergiocalazans.github.io/analise-de-dados/index.html).

O sistema utiliza o **GitHub Pages** para hospedar arquivos JSON estáticos, que funcionam como endpoints da API. As atualizações no repositório são automaticamente publicadas através de um workflow do **GitHub Actions**.

## Como Funciona

Os dados são armazenados em arquivos `.json` na pasta `/data`. Quando qualquer alteração é enviada para a branch `main`, uma ação do GitHub (GitHub Action) é acionada para implantar o conteúdo do repositório no GitHub Pages. Isso torna os arquivos JSON publicamente acessíveis através de URLs específicas, permitindo que qualquer aplicação front-end (ou outro serviço) os consuma como se fossem endpoints de uma API tradicional.

## Endpoints da API (Dados Disponíveis)

Abaixo estão os links diretos para os arquivos JSON hospedados no GitHub Pages. Estes são os "endpoints" que seu projeto front-end deve consumir.

### 📊 Dados de Acessos
Registros de acessos.

*   **URL do Endpoint:**
    [`https://sergiocalazans.github.io/api-redes-sociais/data/dados-globais.json`](https://sergiocalazans.github.io/api-redes-sociais/data/dados-globais.json)

### 📝 Dados do Número de Acessos 
Informações sobre os acessos de cada rede social usada.

*   **URL do Endpoint:**
    [`https://sergiocalazans.github.io/api-redes-sociais/data/numero-acessos.json`](https://sergiocalazans.github.io/api-redes-sociais/data/numero-acessos.json)

### 👥 Dados das Redes Favoritas
Lista de redes sociais favoritas.

*   **URL do Endpoint:**
    [`https://sergiocalazans.github.io/api-redes-sociais/data/redes-favoritas.json`](https://sergiocalazans.github.io/api-redes-sociais/data/redes-favoritas.json)

### 👥 Dados da Pesquisa
Lista dos dados extraídos da pesquisa.

*   **URL do Endpoint:**
    [`https://sergiocalazans.github.io/api-redes-sociais/data/redes-sociais-escola.json`](https://sergiocalazans.github.io/api-redes-sociais/data/redes-sociais-escola.json)

## Como Contribuir

Para adicionar ou atualizar dados:
1.  Faça um fork deste repositório.
2.  Edite os arquivos JSON na pasta `/data`.
3.  Abra um Pull Request com suas alterações.

## 📜 Licença

Este projeto está licenciado sob a **Licença MIT**.

Isso significa que você tem total liberdade para usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias deste software, tanto para projetos pessoais quanto comerciais, contanto que o aviso de copyright original e o texto da licença sejam mantidos.

Para ler os termos completos, consulte o arquivo [LICENSE](LICENSE) neste repositório.
