

# 🧠 Directo con Martín Cristóbal

Conversación con **Martín Cristóbal**, profesor del máster, sobre buenas prácticas en ingeniería de software, requisitos, metodologías ágiles y gestión de proyectos.

---

## 📋 Definición de requisitos

**Pregunta:** En un nuevo proyecto, ¿los objetivos y requisitos siempre deben medirse?  
**Respuesta:**

- Definir requisitos es como una negociación.
    
- A veces hay que explicar al cliente las limitaciones técnicas y proponer alternativas realistas.
    
- Lo ideal es **comprender profundamente el negocio del cliente** para ofrecer soluciones ajustadas.
    

**Pregunta:** ¿Existen documentos estándar para escribir requisitos?  
**Respuesta:**

- Lo más habitual son **historias de usuario** y **criterios de aceptación**, heredados de **SCRUM**.
    
- Martín recomienda:
    
    1. Empezar con un documento en **lenguaje natural (Word)**.
        
    2. Convertirlo luego en **historias de usuario**.
        
    3. Mantener todo **bien documentado** para justificar decisiones futuras.
        

---

## 🔄 Metodologías y enfoques de desarrollo

**Pregunta:** Diferencia entre iterativo, incremental y espiral.  
**Respuesta:**

- **Iterativo:** mejoras sucesivas del producto final (patinete → bici → moto → coche).
    
- **Incremental:** desarrollo por partes o módulos (ruedas, motor, ensamblado).
    
- **Espiral:** se hacen pruebas de alto riesgo, por ejemplo probar una nueva pasarela de pago en una branch aparte.
    

---

## ☁️ Estrategia en proyectos SaaS

**Pregunta:** ¿Qué se desarrolla primero, el panel de administración o el SaaS en sí?  
**Respuesta:**

- Se recomienda **iterar ambos en paralelo**.
    
- Ejemplo: un SaaS de notas tipo _Notion_ →
    
    - Feature: crear una nota.
        
    - Derivada: necesidad de moderar publicaciones.
        
- Pensar en **features completas** con su parte funcional y administrativa.
    

---

## 🧪 Testing y calidad

**Pregunta:** ¿Cómo aplicar TDD cuando los requisitos cambian mucho?  
**Respuesta:**

- TDD se organiza en una pirámide:
    
    1. Tests **unitarios**
        
    2. Tests de **integración**
        
    3. Tests **end-to-end**
        
- Los tests unitarios pueden acoplarse demasiado al código.
    
- Martín comenta que **a veces es mejor centrarse en tests de integración** (por ejemplo, contra una base de datos falsa).
    

**Pregunta:** ¿Qué opinas de los tests de regresión visual?  
**Respuesta:**

- “En mi experiencia, no merecen la pena” — pueden fallar con facilidad.
    

---

## 📘 Estándares y documentación

**Pregunta:** ¿Se sigue utilizando el estándar IEEE 830?  
**Respuesta:**

- Ya no se usa mucho. Se prefiere trabajar con **historias de usuario**.
    
- Los estándares demasiado formales no suelen funcionar bien en entornos colaborativos.
    

**Pregunta:** ¿Qué debería incluir el `README.md`?  
**Respuesta:**

- Instrucciones para **ejecutar el proyecto**.
    
- Carpeta `design_docs/` con todos los archivos de requisitos.
    

---

## 🤝 Trabajo con clientes y cambios de requisitos

**Pregunta:** ¿Cómo lidiar con empresas que cambian los requisitos constantemente?  
**Respuesta:**

- Muy común, especialmente en startups.
    
- Claves:
    
    - Mantener una **visión clara del producto**.
        
    - Hacer **encuestas a usuarios** para entender necesidades reales.
        
    - No seguir ciegamente las directrices del cliente: **entender primero el problema**.
        
    - Reunir a negocio para **priorizar y agrupar cambios**.
        
    - Evitar desgaste con **buena gestión del producto**.
        

**Pregunta:** ¿Cómo cotizar proyectos cuando los requisitos cambian durante el desarrollo?  
**Respuesta:**

- Cobrar **por horas de trabajo** e incluir un **buffer de seguridad**.
    
- Si se esperan cambios frecuentes:
    
    - Facturar revisiones aparte.
        
    - Firmar requisitos iniciales y establecer que cualquier cambio **se paga mediante anexo**.
        
    - Si el cliente no acepta, dejar que lo desarrolle otro.
        

---

## ⚙️ Trabajo con legacy code

**Pregunta:** ¿Cómo integrar código legacy en nuevos proyectos?  
**Respuesta:**

- Puede integrarse de forma funcional, como un módulo que se conecta a una herramienta existente.
    
- Documentar la integración y dejar un **ticket de deuda técnica**.
    

---

## 🧍‍♂️ Entrevistas con usuarios

**Pregunta:** ¿Qué preguntas son imprescindibles al entrevistar usuarios?  
**Respuesta:**

- La pregunta más importante:
    
    > “¿Cuál es el problema? ¿Qué intentas conseguir?”
    
- A veces los usuarios **piden una cosa pero necesitan otra**.
    
- Comprender a fondo el negocio es clave.
    

---

## ⚖️ MVP, principios y deuda técnica

**Pregunta:** ¿Cómo equilibrar un MVP funcional sin caer en sobreingeniería?  
**Respuesta:**

- No aplicar SOLID a rajatabla desde el inicio.
    
- En las primeras fases, **código suficientemente bueno** es preferible.
    
- Evitar deuda técnica grave y priorizar principios críticos como **separación de responsabilidades**.
    

---

## ⏱️ Gestión del tiempo y estimaciones

**Pregunta:** ¿Cómo manejar la presión por dar fechas exactas de entrega?  
**Respuesta:**

- No hay una fórmula mágica.
    
- Dividir el trabajo en **bloques de medio día**.
    
- **Inflar un 15-20% las estimaciones.**
    
- Regla de oro: _underpromise and overdeliver_.
    

---

## 🧩 Prototipos y POCs

**Pregunta:** ¿Hasta qué punto usar POCs en proyectos ágiles?  
**Respuesta:**

- Si un POC se valida, **convertirlo en producto real cuanto antes**.
    
- Activarlo progresivamente y documentar bien los aprendizajes.
    

---

## 💬 Documentación y herramientas de IA

**Pregunta:** ¿Cómo documentas tu código? ¿Usas herramientas de IA?  
**Respuesta:**

- Uso de **Markdown** y herramientas como **Claude Code** para generar:
    
    - Requisitos
        
    - Tareas
        
    - Plantillas (_boilerplates_)
        

---

## 🧱 Anti-patrones y gestión de equipos

**Pregunta:** ¿Qué hacer cuando el ciclo de vida del software parece “cascada disfrazada de ágil”?  
**Respuesta:**

- Evitar que los equipos esperen “soluciones mágicas”.
    
- Implementar **monitoreo de uso** (ej. Posthog).
    
- Recordar que conocer SCRUM no significa que el desarrollo vaya más rápido.
    

---

## 🧠 Buenas prácticas y recursos recomendados

**Pregunta:** ¿Repositorios útiles para aprender buenas prácticas y patrones de diseño?  
**Respuesta:**

- [Build Your Own X](https://github.com/codecrafters-io/build-your-own-x)
    
- [Patterns.dev](https://www.patterns.dev/)
    
- [Refactoring Guru](https://refactoring.guru/design-patterns)
    
- [DevDocs.io](https://devdocs.io/)
    

-