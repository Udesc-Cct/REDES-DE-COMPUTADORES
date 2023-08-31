# Camada de Transporte
Para existir uma camada de transporte tem que existir um contolo de enventos, exemplo:

| Problemas | Solução |
|----------------|------------------|
| Bit invertido | ACK/NACK |
| Perder Buffer | Timeout |
| Conexão | RTT |

Enviou -> RDT_SEND(); -> UDT_SEND(); -> RDT_RCV(); -> DELIVER_DATA(); -> RECEBEU

RDT 1.0
- UTOPICO PERFEITO

RDT 2.0
- Bit

