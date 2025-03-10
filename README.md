# Maos-Unidas

Esse projeto se trata de um software universitário com o objetivo de auxiliar empresas e organizações no monitoramento, análise e gestão de práticas ambientais, sociais e de governança (ESG). O foco do cliente está na vertente Social, promovendo ONGs e aumentando sua visibilidade.

## Organização das Pastas

```
maos-unidas-app/
│── 📂 src/
│   ├── 📂 main/
│   │   ├── 📂 java/com/maosunidas/
│   │   │   ├── 📂 config/          # Configurações gerais (segurança, banco de dados)
│   │   │   ├── 📂 controllers/     # Controladores das rotas HTTP
│   │   │   ├── 📂 dto/             # Data Transfer Objects (DTOs)
│   │   │   ├── 📂 exceptions/      # Manipulação de erros e exceções
│   │   │   ├── 📂 models/          # Classes de modelo (Entidades)
│   │   │   ├── 📂 repositories/    # Interfaces do banco de dados (JPA)
│   │   │   ├── 📂 security/        # Configuração de autenticação e autorização
│   │   │   ├── 📂 services/        # Regras de negócio
│   │   │   ├── 📂 utils/           # Classes auxiliares e utilitárias
│   │   │   ├── Application.java    # Classe principal da aplicação
│   │   ├── 📂 resources/           # Arquivos de configuração (ex: application.yml)
│   │   ├── 📂 test/                # Testes unitários e de integração
│── 📂 frontend/                     # Aplicação Front-End (React, Vue ou Angular)
│   ├── 📂 public/                   # Arquivos estáticos
│   ├── 📂 src/                      # Código-fonte do Front-End
│   │   ├── 📂 assets/               # Imagens, ícones, fontes
│   │   ├── 📂 components/           # Componentes reutilizáveis
│   │   ├── 📂 pages/                # Telas principais do sistema
│   │   ├── 📂 services/             # Comunicação com API
│   │   ├── 📂 store/                # Gerenciamento de estado (Redux, Vuex)
│   │   ├── 📂 styles/               # Arquivos CSS/SASS
│   │   ├── App.js                   # Arquivo principal da aplicação
│   │   ├── index.js                 # Ponto de entrada
│── 📂 docs/                          # Documentação do projeto
│   ├── 📜 requisitos.md              # Requisitos funcionais e não funcionais
│   ├── 📜 arquitetura.md             # Definição da arquitetura do sistema
│   ├── 📜 API.md                     # Documentação das rotas da API
│── 📂 database/                      # Arquivos de configuração do banco de dados
│   ├── 📜 schema.sql                  # Estrutura do banco de dados
│   ├── 📜 seed.sql                    # Dados iniciais para popular o banco
│── 📂 deploy/                        # Configurações para deploy
│   ├── 📜 docker-compose.yml          # Configuração Docker para rodar a aplicação
│   ├── 📜 kubernetes.yaml             # Configuração para Kubernetes
│── 📂 tests/                         # Testes automatizados
│── 📜 README.md                      # Documentação geral do projeto
│── 📜 .gitignore                      # Arquivos ignorados pelo Git
│── 📜 pom.xml                         # Configuração do Maven para dependências
```

