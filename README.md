Menu

- Semana No.1 

## Tuesday

- **Base on this reading and this video, create an explanation about Interpreted And Compiled Programming Languages in your README**
Explicación: El lenguaje compilado, es aquel donde se convierte directamente en codigo que el procesador puede ejecutar inmediatamente, como resultado suelen ser mas rapidos y eficientes. Tenemos como ejemplo: C, C++, Erlang, Haskell, Rust y Go.  Por otro lado, el lenguaje interpreted, corre directamente a traves un programa, línea por línea, ejecutando cada comando. Ejemplos: php, Ruby, Phyton y JavaScript. 

- **Is Java compiled or interpreted, or both?**
Java se puede considerar tanto un lenguaje compilado como interpretado porque su código fuente se compila primero en un código de bytes binario. Este código de bytes se ejecuta en la máquina virtual de Java (JVM), que suele ser un intérprete basado en software..

- *Pseudocódigo Ejercicio*
```javascript
START
Cantidad <-- GET
BitCoin <-- GET FROM (www.xe.com/es/currencyconverter/convert/?Amount=1&From=USD&To=BTC)
Total <-- Cantidad * BitCoin 
Print Total 
END
```
## Wednesday 

- Your date of birth in the matrix? 

| Fecha nacimiento |  |
| ----------- | ----------- |
| Binario | 11111001010 |
| Base 10    | 1994 |
.

- MIPS 

```javascript
  .data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
	                    	      result_message: .asciiz "\nEl resultado es: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              li $v0, 1
              move $a0, $t0
              

              	      
              	                    add $t2, $t0, $t1
              	                    li $v0, 4
              la $a0 result_message
              syscall

              li $v0, 1
              move $a0, $t2
              	      
              	      
              syscall
```
Resultado
![Captura de pantalla (1)](https://user-images.githubusercontent.com/109687502/180795599-132b6d51-9529-49b0-a87a-09b1bd144684.png)