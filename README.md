## Desenvolvimento em KICAD de placa de avaliação do CI da Texas Instrumets BQ769x2 para monitoramento e proteção de batérias de íon-lítio 3S-16S.


## Changelog

12/12/25
- Separa folha de monitoramento, folha de proteção e folha raiz
- (Folha raiz)Adiciona conector para resistores shunt de simulação de células
- (Folha de monitoramento) Adiciona botão de WAKE no pino TS2 do CI e jumper para conectar termistor externo ao pino TS2
- (Folha de monitoramento) Adiciona conector para monitorar externamente tensões geradas por regulador interno do CI em REG1 e REG2.
- (Folha de proteção) Adiciona componentes para circuito de disparo de fusível controlável
- (Folha de proteção) Adiciona componentes para circuito de pré-carga/descarga
- (Folha de proteção) Adciona componentes para proteção de conexão com polaridade reversa

18/12/25
- Adiciona diretório com simulações de LTSpice
28/01/25
- Adiciona footprints finais, com base na lista de componentes fornecidas ao pessoal do SENAI
- Posiciona Net-Tie entre terminal negativo da bateria e tensão de referência dos CIs para isolar caminhos de alta corrente
