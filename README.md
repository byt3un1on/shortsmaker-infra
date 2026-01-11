# Shortsmaker Infra

Este repositório contém os manifestos para os serviços de infraestrutura do sistema Shortsmaker.

## Serviços

- **Postgres:** Banco de dados relacional.
- **Minio:** Object Storage (S3 compatível) para armazenar arquivos de mídia.
- **Wiremock:** Simulador de APIs para as IAs de roteiro e vídeo.

## Como rodar

```bash
docker compose up -d
```
