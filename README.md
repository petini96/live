# Live Dev Full Cycle - Acompanhamento

Este projeto é um exemplo prático de implementação de endpoints em Golang utilizando a arquitetura hexagonal (ports & adapters) com integrações Apache Kafka, HTTP e MySQL.

## Tecnologias Utilizadas

- Golang
- Apache Kafka
- MySQL
- Docker
- ...

## Estrutura do Projeto

A estrutura do projeto segue a arquitetura hexagonal, com divisão clara entre camadas de aplicação, infraestrutura e domínio.

- `cmd/`: Contém o ponto de entrada da aplicação.
- `internal/`: Contém os pacotes internos, incluindo as implementações dos casos de uso, interfaces, repositórios, etc.
- `pkg/`: Contém pacotes reutilizáveis que podem ser usados em outros projetos.
- `docker/`: Contém os arquivos de configuração Docker.
- `...
 