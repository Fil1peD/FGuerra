# FGuerra
Plugin de guerras para a 1.21.11
## Comandos diversos e úteis.

### Atualizações:

## 1.0.0 — Lançamento

Mapas, fila, kit SETADO/PRÓPRIO, countdown, PvP temporizado, vitória por clan, menu, SimpleClans, auto-start, comandos/itens proibidos.

## 1.1.0 — Dependências opcionais

Clans: SimpleClans · Economia: Vault ou comandos · clan-provider / economy-provider · /guerra reload.

## 1.2.0 — Reconectar e moderação

/guerra reconectar (5 min) · /guerra puxar · /guerra kick · /guerra kickall · comandos proibidos para todo o servidor durante a guerra.

## 1.2.1 — Correções de inventário

Logout guarda kit do evento e restaura inventário original · reconectar devolve kit do evento · recompensas depois de restaurar o inventário (já não são apagadas).

### FGuerra 1.3.0 — Atualização

**Menu**
- Posição do vidro (camarote) ajustada um slot para a direita  
- Armor stand (clans vivos) movido dois slots para a direita  

**Comandos**
- Ajuda reorganizada no formato **AJUDA - FGUERRA**, com lista legível de comandos  
- Kit por mapa: `/guerra setarkit <mapa> <setado|proprio>`  
  - **setado** — grava inventário e armadura do admin  
  - **proprio** — jogadores usam o próprio inventário  

**Mensagens**
- Aviso de início a cada **20 segundos**, com número de jogadores e clans  
- Feed de kills: `Jogador(kills) matou Jogador(kills)`  
- Aviso quando um clan é eliminado e quantos restam  
- Aviso ao cair/desconectar, com lembrete dos 5 minutos de reconectar  
- Vitória com **tag do clan**, **MVP** (mais kills) e **data** do evento  
- Texto de PvP corrigido: *“Que vença o melhor clan”*  

**Sistemas**
- Após **3 saídas/quedas**, o jogador deixa de poder usar `/guerra reconectar`  
- Limite configurável em `max-saidas-reconectar` no `config.yml`  


### FClans

**Dependencia opcional do FGuerra, caso nao queira usar FClans, pode usar SimpleClans**
