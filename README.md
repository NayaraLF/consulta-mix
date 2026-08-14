# Consulta de Compatibilidade de Lampadas Automotivas

Sistema online para consultar compatibilidade de lampadas automotivas. Dados agregados de multiplas fontes especializadas.

## Recursos

- Busca em tempo real por marca, modelo, ano ou codigo de lampada
- Filtro por montadora
- Dados de multiplas fontes (Rayx, Permak, Liderauto)
- Interface offline, funciona completamente no navegador
- Site estatico, sem servidor

## Estrutura

```
consulta-mix/
├── public/
│   ├── index.html                # Interface web
│   └── data/
│       └── lampadas_data.json    # Base de dados
├── package.json
├── vercel.json                   # Config de deploy
└── README.md
```

## Deploy

Hospedado no Vercel. Qualquer push para `main` dispara um redeploy automatico.

```bash
git push origin main
```

## Licenca

Dados compilados de fontes publicas. Uso livre.
