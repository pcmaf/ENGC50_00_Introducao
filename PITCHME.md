
# ENGC50

## Sistemas Microprocessados

### 2017.1

#HSLIDE

#### Sistemas embarcados

- Microprocessadores de propósito geral
- Microcontroladores
- FPGA
- DSP (Digital Signal Processor)

#HSLIDE

#### Microprocessadores de propósito geral

- Microprocessadores são dispositivos digitais programáveis que integram todas as funcionalidades de uma CPU em um único chip.
- Possuem conjunto de instruções e arquitetura bem definidos
- Não possuem dispositivos de I/O integrados
- Não possuem timers, contadores, ou interfaceamento com sinais analógicos
- São usados em aplicações genéricas
- x86, PowerPC, Z80

#HSLIDE

#### Microprocessadores de propósito geral

<!--![](images/microprocessor.png)-->
<img src="images/microprocessor.png" alt="uP" width="784" height="417"/>


#HSLIDE

#### Microcontroladores

- Um microcontrolador pode ser definido como um sistema computacional totalmente contido em um circuito integrado
- Conjunto de instruções e arquitetura definidas
- Possuem recursos de I/O
- Custo e consumo baixos
- Poder de processamento menor que um microprocessador de propósito geral
- 8051, PIC, ATmega8

#HSLIDE

#### Microcontroladores

![](images/100000000000023B000001BDB26F66ED.png) 

#HSLIDE

#### Microcontroladores

<!--![](images/10000201000003A400000618DE1DA1BD.png  =600x) -->
<img src="images/10000201000003A400000618DE1DA1BD.png" alt="PIC" height="500"/>

#HSLIDE

#### FPGA – Field Programmable Gate Array

- Um FPGA é um dispositivo digital contendo blocos lógicos e conexões programáveis
- Não possui arquitetura definida
- Geralmente não possuem facilidades de I/O
- Usada em aplicações computacionais que demandam processamento paralelo reconfigurável
- Possui recursos de memória interna

#HSLIDE

#### FPGA – Field Programmable Gate Array

<!--![](images/100000000000018200000152D70C8897.png) -->
<img src="images/100000000000018200000152D70C8897.png" height="500"/>

#HSLIDE

#### DSP (Digital Signal Processor)

- Hardware especializado para execução eficiente de operações matemáticas comuns  (adição, multiplicação) e transferência de memória 
- Alta velocidade de operação, possibilitando a amostragem e manipulação de grandes quantidades de dados 
- Componentes arquiteturais específicos com o objetivo de aumentar a eficiência do processamento de sinais
- Conjunto de instruções definido
- Possui alto grau de paralelismo

#HSLIDE

#### DSP (Digital Signal Processor)

![](images/100000000000050A000001200176FACA.png) 

#HSLIDE

#### DSP (Digital Signal Processor)

![](images/10000000000001F5000001F245040A69.png) 

#HSLIDE

#### DSP (Digital Signal Processor)

![](images/100000000000026D000001EC3E8D15BC.png) 

#HSLIDE

#### Arquiteturas de memória

![](images/100000000000034D000001840473CF00.png) 

#HSLIDE

#### Arquiteturas de memória

<!--![](images/10000000000002660000024F7DFDFA24.png) -->
<img src="images/10000000000002660000024F7DFDFA24.png" alt="PIC" height="500"/>

#HSLIDE

#### Microcontroladores

<!--![](images/10000000000003780000018BC496FEFE.png) -->
<img src="images/10000000000003780000018BC496FEFE.png" alt="PIC" height="300"/>

![](images/100000000000011400000087546A7429.png) 

#HSLIDE

#### Microcontroladores

- Timers

<img src="images/10000000000003960000018CB6BC3E4C.png"/>

#HSLIDE

#### Microcontroladores

- Whatchdog timer
- Reset input
- Brown-out detector
- Sleep mode
- Power-on Reset (POR)
- Current sink/source capability
- Analog comparators

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/10000000000003C50000020F8D629461.png"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)
	- Bloco responsável por converter o sinal analógico em quantidades digitais a serem transferidas para o microcontrolador

<img src="images/100000000000042A0000011BEAA2DCA6.png"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/10000000000002B50000016F9EF54892.png" height="500"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/10000000000002F70000018789633286.png" height="500"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/1000000000000262000001AFF8F1EC49.png" height="500"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/100000000000021A000001D703C2BC66.png" height="500"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/100000000000033E0000016DA47C0870.png" height="500"/>

#HSLIDE

#### Microcontroladores

- ADC (Analog to Digital Converter)

<img src="images/10000000000003A100000261D5A1DDB9.png" height="500"/>

#HSLIDE

#### Microcontroladores

- Real Time Clock
- USB interface
- CAN interface
- Ethernet interface
- ZigBee interface
- I2C interface
- SPI interface
- RS - 232

#HSLIDE

#### Microcontroladores

- Interface serial - USART
	- Transmissão

<img src="images/100000000000032700000140B4CFECF6.png"/>

#HSLIDE

#### Microcontroladores

- Interface serial - USART
	- Recepção

<img src="images/1000000000000393000001D824D78820.png" height="400"/>

#HSLIDE

#### Microcontroladores

- Interface serial - SPI (Serial Peripheral Interface)

<img src="images/100000000000032B000001C582A85739.png" height="400"/>

#HSLIDE

#### Microcontroladores

- Interface serial - SPI (Serial Peripheral Interface)

<img src="images/100002010000016B00000120A93D5D23.png" height="400"/>	
#HSLIDE

#### Microcontroladores

- PWM (Pulse Width Modulation)

<img src="images/1000020000000146000001163214951B.png" height="400" />
	
#HSLIDE

#### Microcontroladores

- PWM (Pulse Width Modulation)

<img src="images/100000000000039500000142E6B1567A.png" />
	
#HSLIDE

#### Microcontroladores

- PWM (Pulse Width Modulation)

<img src="images/10000000000003910000017C739AC66D.png" />

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/10000000000001F4000001C957E0959E.png" height="500"/>

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/10000000000001FE000001AD5423B416.png" />

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/10000000000002FB00000231D4C07D80.png" height="400" />

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/100000000000030B000001BC4224BB43.png" />

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/10000000000002FE0000017740D04C0F.png" />

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/100000000000027D000001EABBDD0A6D.png" />

#HSLIDE

#### Microcontroladores

- Exemplos

<img src="images/1000000000000304000001C724AAABEF.png" />	

	
	




	



	

	
			













