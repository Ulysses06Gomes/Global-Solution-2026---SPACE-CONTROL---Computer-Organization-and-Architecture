# Global-Solution-2026---SPACE-CONTROL---Computer-Organization-and-Architecture
Desenvolver um sistema de Internet das Coisas (IoT) destinado ao monitoramento de variáveis físicas essenciais para a operação segura de um módulo espacial durante uma missão simulada. O sistema deve coletar, processar e exibir informações em tempo real sobre as condições internas e operacionais do módulo.
Tinkercad: https://www.tinkercad.com/things/7NKSlYhlrzL-gs-space-control-computer-organization?sharecode=z6Ngrem2PkWDVed7z2EQkd-gMK5ilCoWQ3oHY1_wvJg
Youtube: 

Variáveis Monitoradas
•	Temperatura: Temperatura do ambiente interno da cápsula, indicando risco de superaquecimento ou hipotermia dos tripulantes.
•	Luminosidade: Luminosidade, simulando condições internas e externas do módulo, útil para detectar falhas de iluminação ou exposição solar anômala.
•	Vibração: Vibração, indicando possíveis impactos, falhas mecânicas ou turbulências durante a missão.

Resultados Obtidos
A simulação foi executada com sucesso no Tinkercad com Arduino Uno. Os principais resultados observados foram:
•	O sensor TMP apresentou leituras estáveis de temperatura e umidade, com atualização a cada 1 segundo no display LCD.
•	O divisor de tensão com LDR respondeu corretamente às variações de luminosidade simuladas, ativando alerta visual ao atingir valores críticos.
•	O SW-200D detectou acelerações simuladas, acionando o buzzer nos cenários de impacto.
•	O display LCD exibiu todas as três variáveis de forma clara e contínua, com status de saúde do sistema na linha inferior.

Conclusão
O projeto demonstrou com sucesso a viabilidade de construção de um sistema IoT embarcado para monitoramento de cápsula espacial utilizando componentes acessíveis e plataformas de simulação gratuitas. A integração entre o microcontrolador Uno, os três sensores (TMP, LDR, SW-200D) e o display LCD resultou em um sistema coeso, funcional e com resposta em tempo real.
O impacto real da solução se conecta ao ODS 9 (Inovação e Infraestrutura) e ao ODS 13 (Ação Climática), pois tecnologias de monitoramento espacial têm aplicação direta no monitoramento ambiental terrestre, antecipação de desastres e operações em regiões remotas sem infraestrutura convencional.
