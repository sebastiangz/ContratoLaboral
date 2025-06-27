# Generador de Contratos Laborales v2.0 - México

## 📋 Descripción
Programa desarrollado en Python para generar contratos laborales con base en la normatividad vigente. Permite crear diferentes tipos de contratos, exportarlos a Word con marca de agua personalizable y proporciona sugerencias automáticas según el tipo de contrato seleccionado.

## 🚀 Características Principales

- **Tipos de contratos soportados:**
  - Indefinido/Permanente
  - Temporal/Plazo Fijo
  - Por Obra o Servicio
  - Aprendizaje/Prácticas
  - Tiempo Parcial
  - Eventual/Ocasional
  - De Temporada

- **Funcionalidades:**
  - Interfaz gráfica intuitiva con pestañas organizadas
  - Sugerencias automáticas según el tipo de contrato
  - Generación de documentos Word (.docx)
  - Marca de agua personalizable
  - Vista previa del contrato antes de generar
  - Guardado y carga de datos en formato JSON
  - Validación de campos obligatorios

## 🛠️ Requisitos del Sistema

- **Sistema Operativo:** Windows 10 o Windows 11
- **Python:** Versión 3.7 o superior
- **Espacio en disco:** Mínimo 100 MB libres

## 📦 Instalación

### Paso 1: Verificar Python
Abre el **Símbolo del sistema** (CMD) o **PowerShell** y ejecuta:
```bash
python --version
```
Si no tienes Python instalado, descárgalo desde: https://www.python.org/downloads/

### Paso 2: Crear directorio del proyecto
```bash
mkdir GeneradorContratos
cd GeneradorContratos
```

### Paso 3: Crear entorno virtual (recomendado)
```bash
python -m venv venv
venv\Scripts\activate
```

### Paso 4: Instalar dependencias
Guarda el archivo `requirements.txt` en la carpeta del proyecto y ejecuta:
```bash
pip install -r requirements.txt
```

### Paso 5: Ejecutar el programa
Guarda el archivo `generador_contratos.py` y ejecuta:
```bash
python generador_contratos.py
```

## 📚 Manual de Uso

### 1. Información General
- **Tipo de Contrato:** Selecciona el tipo de contrato deseado
- **Información del Empleador:** Completa los datos de la empresa
- **Información del Trabajador:** Ingresa los datos del empleado
- **Información del Puesto:** Define el cargo y funciones
- **Panel de Sugerencias:** Revisa las recomendaciones automáticas

### 2. Condiciones Laborales
- **Fechas:** Establece inicio y fin del contrato (si aplica)
- **Jornada:** Define horarios y modalidad de trabajo
- **Ubicación:** Especifica el lugar de trabajo
- **Período de Prueba:** Configura la duración (opcional)

### 3. Aspectos Económicos
- **Salario:** Ingresa el salario base y moneda
- **Beneficios:** Lista beneficios adicionales
- **Forma de Pago:** Selecciona método y periodicidad

### 4. Configuración y Generación
- **Marca de Agua:** Personaliza el texto de la marca de agua
- **Vista Previa:** Revisa el contrato antes de generar
- **Generar:** Crea el documento Word final
- **Guardar/Cargar:** Administra plantillas de datos

## 🎯 Flujo de Trabajo Recomendado

1. **Seleccionar tipo de contrato** → Las sugerencias se actualizan automáticamente
2. **Completar información básica** → Empleador, trabajador y puesto
3. **Configurar condiciones laborales** → Horarios, fechas, modalidad
4. **Definir aspectos económicos** → Salario y beneficios
5. **Revisar vista previa** → Verificar que toda la información esté correcta
6. **Generar contrato** → Crear el documento Word final
7. **Guardar datos** → Para reutilizar en futuros contratos similares

## ⚡ Características Inteligentes

### Sugerencias Automáticas
- El sistema proporciona recomendaciones específicas según el tipo de contrato
- Se autocompletan campos cuando es apropiado
- Se sugieren duraciones y condiciones típicas

### Validación de Datos
- Campos obligatorios resaltados
- Verificación de fechas coherentes
- Formato de datos apropiado

### Flexibilidad
- Funciona con información parcial
- Genera contratos coherentes incluso con datos faltantes
- Permite personalización completa

## 📝 Tipos de Contratos Específicos

### Contrato Indefinido/Permanente
- **Duración:** Sin límite de tiempo
- **Características:** Estabilidad laboral, beneficios completos
- **Sugerencias:** Período de prueba, beneficios de ley, funciones permanentes

### Contrato Temporal/Plazo Fijo
- **Duración:** 1-3 años típicamente
- **Características:** Renovable, fechas específicas
- **Sugerencias:** Fechas exactas, posibilidad de renovación

### Contrato por Obra o Servicio
- **Duración:** Hasta completar proyecto
- **Características:** Vinculado a entregables
- **Sugerencias:** Descripción detallada, hitos, criterios de finalización

### Contrato de Aprendizaje
- **Duración:** 6 meses - 2 años
- **Características:** Formación + trabajo
- **Sugerencias:** Programa formativo, supervisor, evaluaciones

## 🔧 Solución de Problemas

### Error al generar documento Word
- Verificar que python-docx esté instalado
- Comprobar permisos de escritura en el directorio destino
- Asegurar que no hay archivos abiertos con el mismo nombre

### Campos no se guardan
- Verificar que todos los campos requeridos estén completos
- Comprobar formato de fechas (DD/MM/YYYY)
- Revisar caracteres especiales en nombres de archivo

### Marca de agua no aparece
- La marca de agua se coloca en el encabezado
- Puede ser necesario ajustar la visualización en Word
- Verificar que el texto no esté vacío

## 💡 Consejos de Uso

1. **Completa información progresivamente:** Utiliza las pestañas en orden
2. **Revisa las sugerencias:** Siempre verifica las recomendaciones automáticas
3. **Usa la vista previa:** Revisa el contrato antes de generar el documento final
4. **Guarda plantillas:** Crea plantillas para tipos de contratos frecuentes
5. **Personaliza la marca de agua:** Ajusta según tu empresa o necesidades

## 📞 Soporte

Para soporte técnico o consultas sobre el uso del programa:
- Revisar este manual de usuario
- Verificar los logs de error en la consola
- Comprobar que todas las dependencias estén instaladas

## 🔄 Actualizaciones

Para mantener el programa actualizado:
1. Verificar nuevas versiones de las dependencias
2. Revisar cambios en la normatividad laboral
3. Actualizar plantillas según nuevos requerimientos legales

## ⚖️ Consideraciones Legales

- Este programa es una herramienta de asistencia para la creación de contratos
- Siempre consultar con un abogado laboralista para casos específicos
- Verificar que el contrato cumple con la legislación local vigente
- Mantener actualizadas las cláusulas según cambios normativos

---

**Versión:** 1.0  
**Fecha:** Junio 2025  
**Desarrollado por:** Infraestructura GIS  
**Sitio web:** www.infraestructuragis.com