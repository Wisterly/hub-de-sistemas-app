# Hub Seduc.Lab 0.1.26

- Aplica blindagem com fallback rigoroso (`?.trim() ||`) em todas as URLs dos sistemas do catálogo, impedindo que variáveis de ambiente em branco ou nulas em provedores de hospedagem (como Vercel) desativem os links.
- Revalida e consolida o link direto do OrçaCraft.lab (`https://orcacraft-lab.vercel.app/`).
