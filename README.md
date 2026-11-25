# Sistema de Gestão Web - Projeto de Extensão (Terceiro Setor)

Aplicação web desenvolvida como parte do Projeto de Extensão da disciplina de **Programação Web I**, do curso de **Sistemas de Informação** (Unidavi - Centro Universitário para o Desenvolvimento do Alto Vale do Itajaí).

## Propósito
Fornecer uma solução digital leve, acessível e funcional para apoiar a organização administrativa, operacional ou comunitária de uma entidade sem fins lucrativos da região do Alto Vale do Itajaí, promovendo impacto social por meio da tecnologia.

> *Nota: A entidade beneficiada e os módulos específicos de negócio serão detalhados após a etapa de levantamento de requisitos e entrevista.*

## Funcionalidades em Desenvolvimento
- [x] Estrutura base do projeto e configuração de ambiente
- [ ] Página inicial pública (`index.php`)
- [ ] Sistema de autenticação (Login / Logout com hash de senha e controle de sessão)
- [ ] Controle de acesso por perfis de usuário (RBAC básico / níveis de permissão)
- [ ] Camada de endpoints API em PHP para requisições assíncronas
- [ ] Módulos específicos da entidade (CRUD e persistência em banco de dados)

## Tecnologias Utilizadas
- **Back-end:** PHP 8+ (PDO / Arquitetura modular com API REST simples)
- **Front-end:** HTML5, CSS3, Bootstrap 5 e JavaScript Puro (Vanilla JS / Fetch API)
- **Banco de Dados:** MySQL / MariaDB
- **Ambiente Local:** XAMPP (Apache + MySQL)

## Como Executar Localmente
1. Clone este repositório dentro da pasta `htdocs` do seu XAMPP:
   ```bash
   git clone [https://github.com/DevMireski/sig-social-php.git](https://github.com/DevMireski/sig-social-php.git)
