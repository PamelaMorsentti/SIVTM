# SIVTM_CONTEXT.md

# ===================================================================
# SIVTM - CONTEXTO GENERAL DEL PROYECTO
# Documento Maestro de Continuidad
# ===================================================================

Versión: 0.1.0

Estado:
Activo

Última actualización:
09/07/2026

Proyecto:
Sistema Inteligente de Verificación Técnica Municipal (SIVTM)

Repositorio:
SIVTM

Autor funcional:
Dirección de Obras Privadas y Planeamiento
Municipalidad de Colón
Entre Ríos
Argentina

Arquitectura funcional:
Proyecto desarrollado conjuntamente entre la Dirección de Obras Privadas y ChatGPT (OpenAI).

====================================================================

# PROPÓSITO DE ESTE DOCUMENTO

Este archivo constituye la memoria permanente del proyecto.

Su finalidad es permitir que cualquier desarrollador o sistema de Inteligencia Artificial pueda comprender rápidamente:

- qué es el proyecto;
- por qué existe;
- qué decisiones ya fueron tomadas;
- cuál es el estado actual;
- qué documentación existe;
- qué resta desarrollar.

Este documento debe actualizarse al finalizar cada sesión de trabajo.

====================================================================

# MISIÓN DEL PROYECTO

Construir una plataforma integral para asistir técnicamente a los municipios durante todo el ciclo de vida de los expedientes de Obras Privadas.

El sistema permitirá verificar automáticamente el cumplimiento de la normativa urbanística, edilicia y administrativa, integrando información catastral, territorial y documental mediante un motor de reglas explicable y trazable.

====================================================================

# VISIÓN

El SIVTM no será únicamente un software para revisar planos.

Será una plataforma de gestión del conocimiento técnico municipal.

El objetivo final es preservar el conocimiento institucional, automatizar verificaciones objetivas y facilitar la gestión territorial mediante inteligencia artificial, reglas normativas y sistemas geográficos.

El proyecto está pensado para ser reutilizable por otros municipios.

====================================================================

# PROBLEMAS QUE BUSCA RESOLVER

Actualmente la revisión técnica presenta dificultades como:

- Expedientes predominantemente en papel.
- Planos PDF escaneados.
- Falta de protocolos digitales.
- Verificaciones repetitivas.
- Criterios técnicos no documentados.
- Dependencia del conocimiento individual del revisor.
- Dificultad para consultar antecedentes históricos.
- Escasa integración entre Catastro, Expedientes y GIS.

====================================================================

# FILOSOFÍA DEL PROYECTO

El sistema nunca reemplazará el criterio técnico municipal.

Su función será:

- asistir;
- verificar;
- documentar;
- fundamentar;
- explicar;
- registrar.

La decisión final siempre corresponderá al profesional responsable.

====================================================================

# PRINCIPIOS FUNDAMENTALES

PF-001
El Catastro Municipal constituye la Fuente Única de Verdad.

PF-002
El objeto principal del sistema es el INMUEBLE.

PF-003
Los expedientes representan actuaciones administrativas sobre un inmueble.

PF-004
Toda observación debe poseer evidencia.

PF-005
Toda conclusión debe poder explicarse.

PF-006
Toda regla debe estar respaldada por una norma.

PF-007
Todo dato debe ser trazable.

PF-008
Toda decisión importante debe quedar documentada.

PF-009
La Inteligencia Artificial nunca reemplaza al profesional.

PF-010
La documentación tiene prioridad sobre el código.

PF-011
Primero se modela.
Luego se programa.

====================================================================

# ESTADO ACTUAL DEL PROYECTO

Fase:

INGENIERÍA CONCEPTUAL

No existe desarrollo de software.

Actualmente se está diseñando:

- Modelo del Dominio.
- Modelo Administrativo.
- Modelo Territorial.
- Modelo Normativo.
- Arquitectura General.
- Ontología Municipal.

====================================================================

# DECISIONES IMPORTANTES TOMADAS

D-0001

El proyecto se desarrollará desde la documentación hacia el código.

------------------------------------------------------------

D-0002

Toda decisión deberá registrarse.

------------------------------------------------------------

D-0003

La documentación será versionada mediante Git.

------------------------------------------------------------

D-0004

El sistema será modular.

------------------------------------------------------------

D-0005

Se distinguen dos modelos principales:

Modelo Administrativo.

Modelo Técnico.

------------------------------------------------------------

D-0006

El expediente municipal posee un número único otorgado por Mesa de Entradas.

No contiene el año.

Ejemplo:

583520

------------------------------------------------------------

D-0007

