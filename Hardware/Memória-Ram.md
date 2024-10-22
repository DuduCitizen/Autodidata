# Timing

O termo "time da memória RAM" geralmente se refere à ***latência e à velocidade*** da memória RAM em um sistema de computador. Esses tempos descrevem o desempenho da RAM, influenciando o quão rápido ela pode ler ou gravar dados.

<br>

- **Latência CAS (Column Address Strobe)**: `É o tempo que leva entre o momento em que um comando é enviado à memória e o momento em que os dados começam a ser lidos ou escritos`. Uma latência CAS menor significa uma memória mais rápida.

#
<br>

- **Timing**: O timing da RAM é geralmente representado por uma série de números (por exemplo, **`16-18-18-36`**). Esses números correspondem a diferentes tipos de latências na memória:
  
      - CAS Latency (CL): O tempo para acessar uma coluna específica na memória.
      - RAS to CAS Delay (tRCD): O tempo entre a ativação de uma linha de memória e a ativação de uma coluna.
      - Row Precharge Time (tRP): O tempo necessário para desativar uma linha de memória antes de ativar outra.
      - Row Active Time (tRAS): O tempo total que uma linha de memória permanece ativa para uma operação.
  
<div align="center">
  
  ### [Aula sobre Timing](https://youtu.be/wmwTXlfrkxs?si=7sbOQn6wBxSHUIMZ)
</div>
