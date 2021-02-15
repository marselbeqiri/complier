### Build:

Ne pathin e projektit hapni terminalin dhe ekzekutoni:
```
make
```
###### Per te ekzekutuar komanden 'make' duhet qe paraprakisht te kemi te instaluar "Make: GNU make" 
#
### Ekzekutimi:

Vendos filen java qe deshiron te ekzekutosh ne folder-in "samples" dhe me pas ekzekuto komanden: 
```
make run file=FileQeDoTeEkzekutohet.java
```

Ndryshe mund te kryejme ekzekutim manual: 

- Linux: 

```
java -cp ./tools/java-cup-11a.jar:. MiniJavaCompiler samplesFileQeDoTeEkzekutohet.java
```
- Windows 
```
java -cp ./tools/java-cup-11a.jar;. MiniJavaCompiler samplesFileQeDoTeEkzekutohet.java
```
#
### Ekzekuto OutPut:

Pasi komanda e meparshme ekzekutohet me sukses, ajo kthen nje file assembler mips
te cilin nepermjet Simulatorit Mars i bejme run si me poshte:


```
make runMars file=samplesFileQeDoTeEkzekutohet.asm
```