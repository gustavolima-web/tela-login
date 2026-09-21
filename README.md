# Tela de Login

Página de login com tema escuro, validação de campos em JavaScript e controle de
versões com Git, desenvolvida para a atividade avaliativa de Versionamento da
disciplina de Engenharia de Software.

## Funcionalidades

- Tela de login com tema escuro (`index.html`)
- Validação dos campos usuário e senha via JavaScript (`script.js`)
- Mensagens de erro para campos vazios ou credenciais inválidas
- Painel principal com menu e boas-vindas (`dashboard.html`)
- Formulário de cadastro de novos usuários (`cadastro.html`)

## Credenciais de teste

| Usuário | Senha |
|---------|-------|
| adm     | 123   |

## Estrutura de arquivos

```
tela-login/
├── index.html      # tela de login
├── dashboard.html  # painel principal
├── cadastro.html   # cadastro de usuários
├── style.css       # estilos do tema escuro
└── script.js       # validação dos campos
```

## Organização das branches

| Branch                     | Base    | Finalidade                          |
|----------------------------|---------|-------------------------------------|
| `main`                     | —       | Código estável e publicado          |
| `develop`                  | `main`  | Desenvolvimento ativo               |
| `feature/validacao`        | `develop` | Validação dos campos de login     |
| `feature/dashboard`        | `develop` | Painel principal                  |
| `feature/cadastro-usuario` | `develop` | Tela de cadastro                  |
| `hotfix/erro-html`         | `main`  | Correção estrutural no HTML         |
| `release/v1.1.0`           | `develop` | Preparação da versão 1.1.0        |

## Autor

Gustavo Lima — gustavo.lima@fatecitapetininga.edu.br
