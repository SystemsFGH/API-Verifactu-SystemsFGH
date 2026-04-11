# ⚖️ Aviso Legal, Privacidad y Condiciones de Uso

**VeriFactu MicroServer** (en adelante, el "Software") y sus servicios asociados están supeditados a las siguientes condiciones, establecidas para proteger tanto a los usuarios integradores como a la propiedad intelectual e infraestructura técnica del sistema.

---

## 1. AVISO LEGAL Y CONDICIONES DE USO

### 1.1 Condiciones Generales y Titularidad
En cumplimiento con el deber de información general, se informa que el software asociado y sus componentes son propiedad, mantenidos y operados de forma independiente por **Fernando Gallego**, persona física con DNI 05616281A, con correo electrónico de contacto: [admin@systemsfgh.com](mailto:admin@systemsfgh.com).

### 1.2 Carácter No Comercial (Fase de Prueba)
El presente repositorio y software no realiza ninguna actividad económica transaccional. La distribución del software "VeriFactu MicroServer" se ofrece actualmente en calidad de evaluación y prueba (TRIAL/BETA) con una licencia gratuita de duración temporal (18 meses). El desarrollador no actúa bajo ningún régimen societario ni mercantil durante esta etapa de distribución gratuita.

### 1.3 Cláusula de Exención de Responsabilidad Absoluta (Disclaimer)
> **⚠️ IMPORTANTE:** El Software de integración fiscal se proporciona en estado **"TAL CUAL" (AS-IS) y "SEGÚN DISPONIBILIDAD"**, sin garantías de ningún tipo, ni explícitas ni implícitas, incluyendo, entre otras, las garantías de idoneidad para un propósito particular comercial o de cumplimiento normativo absoluto ininterrumpido.

Al descargar y utilizar la licencia gratuita de prueba, **el usuario o empresa integradora acepta y asume todo el riesgo derivado de su uso**. En ningún caso Fernando Gallego será legalmente responsable de daños directos, indirectos, lucro cesante, requerimientos, inspecciones o sanciones económicas de la Agencia Tributaria (AEAT) ni pérdidas causadas por el uso, incapacidad de uso, fallos de las integraciones síncronas o asíncronas, lentitud, caídas de servidor o errores de emisión de facturas derivadas del uso o mal uso de este Software. El usuario técnico final es el único responsable de validar las firmas, hashes y envíos fiscales ante la Administración.

### 1.4 Declaración Responsable del Sistema Informático
El Software incorpora las plantillas y definiciones técnicas necesarias para la "Declaración Responsable" del sistema informático, exigencia ineludible por la normativa VeriFactu. Por diseño e imperativo legal, el Panel de Control limitará sus opciones; **aunque sí permite el registro inicial de licencias y el libre acceso a la documentación técnica**, el resto de las funciones operativas estarán bloqueadas hasta que el usuario integrador haya definido y completado los datos de parametrización de su sistema informático.

> **⚖️ Aclaración Legal:** Debe quedar constancia expresa de que se considera «Sistema Informático», a todos los efectos legales y tributarios, **el ERP, TPV o software de gestión de cualquier tipo que haga uso de este motor (MicroServer)**. Esto se debe a que, por mandato legal, es ese software de gestión en su conjunto (y su fabricante/integrador) la entidad productora que emite oficialmente la Declaración Responsable y de Certificación ante la Administración Estatal.

