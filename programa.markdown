---
layout: page
title: Programa
permalink: /programa/
---

## Fundamentos transversales

*Marco teórico común a todas las áreas del curso. Establece los modelos y abstracciones necesarias para razonar sobre sistemas donde las fallas parciales, la ausencia de relojes globales y la concurrencia son la norma.*

- Modelos arquitectónicos: cliente-servidor y peer-to-peer
- Remote Procedure Call
- Modelos sincrónicos y asincrónicos
- Semánticas de entrega
- Causalidad y tiempo
- Relojes lógicos y vectoriales
- Estado global y cortes del sistema
- Modelos de consistencia
- Modelos de falla
- Tolerancia a fallos
- Coordinación y consenso

## Áreas de aplicación

*Los contenidos se organizan en cuatro áreas de aplicación que no son independientes entre sí: los mismos problemas de consenso, replicación y consistencia aparecen en todas ellas. La división busca claridad pedagógica, no fronteras rígidas.*

## Área 1 — Compute

*Cómo coordinar múltiples nodos para ejecutar trabajo de forma correcta, eficiente y tolerante a fallos, desde paradigmas clásicos hasta las demandas modernas del machine learning a escala.*

- Paradigmas de cómputo distribuido
- Distribución y coordinación de tareas
- Detección y recuperación de fallos
- Cómputo batch y sus limitaciones

## Área 2 — Storage

*Persistir datos en múltiples nodos implica navegar trade-offs fundamentales entre consistencia, disponibilidad y performance. Esta área estudia cómo los sistemas reales resuelven esos trade-offs, desde filesystems hasta bases de datos globalmente distribuidas.*

- Filesystems distribuidos
- Replicación y sharding
- Replicación por máquina de estados distribuida
- Transacciones distribuidas
- Consistencia en caches
- Replicación y anti-entropía
- Trade-offs entre consistencia y disponibilidad

## Área 3 — Stream Processing

*Muchas decisiones no pueden esperar a un procesamiento batch. Esta área estudia cómo procesar flujos de datos en tiempo real con garantías semánticas precisas, y los modelos de mensajería que hacen posible la comunicación asíncrona a escala.*

- Mensajería distribuida y el log como estructura unificadora
- Message Oriented Middleware
- Modelos de comunicación: request-reply, publisher-subscriber
- Procesamiento de streams: tiempo de evento vs tiempo de procesamiento, watermarks, ventanas
- Modelo unificado batch y streaming
- Pipelines secuenciales y paralelos

## Área 4 — Cloud Computing

*El entorno donde todo lo anterior opera en producción. Esta área estudia cómo gestionar infraestructura a escala, obtener visibilidad sobre sistemas complejos y sostener confiabilidad cuando el hardware falla constantemente.*

- Infraestructura a escala: scheduling y orquestación de recursos
- Load balancing y routing
- Sistemas elásticos y escalado automático
- Cómputo efímero y serverless
- Observabilidad: métricas, logs y trazas distribuidas
- Principios de diseño y operabilidad de servicios a escala