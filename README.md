# ADR-002 – Arquitetura Hexagonal

## Contexto
O backend precisa ser modular, testável e preparado para evolução.

## Decisão
Adotar arquitetura hexagonal com:
- Domain
- Application (use cases)
- Adapters (REST, Kafka, DB)
- Infrastructure

## Consequências
- Testes mais simples
- Baixo acoplamento
- Facilidade para trocar frameworks
