#  Relógio Java 
Exercício da DIO de Programação Orientada a Objetos em Java.

Um Relógio que funciona em dois formatos e converte um no outro.

## O que o projeto faz
- **BRLClock** Relógio Brasileiro no formato 24h (ex: "23:00:00")
- **USAClock** Relógio Americano no formato 12h com AM/PM (ex: "11:00:00")
- **Convert** Transforma um relógio no outro

## Como Funciona
'''Java
Clock brlClock = new BRLClock();
brclClock.setHour(23);
System.out.println(brlClock.getTime()); // 23:00:00

Clock usaClock = new USAClock();
usaClock.convert(brlClock);
System.out.println(usaClock.getTime()); // 11:00:00

## Regra de Validação
- Hora no Relógio brasileiro trava em 23 se passar disso
- Hora no Relógio americano vai até 12 e usa AM/PM
- Minuto e segundo travam em 59

## Tecnologias
- JAVA
- VS Code

feito por Mcollecta
