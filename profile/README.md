# FIAP - Software Architect

## Utilitários

- [Miro](https://miro.com/app/board/uXjVHZouAEk=/)
- [Figma](https://www.figma.com/board/wx7kmepPOFfWmXFR4geq0m/FIAP?node-id=0-1&t=L0gnz3Jyn21QlNyT-1)

## Tech-Challenges

### Fase 1

> [PDF](../tech-challenges/phase-1.pdf)

#### Resumo

**Arquitetura e Design**

- Back-end monolítico com arquitetura em camadas
- Aplicação de Domain-Driven Design (DDD)
- Event Storming dos fluxos principais

**APIs e Documentação**

- APIs RESTful
- Documentação via Swagger ou similar
- Endpoints para CRUD de clientes, veículos, serviços e peças
- API pública para acompanhamento de OS pelo cliente

**Segurança**

- Autenticação JWT nas APIs administrativas
- Validação de dados sensíveis (CPF/CNPJ, placa de veículo)
- Relatório de análise de vulnerabilidades (scan de código)

**Banco de Dados**

- Livre escolha, mas com justificativa da decisão

**Infraestrutura**

- Dockerfile para build da aplicação
- docker-compose.yml para orquestrar o ambiente completo

**Qualidade e Testes**

- Testes unitários e de integração nos fluxos principais
- Cobertura mínima de 80% nos domínios críticos

**Repositório e Entrega**

- Repositório privado com acesso ao usuário `soatarchitecture`
- README.md completo com instruções de uso
- Vídeo demonstrativo de até 15 minutos
- Documentação DDD (Miro ou equivalente)
- Documento de entrega em PDF com dados do grupo e links

## Meeting Notes

- [17/05/2026](../meetings/2026-05-17.md) Primeira reunião com toda a equipe para falar sobre o projeto.
- [24/05/2026](../meetings/2026-05-24.md) Mapeamento dos sub-domínios
