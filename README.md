# Roteirizador Logístico V4 — Geoapify

Primeira versão web: copiar/colar endereços, validar, calcular matriz rodoviária, otimizar por tempo/distância e desenhar rota com setas.

## Segurança
Nunca grave a API key no repositório. No Cloudflare Pages configure um Secret chamado `GEOAPIFY_API_KEY`.

## Limites do piloto
- até 30 entregas + base;
- perfil `drive`;
- algoritmo 2-opt (heurístico; não garante ótimo global);
- confira os pontos geocodificados visualmente antes da otimização.
