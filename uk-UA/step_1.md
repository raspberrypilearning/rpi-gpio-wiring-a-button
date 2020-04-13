Кнопка — один з найпростіших компонентів вводу, які ти можеш приєднати до Raspberry Pi. Вона є неполяризованим компонентом, тобто таким, який ти можеш розмістити в електричному колі в будь-якому напрямі, і він працюватиме.

Існують різні типи кнопок, наприклад вони можуть мати дві або чотири ніжки. Версії з двома ніжками в основному використовуються з дротами для з’єднання з контролюючим пристроєм. Кнопки з чотирма ніжками в основному встановлюються на друковані або макетні плати.

Нижченаведені діаграми показують як приєднати кнопку з двома або чотирма ніжками до Raspberry Pi. В обох випадках **GPIO 17** є вхідним піном.

![2-pin-btn](images/2-pin-button.png) ![4-pin-btn](images/4-pin-button.png)

If you are using multiple buttons, then it is often best to use a *common ground* to avoid connecting too many jumper leads to **GND** pins. You can wire the negative rail on the breadboard to a single *ground* pin, which allows all the buttons to use the same ground rail.

![2x4-pin-btn](images/2x4-pin-button.png)
