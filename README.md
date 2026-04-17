# Circuito isolador de portas USB

![Status do Projeto](https://img.shields.io/badge/Status-Desenvolvimento-yellow)
![PCB](https://img.shields.io/badge/PCB-KiCad-green)

## Descrição
Este circuito foi desenvolvido com o propósito de realizar uma isolação digital de 3,75 kV RMS para USB 2.0 de alta e baixa velocidade.

<p align="center">
  <img width="751" height="405" alt="Imagem3" src="https://github.com/user-attachments/assets/377739c6-405a-481e-a46d-2d39081b6d20" />
</p>

---

## Descrições técnicas

- Sinalização USB 2.0 com detecção automática de conexões de baixa, plena e alta velocidade;
- Taxas de dados de 1,5 Mbps, 12 Mbps e 480 Mbps;
- Isolador USB bidirecional para portas upstream e downstream;
- Recondicionamento e retiming de dados em alta velocidade para remoção de jitter de entrada;
- Modo de espera de ultrabaixo consumo em suspensão (L2) ou desconexão USB 2.0;
- Corrente típica de espera de baixa potência no lado upstream: 1,7 mA;
- Corrente típica de espera de baixa potência no lado downstream: 20 μA;
- Proteção ESD de ±6000 V conforme a norma IEC 61000-4-2, através da barreira de isolação;
- Atende aos requisitos de emissão da norma CISPR32/EN55032 Classe B;
- Alta imunidade a transientes de modo comum: 50 kV/μs (típico).

---

## Estrutura do repositório
Os arquivos de hardware foram desenvolvidos utilizando o KiCad 9.0.
- **`.kicad_pcb`**: Layout da placa de circuito impresso (Board).
- **`.kicad_sch`**: Esquemático eletrônico do sistema (Schematic).
- **`.kicad_pro`**: Gerenciador de projeto do KiCad (Project).

---

## Autor
**Dr. Luiz Fernando Pinto de Oliveira**

*Engenheiro Eletrônico especializado em Sistemas Embarcados e Ultra-Low Power.*
- **Website:** [FAPLO](https://faplo.webnode.page/)
- **LinkedIn:** [lfpo](https://www.linkedin.com/in/lfpo/)

---

Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
