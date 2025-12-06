# Projeto-Ns3

Explicação do Resultado

Você está vendo eventos reais de transmissão (TX) e recepção (RX) dos nós IoT.

Cada linha significa:

[TX]

Um pacote foi transmitido pelo nó (MAC transmitindo).

[RX]

O pacote foi recebido pelo outro nó (MAC recebendo).

Exemplo:
[TX] /NodeList/0/DeviceList/0/Mac/MacTx | 36 bytes
[RX] /NodeList/1/DeviceList/0/Mac/MacRx | 36 bytes


Significa:

O nó 0 enviou um pacote de 36 bytes

O nó 1 recebeu corretamente o mesmo pacote

📡 O que está acontecendo na sua simulação

✔ Dois nós (Node0 e Node1) estão trocando mensagens
✔ As mensagens variam entre 36 bytes e 236 bytes
✔ O canal está funcionando perfeitamente, sem perdas
✔ Você habilitou os trace sources do MAC, então só vê TX/RX

# Resultado 
![g](https://github.com/user-attachments/assets/4c204761-c215-4e83-be34-7984d2c57c86)

# Erro
![erro](https://github.com/user-attachments/assets/34d8d9d6-958f-4f04-96e4-6dbd3e8f38ea)



