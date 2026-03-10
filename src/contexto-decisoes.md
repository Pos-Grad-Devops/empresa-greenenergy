# Contexto de Decisões Arquiteturais - GreenEnergy

## Situação atual
- Plataforma coleta telemetria de usinas solares e eólicas em tempo quase real.
- Dados são consumidos por painéis operacionais e relatórios regulatórios.
- Crescimento recente elevou volume de eventos e necessidade de resiliência.

## Decisões já tomadas informalmente
- Separação entre API de ingestão e API de consulta.
- Uso de fila para desacoplamento de processamento.
- Replicação de banco para leitura analítica.

## Problema principal
- Não existe histórico formal explicando por que as decisões foram adotadas.
- Alternativas avaliadas não foram registradas.
- Novas equipes têm dificuldade para entender trade-offs técnicos.
