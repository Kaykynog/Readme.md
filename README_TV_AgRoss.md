
# 🎥 TV AgRoss - Painel de Sorteios Interativos

Projeto em desenvolvimento para a empresa **AgRoss**, voltado ao gerenciamento de **sorteios e premiações** em transmissões de TV ao vivo. O sistema permite controlar diferentes tipos de sorteios com interface interativa e painel de administração.

---

## 🌐 Acesso Rápido

- 🔗 Frontend (dev): [http://5.161.234.4:8085](http://5.161.234.4:8085)
- 📺 Vídeo demonstração: [YouTube - TV AgRoss](https://www.youtube.com/watch?v=afmWwZp5MSY)
- 🌐 Novo domínio previsto: `tvdash.websiteds.com.br`

---

## ⚙️ Tecnologias Utilizadas

### Backend
- Laravel (PHP)
- API REST
- PostgreSQL

### Frontend
- Interface web responsiva (em desenvolvimento)

### Infraestrutura
- VPS Hertzner
- Ambiente de produção: IP `5.161.234.4`

---

## 🧩 Funcionalidades Principais

- **Sorteio NF Premiada**  
  Sorteios com base em notas fiscais cadastradas

- **Palpite Premiado**  
  Sistema de quiz com seleção de respostas corretas e premiação

- **Painel Super ADM**  
  Administração completa do sistema (cadastros, relatórios, etc.)

- **Histórico de Premiações**  
  Consulta de sorteios anteriores

- **Sorteios Múltiplos**  
  - 1 a 4 vencedores: bingueira (sorteio com bolas)  
  - 5+ vencedores: roleta online ([agross.com.br/roleta](https://agross.com.br/roleta))

---

## 🛠️ Instalação (Ambiente Local)

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/tv-agross.git
cd tv-agross

# Instalar dependências
composer install

# Copiar variáveis de ambiente
cp .env.example .env

# Gerar chave da aplicação
php artisan key:generate

# Rodar migrations
php artisan migrate
```

---

## 🗃️ Banco de Dados

- Banco: PostgreSQL
- Migrations criadas e atualizadas
- Diagrama: [dbdiagram.io](https://dbdiagram.io/d/685ac295f413ba3508a63c93)

**Principais Tabelas:**
- `usuarios`
- `sorteios`
- `participantes`
- `premiacoes`
- `configuracoes`

---

## 📡 Documentação da API

- Gist com os endpoints mapeados:  
  [https://gist.github.com/FelipeMFx/b7cb23b2ec6b1e3a2006c32bf9c3da4d](https://gist.github.com/FelipeMFx/b7cb23b2ec6b1e3a2006c32bf9c3da4d)

> ⚠️ Endpoints de autenticação de operadores ainda precisam ser implementados.

---

## 🚧 Status do Projeto

### ✅ Concluído
- Autenticação (completa)
- Migrations do banco de dados
- Mapeamento de endpoints
- Frontend avançado

### 🔄 Em Desenvolvimento
- Responsividade do frontend
- Implementação da API
- Integração frontend/backend

### ⏳ Pendências
- Finalização da API
- Testes de integração
- Deploy final
- Ajustes da equipe AgRoss

---

## 👥 Equipe do Projeto

| Nome             | Função                      |
|------------------|-----------------------------|
| John             | Coordenador geral           |
| Felipe           | Desenvolvedor Frontend      |
| Daiane           | Gestora de Requisitos       |
| Kayky Nogueira   | Desenvolvedor Backend  |
| Marcos Henrique  | Desenvolvedor Backend    |

---

## 📌 Observações

- O backend do operador está sendo construído **do zero**
- O sistema de autenticação é **independente** do painel atual da AgRoss
- Projeto com **urgência alta** e prioridade de entrega
- Documentação técnica disponível para consulta

---

## 📄 Licença

Este projeto é privado e restrito à equipe da **AgRoss**.  
Uso não autorizado é proibido.

---
