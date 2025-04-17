```python
import time
import sys

mensagem = (
    "Olá, meu nome é Hebert e estou explorando o mundo dos códigos e IA. "
    "Além de um pouco de low code e no code."
)

for caractere in mensagem:
    sys.stdout.write(caractere)
    sys.stdout.flush()
    time.sleep(0.05)  # tempo entre letras (ajuste se quiser mais lento ou rápido)

print()  # nova linha após a mensagem

