# CurseForge

Pagina feita para catalogar os Modpacks jogados pela QDT.

- [All of Fabric 6](1.19.2/All of Fabric 6.md)

# Dicas
- Modpacks até a 1.16 necessitam do [Java 8](https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR)
- Modpacks da 1.17 necessitam do [Java 16](https://www.oracle.com/java/technologies/javase/jdk16-archive-downloads.html)
- Modpacks da 1.18 pra frente necessitam do [Java 17](https://builds.openlogic.com/downloadJDK/openlogic-openjdk-jre/17.0.9+9/openlogic-openjdk-jre-17.0.9+9-windows-x64.msi)


# Parametros Java

### Parametros otimizados para sistemas com pelo menos 8GB de RAM

<details><summary>Parametros Padrão</summary>

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

</details>

<details><summary>Caso estiver utilizando o Java 17 da OpenJDK</summary>

```
-Xmn4096m 
-XX:+AlwaysPreTouch 
-XX:+ParallelRefProcEnabled 
-XX:+PerfDisableSharedMem 
-XX:+UseCompressedOops 
-XX:-UsePerfData 
-XX:MaxGCPauseMillis=200 
-XX:ParallelGCThreads=8 
-XX:ConcGCThreads=2 
-XX:InitiatingHeapOccupancyPercent=50 
-XX:G1HeapRegionSize=1 
-XX:G1HeapWastePercent=5 
-XX:G1MixedGCCountTarget=8 
-XX:+UseShenandoahGC 
-XX:+UnlockExperimentalVMOptions 
-XX:+AlwaysPreTouch 
-XX:+UseStringDeduplication 
-Dfml.ignorePatchDiscrepancies=true 
-Dfml.ignoreInvalidMinecraftCertificates=true 
-XX:-OmitStackTraceInFastThrow 
-XX:+OptimizeStringConcat 
-Dfml.readTimeout=180
```

</details>

