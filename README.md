# 🚦 TrafficLight

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Java](https://img.shields.io/badge/java-8%2B-blue.svg)](#)

> Um sistema de semáforo modular para monitorar recursos e adaptar dinamicamente o comportamento da sua aplicação com base na carga.

---

## ✨ Visão geral

**TrafficLight** é uma biblioteca Java leve e extensível que ajuda sua aplicação a se manter **resiliente sob pressão**.  
Ela fornece um "estado do sistema" baseado em uso de CPU, memória ou qualquer métrica personalizada que você quiser rastrear — com uma interface simples baseada em **verde / amarelo / vermelho**.

---

## 📦 Instalação

### Com Maven

```xml
<dependency>
  <groupId>com.github.matheusknaul</groupId>
  <artifactId>trafficlight</artifactId>
  <version>1.0.0</version>
</dependency>
```

### Com Gradle

### 📦 Instalação via Gradle

```groovy
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.matheusknaul:trafficlight:1.0.0'
}
```