# CurseForge

Pagina feita para catalogar os Modpacks jogados pela QDT.

- [All of Fabric 6](1.19.2/All of Fabric 6.md)

# Dicas
- Modpacks da 1.16 ou anterior necessitam do [Java 8](https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR)
- Modpacks da 1.17 necessitam do [Java 16](https://www.oracle.com/java/technologies/javase/jdk16-archive-downloads.html)
- Modpacks da 1.18 pra frente necessitam do [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

### Recomendamos utilizar o parametro abaixo:
```
-XX:+UseG1GC 
-XX:+ParallelRefProcEnabled 
-XX:MaxGCPauseMillis=100 
-XX:+UnlockExperimentalVMOptions 
-XX:+DisableExplicitGC 
-XX:+AlwaysPreTouch 
-XX:G1NewSizePercent=30 
-XX:G1MaxNewSizePercent=40 
-XX:G1ReservePercent=20 
-XX:G1HeapWastePercent=5 
-XX:G1MixedGCCountTarget=4 
-XX:InitiatingHeapOccupancyPercent=15 
-XX:G1MixedGCLiveThresholdPercent=90 
-XX:G1RSetUpdatingPauseTimePercent=5 
-XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem 
-XX:MaxTenuringThreshold=1
```