Puede consultar la publicación normativa que rige este aspecto en el [Boletín Oficial del Estado (Art. 15)](https://www.boe.es/buscar/act.php?id=BOE-A-2023-24840#a1-5).

---

## 2. POLÍTICA DE PRIVACIDAD Y PROTECCIÓN DE DATOS (RGPD)

### 2.1 Responsable del Tratamiento de Datos
De conformidad con lo dispuesto en el Reglamento General de Protección de Datos (RGPD) aplicable a la UE, se informa que Fernando Gallego, bajo el concepto de Persona Física desarrolladora, actuará como Responsable del Tratamiento de los datos mínimos requeridos para la generación y validación de las licencias.
Email de contacto y ejercicio de derechos: [admin@systemsfgh.com](mailto:admin@systemsfgh.com)

### 2.2 Finalidad de los Datos Recopilados
A través de las peticiones API y validación de licencias, únicamente se recopilará la siguiente información de forma estricta:
*   Direcciones de correo electrónico (solamente si se proporcionan voluntariamente para solicitar la llave de uso o registro).
*   Hardware ID o Identificador Anónimo de máquina para restringir el límite de emisiones vinculadas a la licencia de evaluación de 18 meses.
*   Direcciones IP con efecto limitativo (Prevención de ataques y Rate Limiting).

> **🛡️ Resguardo de la Privacidad de la Información:**
> La aplicación MicroServer se ejecuta localmente en el entorno del usuario. SystemsFGH no procesa el contenido de sus facturas ni almacena sus Certificados Electrónicos de la FNMT, los cuales en todo momento permanecen bajo ejecución local en la infraestructura física (On-Premise) del integrador. **El usuario es el único responsable del uso de la aplicación y del cumplimiento de sus obligaciones legales de protección de datos y de carácter fiscal ante la Administración.**

### 2.3 Derechos ARCO y Conservación
Los datos técnicos se usarán estrictamente para el mantenimiento del servicio temporal y soporte mientras dure la licencia. No se cederán datos a terceros bajo ninguna circunstancia, salvo imperativo legal. Puede ejercer sus derechos de acceso, rectificación, supresión y limitación de datos ("Derechos ARCO") remitiendo una solicitud formal a [admin@systemsfgh.com](mailto:admin@systemsfgh.com).

### 2.4 Política de Cookies y Analítica Web (Portal asociado)
El portal web principal asociado a este repositorio emplea cookies técnicas necesarias para el mantenimiento seguro de la sesión del usuario. Adicionalmente, de forma opcional y sujeta a consentimiento expreso previo, el sitio emplea Google Analytics para realizar mediciones estadísticas anónimas sobre la navegación almacenadas temporalmente (`localStorage`). Usted es totalmente libre de rechazar esta carga estadística sin que el servicio central merme sus capacidades operativas.

---

## 3. PROYECCIÓN ESTRATÉGICA, ROADMAP TECNOLÓGICO Y TRANSICIÓN SOCIETARIA

La presente fase de distribución del Software en su estadio de evaluación y operado de forma individual tiene un carácter estrictamente temporal de maduración técnica. A futuro, la evolución del proyecto está planificada bajo dos ejes convergentes y mutuamente compatibles:

**A. Vía Open Source (Apertura progresiva y compromiso de liberación)**
Nuestro plan estratégico a medio plazo pasa por liberar la mayor parte —o la totalidad— del motor central de enrutamiento y encadenamiento del servicio bajo licencia MIT. Esta liberación del código núcleo se ejecutará cuando el sistema haya alcanzado una cota de orquestación, estabilización técnica y escalabilidad absoluta en escenarios reales de producción. Asimismo, se adquiere un compromiso irrenunciable: en el supuesto hipotético de que el proyecto no llegase a dar el salto ni a escalar hacia la configuración organizativa del sistema empresarial corporativo detallado a continuación, el bloque de código del microservicio actual —el cual cuenta ya con la madurez suficiente para operar en entornos Legacy— será íntegramente liberado al dominio público bajo licencia MIT, garantizando que el esfuerzo invertido quede en manos de la base de desarrolladores y no suponga nunca un código cautivo.

**B. Vía Explotación Comercial (Servicios de Valor Añadido)**
En paralelo (y en caso de progreso exitoso), el desarrollo del ecosistema se blindará para soportar explotaciones comerciales de alto rendimiento corporativo, expandiendo la plataforma hacia servicios críticos adicionales in-cloud o híbridos, e incorporando por diseño tecnologías colindantes obligatorias como redes paneuropeas de Facturación Electrónica B2B.

**Transición de la Personalidad Jurídica Limitada**
Debe quedar meridianamente claro que, la situación actual de titularidad civil se circunscribe exclusivamente a la etapa de maduración de laboratorio descrita. En el instante en el que se inicie la explotación comercial en firme, el cobro por licenciamiento y la puesta en marcha de servicios añadidos en escalón de producción masiva, la integralidad del dominio web, infraestructura, operativa civil e intelectual de este proyecto traspasará su titularidad a una Empresa Mercantil formalmente constituida al efecto en España. Esta futura Sociedad Comercial absorberá la responsabilidad y validación fiscal operando corporativamente para integradores con las plenas garantías legales del Estado.
