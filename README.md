# INP PROJEKT 1, FIT VUT 2022

_První projekt (procesor s Brainfuck-like ISA) z předmětu Návrh počítačových systémů (INP), třetí semestr bakalářského studia BIT na FIT VUT/BUT, ak.rok 2022/2023_

🔒 **Aktivní soukromý repozitář — nezveřejňovat!**

<img align="right" width="55%" src='https://github.com/Onegenimasu/VUT-FIT-INP2022-projekt1/raw/main/fsm.png' />

Hodnocení: ?? / ??<br>(??)

Zadání: ??

### TODO List

- [x] `login.b` program na výpis loginu
- [x] Spojeznit _fitkit-build_
- [X] Kouzlo s `cpu.vhd`
  - [X] PC, PTR, CNT, MX
  - [X] FSM logic
    - [X] model
    - [X] implementation base
    - [X] test cpu.test_reset
  - [X] instruction noop
  - [X] instruction 0x00 – null
  - [X] instruction 0x2B – +
    - [X] test cpu.test_increment
  - [X] instruction 0x2D – -
    - [X] test cpu.test_decrement
  - [X] instruction 0x3C – <
  - [X] instruction 0x3E – >
    - [X] test cpu.test_move
  - [X] instruction 0x2E – .
    - [X] test cpu.test_print
  - [X] instruction 0x2C – ,
    - [X] test cpu.test_input
  - [X] instruction 0x5B – [
  - [X] instruction 0x5D – ]
    - [X] test cpu.test_while_loop
  - [X] instruction 0x28 – (
  - [X] instruction 0x29 – )
    - [X] test cpu.test_do_loop
  - [X] test cpu.test_login (while loops only)
  - [ ] test cpu.test_login (change one loop to do-while)
- [ ] ⏰ Deadline 13.11.
- [ ] ⏰ Hodnocení