El Legajo de Obra constituye un identificador independiente.

Ejemplo:

151/26

Puede repetirse cada año.

Se genera luego de la Visación.

------------------------------------------------------------

D-0008

El Catastro Municipal constituye la fuente oficial de información territorial.

------------------------------------------------------------

D-0009

El Visor Urbano será integrado como módulo SIG del SIVTM.

No será un sistema independiente.

------------------------------------------------------------

D-0010

El historial técnico se organizará alrededor del inmueble y no del expediente.

====================================================================

# MODELOS PRINCIPALES

Actualmente el sistema se divide conceptualmente en:

MDEM

Modelo del Expediente Municipal.

------------------------------------------------------------

MTEM

Modelo Técnico Edilicio.

------------------------------------------------------------

MTCM

Modelo Territorial y Catastral.

------------------------------------------------------------

MNM

Modelo Normativo Municipal.

====================================================================

# MÓDULOS PREVISTOS

01 Gestión de Expedientes

02 Catastro

03 SIG Municipal

04 Modelo Territorial

05 Modelo Administrativo

06 Modelo Técnico

07 Motor Normativo

08 Motor de Reglas

09 Motor de Evidencias

10 Motor de Checklists

11 Repositorio de Conocimiento Municipal

12 Inteligencia Artificial

13 Portal Profesional

14 Portal Municipal

15 Administración

16 API

17 Reportes

====================================================================

# OBJETO CENTRAL

Todo el sistema gira alrededor del objeto:

INMUEBLE

Cada inmueble concentrará:

- ubicación;
- datos catastrales;
- nomenclatura;
- zonificación;
- indicadores urbanísticos;
- restricciones;
- antecedentes;
- fotografías;
- expedientes;
- inspecciones;
- proyectos;
- planos;
- liquidaciones;
- habilitaciones;
- normativa aplicable.

====================================================================

# REPOSITORIO DE CONOCIMIENTO

Se construirá una base de conocimiento municipal.

Cada concepto tendrá:

- definición;
- relaciones;
- normativa;
- verificaciones;
- ejemplos;
- excepciones;
- criterios administrativos;
- documentación relacionada.

Ejemplos:

INMUEBLE

PARCELA

MANZANA

OCHAVA

FOS

FOT

LINEA MUNICIPAL

RETIRO

AMBIENTE

ESCALERA

LOCAL COMERCIAL

etc.

====================================================================

# DOCUMENTACIÓN DISPONIBLE

Actualmente el proyecto posee:

README.md

ProyectoMaestro.md

SIVTM_CONTEXT.md

En elaboración:

Arquitectura.md

ModeloNormativo.md

ModeloDominio.md

RepositorioConocimiento.md

ModeloTerritorial.md

ProtocoloPresentacionDigital.md

Roadmap.md

====================================================================

# DOCUMENTACIÓN DEL EXPEDIENTE MUNICIPAL

El expediente podrá contener, entre otros:

- Nota de presentación.
- Reporte de inmueble.
- Plano de mensura.
- Escritura.
- Solicitud de número de finca.
- Planilla de niveles.
- Conocimiento legislación laboral.
- Arbolado público.
- Planos antecedentes.
- Memorias técnicas.
- Aportes profesionales.
- Planillas ATER.
- Planillas de categorización.
- Presupuesto.
- Memorias de cálculo.
- Higiene y Seguridad.
- Planos.
- Fotografías.
- Inspecciones.
- Liquidaciones.
- Dictámenes.
- Resoluciones.
- Poderes.
- Declaratorias.
- Fideicomisos.
- Documentación judicial.

====================================================================

# PRESENTACIÓN DIGITAL

Actualmente el Municipio recibe principalmente:

PDF

y documentación en papel.

Objetivo futuro:

PDF vectorial obligatorio.

DWG o DXF normalizado.

Protocolo CAD.

Capas normalizadas.

Verificación previa automática.

Firma digital.

====================================================================

# TECNOLOGÍAS PREVISTAS

Python

FastAPI

PostgreSQL

PostGIS

QGIS

Leaflet / OpenLayers

OCR

LLM

Git

Docker

====================================================================

# PRÓXIMO OBJETIVO

Diseñar completamente el

MODELO DEL INMUEBLE

Será la base para:

Modelo Territorial.

Modelo Catastral.

Modelo del Proyecto.

Modelo del Plano.

Modelo Normativo.

====================================================================

# REGLA DE ORO DEL PROYECTO

El proyecto nunca dependerá de una conversación.

Toda decisión deberá quedar incorporada a la documentación oficial del repositorio.

====================================================================

FIN DEL DOCUMENTO
