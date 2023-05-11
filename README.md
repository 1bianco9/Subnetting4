# Subnetting4
Abbiamo fatto subnetting delle 4 reti facendole comunicare tra di loro (abbiamo impostato la subnet mask a 255.255.255.192 per far si che le 4 reti differenti comunichino tra di loro).

![tabellasubnetting](https://github.com/1bianco9/Subnetting4/assets/116873906/cd8d35d2-e803-4dfb-a283-8fec465d06b4)

La nostra rete era una /24, percio grande 256; per dividere la rete in quattro parti, come si puo vedere nella tabella, bisogna trasformarla in 4 reti da 64 ip ognuna (ovviamente il primo e l'ultimo ip di ogni rete non si può usare perche il primo è riservato al network id e l'ultimo al broadcast ip)
Una volta configurati gli ip dei computer di ogni sottorete occorre modificare la subnet:
come abbiamo visto nello scorso esercizio "subnetting", per dividere la rete in 2 parti occorreva prendere un bit,
che corrisponde a 2^7, percio 128. Questa volta occorre prendere un'altro bit per dividere la rete in piu parti, quindi verrà preso sia 2^7 che 2^6 che sommati sono: 128+64=192  
Quindi la subnet sarà: 255.255.255.192
