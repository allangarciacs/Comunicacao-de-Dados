--- 
Anotações da disciplina de Comunicação de Dados
---

 ## O QUE É COMUNICAÇÃO DE DADOS?
<pre>
 - É transmitir uma informação para 1 ou mais pessoas atravéz de um meio de transmissão.

   - Fonte               – De onde sai a mensagem, quem cria a informação; 
     - Mensagem            – A informação por si só; 
       - Transmissor         – Dispositivo que envia a mensagem (computador, telefone etc.); 
         - Receptor            – Dispositivo que recebe a mensagem; 
           - Meio                – caminho físico por onde a mensagem viaja (cabo, ar etc.); 
             - Protocolo           – Conjunto de regras que governa essa comunicação de dados (protocolo). 
</pre>

## TRANSMISSÃO DE DADOS 
<pre>
 - Simplex - Dispositivo é o transmissor envia o receptor recebe (unidirensional). Transmissão de antena. 
 - Half-duplex – A e B recebem e enviam, mas precisam estar na mesma rede (Bidirensional). Walkye Talkye.   
 - Full-duplex – A e B podem transmitir e receber dados ao mesmo tempo (100% bidirecional). Internet, telefone fixo, celulares.  
</pre>

## Diferença entre comunicação por TELEFONIA e COMPUTAÇÃO.  
 - Telefonia – Cabos de energia geram a voz. 
 - Computação - Conjunto de regras de comunicação.  

## COMUTAÇÃO
- é conectar pontos para que informações sejam trocadas. 

## COMUTAÇÃO DE CIRCUITOS
<pre>
  - É um processo de conectar 2 ou mais pontos de uma rede, para que seja permitida a troca de informações -> A --------- B.
    
  -> Vantagens    - Garantia de banda       | Baixa latência constânte | Qualidade previsivel
  -> Desvantagens - Desperdício de recursos | Baixa eficiência         | Escalabilidade limitada
</pre>

## COMUTAÇÃO DE PACOTES 
<pre>
  - A mensagem é fragmentada em pacotes, até chegar no destino e ser reorganizada novamente.
    - Cada pacote contém
      - Dados
      - Endereço de origem
      - Endereço de destino
      - Cabeçalho (Header)

  -> Vantagens    - Uso eficiente da rede | Maior escalabilidade        | Flexibilidade das rotas
  -> Desvantagens - Atraso (latência)     | Possível perda de pacotes   | Qualidade não é garantida por padrão
</pre>

## ROTEAMENTO
<pre>
  - O papel do roteamento é encontrar o melhor caminho dos pacotoes para o destino. O melhor caminho é definido a partir da:
    - Número de saltos - Representa quantos roteadores ou nós um pacote deve atravessar. 
    - Latencia 
    - Largura de dados 
    - Congestionamento   
</pre>

## EVOLUÇÃO DOS CELULARES
<pre>
  -> 1G - Voz
  -> 2G - Voz e SMS
  -> 3G - Dados móveis
  -> 4G - Internet rápida
  -> 5G - Alta capacidade + baixa latência
</pre>

## PRINCIPAIS EVOLUÇÕES
<pre>
   - Digitalização do sinal 
   - Compressão de dados
   - Protocolos mais eficientes
   - capacidae de porcessamenteto
</pre>

## DESAFIOS TÉCNICOS NA TRANSMISSÃO
<pre>
  -> A realidade física do sinal
      - Clima
  -> Atenuação 
      - Perda de potência do sinal conforme a distância
  -> Ruído e interferência 
      - Interferência eletromagnetica  
      - Sobreposição de canais wi-fi
      - Obstáculos físicos do ambiente

 Como lidar com esses desafios? 
    -> Bits de qualidade
    -> Checar o cash - Checksue
    -> Retransmissão
    -> Confirmação de recebimento (exemplo: TCP)
    -> Latência (ping)
        - Tempo que o pacote leva para ir da origem ao destino
        - Medida em milisegundos (ms)
    -> Jitter 
        - Variação no tempo da chegada do pacote
        - Afeta principlamente áudio e vídeo
        - SOLUÇÃO: buffer de jitter (atrasa um pouco inicialmente para não ter variação depois)
   </pre>     



 

