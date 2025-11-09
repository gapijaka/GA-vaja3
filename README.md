2
b) ADC pretvornikov je 3 
c) naslov pina PC2(ADC3_IN3)
d) Poleg pina se izpiše ADC3_IN3
e) Opazimo da se je timer clock tudi spremenil. Spremenili so se različni APB-ji. Nova frekvenca je uplivala na veliko drugih vrednosti.
g) 4MHz
i) tvz=247,5/4=61,9μS
tvz=12/4=3μS

3.
f) HAL_GPIO_togglePin (GPIOA GPIO_pin_2)
SLIKA PINOUT:

![f4aecb39-f915-486e-8664-2cb1ca7ccc5f](https://github.com/user-attachments/assets/64fd4c25-795d-41e1-a0bb-0107e95c374f) 
SLIKA TIMER2:

![c0e7d7f2-c1b5-4904-9610-0e9412d4e8ad](https://github.com/user-attachments/assets/f84e4fd7-fe87-44f5-ad30-66720cc8fe03)
SLIKA ADC KONFIGURACIJE:

![688ad21d-0f0a-4405-a8be-79190dfc1cc1](https://github.com/user-attachments/assets/50822346-560e-4493-b373-94fe08d07c0c)
na koncu smo povezali potenciometer in smo na stm studiu prebrali vrednost adc pretvornika in s potenciometrom spremenili vrednost.
