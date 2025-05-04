# EcoLife API

[![CI/CD](https://github.com/yourusername/ecolife-api/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/yourusername/ecolife-api/actions)

Sürdürülebilir yaşam için backend API (Python/Flask)

## Özellikler
- REST & GraphQL API
- JWT Kimlik Doğrulama
- Tarif ve Karbon Ayak İzi Yönetimi
- Redis Caching
- Celery Arka Plan Görevleri

## Kurulum

```bash
git clone https://github.com/yourusername/ecolife-api.git
cd ecolife-api

# Geliştirme ortamı
make dev-up

# Production
docker-compose -f infra/docker-compose.prod.yml up
