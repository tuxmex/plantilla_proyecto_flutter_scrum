---
title: Revisión de Sprint [Fecha] - Evaluación Flutter
labels: revision, sprint, flutter
assignees: instructor_usuario
---

## 📝 Descripción
Revisar el sprint de dos semanas del equipo, verificando cumplimiento de historias,
calidad del código Flutter, uso de Git/GitHub y ceremonias Scrum.

**Sprint:** [Fecha inicio] → [Fecha fin]

## ✅ Checklist de Evaluación

### 1. Gestión del Tablero (GitHub Projects / Trello)
- [ ] Tarjetas del sprint en **Done** o justificadas en **In Progress**.
- [ ] Cada tarjeta con responsable asignado.
- [ ] Criterios de aceptación claros por historia.
- [ ] Movimiento de tarjetas evidenciado durante el sprint.
- [ ] Story points / estimación asignada.

### 2. Repositorio y Flujo Git
- [ ] Commits frecuentes con mensajes descriptivos (Conventional Commits idealmente).
- [ ] Ramas por funcionalidad (`feature/…`, `fix/…`).
- [ ] Pull Requests revisados por al menos otro compañero.
- [ ] Issues vinculados a tarjetas del tablero.
- [ ] `pubspec.lock` versionado (es app, no package).

### 3. Calidad de Código Flutter
- [ ] `flutter analyze` sin errores (warnings aceptables y justificados).
- [ ] `dart format` aplicado (CI pasa el check de formato).
- [ ] Widgets organizados en carpetas (`screens/`, `widgets/`, `models/`).
- [ ] Uso correcto de `const` donde aplique.
- [ ] Sin `print()` en producción (usar `debugPrint` o logger).
- [ ] `analysis_options.yaml` configurado con reglas del equipo.

### 4. Pruebas
- [ ] Al menos 1 test unitario o de widget por historia nueva.
- [ ] `flutter test` pasa en CI (✅ en el PR).
- [ ] Cobertura de tests reportada (objetivo mínimo: ___ %).
- [ ] Pruebas manuales documentadas si no hay automatizadas.

### 5. Entregables del Sprint
- [ ] Incremento **funcional** demostrable (APK, emulador, video o deploy).
- [ ] Historias terminadas según Definition of Done del equipo.
- [ ] Screenshots o video de la demo adjuntos.
- [ ] README actualizado con instrucciones de ejecución (`flutter pub get`, `flutter run`).

### 6. Ceremonias Scrum
- [ ] Daily registrado (fecha, avances, bloqueos).
- [ ] Sprint Review con evidencia (capturas, demo, video).
- [ ] Retrospectiva con al menos 1 acción de mejora concreta.
- [ ] Burndown o gráfico de avance actualizado.

### 7. Trabajo en Equipo
- [ ] Participación equilibrada en commits (no solo 1 persona).
- [ ] Roles Scrum definidos (PO, SM, Dev Team).
- [ ] Bloqueos reportados y resueltos o escalados.

## 🎯 Criterios de Aceptación del Sprint
- [ ] ≥ 80% de los story points planificados completados.
- [ ] CI en verde (`flutter analyze` + `flutter test`) en la rama `main`.
- [ ] Demo del incremento realizada ante instructor o PO.
- [ ] Retrospectiva documentada con acción de mejora.

## 📎 Enlaces de Entrega
- **Tablero:** 
- **Repositorio (rama main):** 
- **Último PR mergeado:** 
- **Demo / Video:** 
- **Acta de Retrospectiva:** 

---
*Issue creado automáticamente por GitHub Actions.*