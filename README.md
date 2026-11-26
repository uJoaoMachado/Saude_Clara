# ALFAS — Plataforma de Literacia em Saúde para Jovens

**Projeto Integrador — Sistemas Multimédia I | ISTEC Porto | 2026/2027**

## Sobre o projeto
O ALFAS é uma plataforma web de literacia em saúde dirigida principalmente a jovens do 3.º ciclo e do ensino secundário. Prevê webinars, workshops, biblioteca virtual, notícias e agenda de atividades.

Os utilizadores registados poderão inscrever-se em recursos formativos, responder a um questionário de diagnóstico antes da formação e a um questionário final depois, consultar resultados e obter badges e certificados mediante os critérios definidos pelo projeto.

## Tecnologias previstas
- **Frontend:** React
- **Backend:** Python com Flask
- **Base de dados:** MySQL ou SQL Server (a selecionar pela equipa)

## Organização inicial do repositório
```text
ALFAS/
├── frontend/           # Aplicação React (a desenvolver)
├── backend/            # API Flask (a desenvolver)
├── docs/               # Documentação e diagramas
├── .github/            # Modelo de Pull Request
├── .gitignore          # Ficheiros ignorados pelo Git
├── CONTRIBUTING.md     # Regras de branches e colaboração
└── README.md           # Apresentação do projeto
```

**Estado:** repositório inicial de planeamento da Sprint A. As pastas `frontend/` e `backend/` ainda não representam uma implementação funcional.

## Perfis previstos
- **Convidado:** consulta conteúdos públicos e efetua registo.
- **Utilizador registado:** inscreve-se em recursos, responde a questionários e consulta recompensas.
- **Manager:** gere conteúdos formativos, questionários e estatísticas.
- **Administrador:** gere também utilizadores, perfis, estados de conta e permissões.

## Trabalho da Sprint A
- **US_A002:** análise e atualização dos casos de uso do Frontoffice e Backoffice.
- **US_A004:** elaboração do Modelo de Domínio.
- **US_A006:** preparação do repositório GitHub e das regras de colaboração.

## Colaboração
Consultar [CONTRIBUTING.md](CONTRIBUTING.md) para regras de branches, commits e Pull Requests.


## Privacidade e segurança
Não publicar palavras-passe, chaves de API, tokens, dados pessoais reais nem ficheiros `.env` com credenciais.
