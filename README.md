# Prototipo estático de Talenti

Un "Figma hecho en HTML": todas las pantallas de Talenti con datos de muestra (inventados). No guarda nada ni calcula nada; los botones solo llevan a otra pantalla.

## Cómo abrirlo
Doble clic en `index.html`. No necesita servidor ni internet (las tipografías van en `assets/fonts`).

## Las tres caras
- **Estudiante** (`estudiante/`): visitante y con sesión (perfil, compatibilidad, DORA por voz, examen, entrevista, cuenta).
- **Empresa** (`empresa/`): panel, vacantes, postulantes, resultados, informes y cuenta.
- **Administrador** (`admin/`): usuarios, empresas, vacantes, planes, consumo de IA, legales, auditoría, incidencias y configuración.

En el ingreso eliges el rol y el botón te lleva a su cara (solo navegación, sin validación). Cada pantalla tiene arriba "Volver al inicio del prototipo".

## Nota
Las páginas se generan desde plantillas que viven en el repositorio de planos del proyecto; aquí solo está el resultado estático. Los componentes y el estilo están explicados en `_guia.html`.

## Sin lógica
Solo HTML y CSS (diálogos con `:target`, acordeones con `details`, animaciones con `@keyframes`). No hay JavaScript.
