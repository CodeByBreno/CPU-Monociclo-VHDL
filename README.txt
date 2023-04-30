Execute no EDA playground ou outro programa que entenda VHDL

Esse código foi compilado usando o Aldec Riviera Pro 2020.4

O código no exemplo1.data é:

addi $s0, $zero, 1
addi $s1, $zero, 1
compara : bne $s0, $s1, label
addi $s0, $s0, 1
j compara
label: