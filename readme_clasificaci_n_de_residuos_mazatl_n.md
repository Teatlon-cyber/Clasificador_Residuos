# 🌊 Clasificador de Residuos Sólidos Urbano e Industrial - Mazatlán, Sinaloa

> **Proyecto de Desarrollo Sustentable | TecNM Campus Mazatlán**
>
> Investigación, análisis de impacto ambiental y desarrollo de un bot automatizado de Telegram con Visión por Computadora (IA) para la clasificación de residuos urbanos, peligrosos e industriales en Mazatlán.

## 👤 Información del Autor y Proyecto

* **Autor:** Julio Cesar Garcia Ceja
* **Institución:** Instituto Tecnológico de Mazatlán (TecNM)
* **Materia:** Desarrollo Sustentable
* **Fecha:** 29 de Octubre de 2026
* **Ubicación de Estudio:** Mazatlán, Sinaloa, México
* **🎥 Video Demostrativo:** [Ver demostración en YouTube](https://www.youtube.com/watch?v=UjVGkN-xdtM)

---

## 📌 Descripción General

Este proyecto integra un diagnóstico legal y socioambiental sobre la problemática de los residuos sólidos en Mazatlán con una solución tecnológica basada en **Inteligencia Artificial y Automatización no-code/low-code**.

El sistema permite a los usuarios enviar una fotografía de cualquier residuo a través de un bot de **Telegram**. Un agente de Inteligencia Artificial analiza la imagen en tiempo real, clasifica el residuo con criterio normativo local (*LGPGIR*) y emite recomendaciones de manejo, disposición final y reportes ambientales.

---

## 🎥 Video Demostrativo del Funcionamiento

Puedes consultar la explicación completa del proyecto, la integración de la IA y la demostración del bot de Telegram en ejecución a través del siguiente enlace:

* 🎬 **Enlace al video:** [Demostración y Explicación del Bot - YouTube](https://www.youtube.com/watch?v=UjVGkN-xdtM)

---

## 📊 1. Marco Teórico e Investigación Previa

### Clasificación de Residuos en México (LGPGIR)

De acuerdo con la *Ley General para la Prevención y Gestión Integral de los Residuos (LGPGIR)*, la NOM-161-SEMARNAT-2011 y la NOM-083-SEMARNAT-2003, los residuos se dividen en tres grandes jurisdicciones:

| Categoría | Descripción | Ejemplos | Nivel de Gobierno | 
| ----- | ----- | ----- | ----- | 
| **Orgánicos (RSU)** | Residuos biodegradables de origen vegetal o animal. | Cáscaras de fruta/verdura, restos de comida, jardinería. | Municipal | 
| **Inorgánicos Reciclables (RSU)** | Materiales inorgánicos con potencial de valorización. | Botellas PET, vidrio, latas de aluminio, cartón/papel limpio. | Municipal / Centros de Acopio | 
| **Inorgánicos No Reciclables (RSU)** | Materiales de difícil reciclaje o contaminados. | Papel higiénico, pañales, unicel, envolturas metalizadas, colillas. | Municipal | 
| **Manejo Especial (RME)** | Grandes volúmenes (>10 t/año) o electrodomésticos. | Refrigeradores, colchones, escombro, muebles. | Estatal | 
| **Peligrosos (RP / CRETIB)** | Sustancias corrosivas, reactivas, explosivas, tóxicas o inflamables. | Pilas, aceites usados, hidrocarburos, medicamentos caducos, fertilizantes. | Federal (Semarnat / Profepa) | 

### Diagnóstico de la Gestión de Residuos en Mazatlán

1. **Generación Diaria:** Mazatlán genera entre **700 y 800 toneladas diarias** de basura, superando las **1,000 toneladas diarias** durante temporadas vacacionales.
2. **Infraestructura y Recolección:**
   * El servicio municipal carece de un sistema consolidado de recolección diferenciada por colores o días.
   * La separación depende del esfuerzo individual, recicladores informales y centros de acopio privados.
3. **Problemática del Basurón Municipal de Urías:**
   * Es un tiradero a cielo abierto con más de 40 años de operación ubicado cerca del Estero de Urías.
   * **Sanción y Clausura:** En diciembre de 2025, la **PROFEPA** multó al Ayuntamiento por más de 10.4 millones de pesos, ordenando la clausura definitiva en julio de 2026.
   * **Estatus Legal:** Continúa recibiendo residuos bajo un amparo legal judicial mientras el Gobierno de Sinaloa planifica la construcción de un nuevo relleno sanitario (inversión de 100 MDP).

### Impacto Ecológico en Canales Pluviales y el Mar

* **Estero de Urías:** Recibe basura y descargas de aguas negras a través de los canales pluviales que cruzan la ciudad, impactando un área de **873 hectáreas de manglar**.
* **Contaminación por Microplásticos:** Un estudio (2021) detectó microplásticos en el tracto digestivo del **55.2% de los peces analizados** en el estero (51.2% fibras de nailon y 36.6% polietileno). Investigaciones de la UNAM ubican los sedimentos del Estero de Urías con algunas de las concentraciones de microplásticos más altas a nivel mundial.
* **Obstrucción de Canales Pluviales:** Mazatlán cuenta con **42 km de canales y arroyos pluviales**. Tiraderos clandestinos de muebles, electrodomésticos y escombro tapan el paso del agua, generando inundaciones recurrentes en colonias vulnerables.

---

## 📝 2. Preguntas de Reflexión y Análisis Práctico

1. **¿Cuántos residuos se pueden reciclar/compostar y cuántos se separan en casa?**
   * *Análisis:* De una muestra representativa de 10 residuos, 5 son reciclables o compostables (orgánicos, PET, vidrio, aluminio, aceite usado). Sin embargo, en los hogares la separación real es baja debido a la falta de recolección diferenciada municipal, provocando que los residuos peligrosos domésticos (pilas y aceites) terminen en el drenaje o la basura común.

2. **¿Qué residuo sorprendió más por su tiempo de degradación?**
   * *Análisis:* El contraste entre desechos de peso similar: una cáscara de verdura se degrada en semanas, mientras que las pilas alcalinas tardan de 500 a 1,000 años liberando metales pesados. Un solo litro de aceite contamina hasta 1,000 litros de agua, creando películas hidrofóbicas en el Estero de Urías que asfixian la fauna marina.

3. **¿En qué casos se equivocó la Inteligencia Artificial?**
   * *Análisis:* La IA presentó sesgos en imágenes con iluminación deficiente, materiales mezclados (envases con restos de comida) o líquidos sin etiquetar (aceite vs. café). Asimismo, la IA ofrece consejos teóricos generales pero desconoce las limitaciones específicas de la infraestructura local en Mazatlán.

4. **¿De quién es la responsabilidad de que un residuo se recicle?**
   * *Análisis:* Es una **responsabilidad tripartita**:
     * **Ciudadano:** Inicia la cadena mediante la separación en origen.
     * **Municipio:** Constitucionalmente responsable (Art. 115) de proveer infraestructura de acopio y disposición final adecuada.
     * **Empresa / Fabricante:** Debe asumir la Responsabilidad Extendida del Productor (REP) mediante ecodiseño y programas de retorno.

5. **Cambios concretos a implementar:**
   * Separación doméstica en 3 categorías: Orgánicos, Reciclables y Peligrosos Domésticos (pilas/aceite).
   * Implementación de composta casera para residuos orgánicos.
   * Reducción en el consumo de plásticos de un solo uso y adopción de pilas recargables.

---

## 🤖 3. Arquitectura del Bot de Telegram (Make.com)

El flujo de automatización se construyó en **Make.com** integrando Telegram, un Modelo de Inteligencia Artificial Multimodal (Visión por Computadora), Google Drive y Google Sheets.

```
[ Telegram User ] ---> (1. WatchUpdates) 
                             |
                   (2. Filter: Only Photos)
                             |
                   (2. Download File)
                             |
             +---------------+---------------+
             |                               |
  (3. AI Local Agent)              (5. Upload to Google Drive)
   - Prompt Contextualizado                  |
   - Clasificación Mazatlán        (6. Append Row to Google Sheets)
             |                               |
  (4. Send Telegram Reply) <-----------------+
```

### Funciones del Flujo:

1. **`telegram:WatchUpdates`:** Escucha mensajes entrantes al Bot de Telegram.
2. **`telegram:DownloadFile`:** Aplica un filtro para procesar únicamente mensajes que contengan imágenes y descarga la fotografía.
3. **`ai-local-agent:RunLocalAIAgent`:** Procesa la imagen mediante un prompt del sistema especializado con criterios del TecNM / Mazatlán. La IA responde en un formato estricto de 7 líneas sin caracteres Markdown para evitar errores de renderizado.
4. **`telegram:SendReplyMessage`:** Devuelve la clasificación y las instrucciones de disposición final al usuario.
5. **`google-drive:ActionUploadFile`:** Respalda la imagen recibida en una carpeta de Google Drive etiquetada con marca de tiempo (`residuo_YYYYMMDD-HHmmss.jpg`).
6. **`google-sheets:addRow`:** Registra cada consulta en una base de datos centralizada en Google Sheets (Residuo, Clasificación, Tiempo de degradación, Formato de reciclaje, Fecha/Hora y Enlace al archivo).

---

## ⚙️ 4. Blueprint del Escenario de Make (JSON)

Para replicar o importar este escenario en Make.com, utiliza el siguiente código JSON:

```json
{
    "name": "Clasificador_Residuos_Equipo#",
    "flow": [
        {
            "id": 1,
            "module": "telegram:WatchUpdates",
            "version": 1,
            "parameters": {
                "__IMTHOOK__": 3001698
            },
            "mapper": {},
            "metadata": {
                "designer": {
                    "x": 0,
                    "y": 0
                },
                "restore": {
                    "parameters": {
                        "__IMTHOOK__": {
                            "label": "Clasificador Residuos Equipo # - Webhook"
                        }
                    }
                }
            }
        },
        {
            "id": 2,
            "module": "telegram:DownloadFile",
            "version": 1,
            "parameters": {
                "__IMTCONN__": 12040059
            },
            "filter": {
                "name": "Filtrar solo fotos",
                "conditions": [
                    [
                        {
                            "a": "{{1.message.photo}}",
                            "o": "exist"
                        }
                    ]
                ]
            },
            "mapper": {
                "fileId": "{{1.message.attachment.file_id}}"
            },
            "metadata": {
                "designer": {
                    "x": 367,
                    "y": -342
                },
                "restore": {
                    "parameters": {
                        "__IMTCONN__": {
                            "data": {
                                "scoped": "true",
                                "connection": "telegram"
                            },
                            "label": "Clasificador Residuos Equipo #"
                        }
                    }
                }
            }
        },
        {
            "id": 3,
            "module": "ai-local-agent:RunLocalAIAgent",
            "version": 0,
            "parameters": {
                "makeConnectionId": 10574833
            },
            "mapper": {
                "defaultModel": "medium",
                "tokenLimit": "60",
                "promptCaching": "none",
                "fallbackEnabled": false,
                "systemPrompt": "Eres un experto asesor en gestión y clasificación de residuos urbanos e industriales para estudiantes de Desarrollo Sustentable del TecNM campus Mazatlán, Sinaloa. Tu objetivo es analizar la imagen recibida e identificar con máxima precisión el residuo presente.\r\n\r\nPASO A PASO PARA TU ANÁLISIS INTERNO (No muestres este proceso en tu respuesta final):\r\n1. Inspecciona la imagen: Identifica forma, textura, color, visibilidad de contenedores (botellas, tambores, barriles, bolsas), etiquetas, derrames, lodos o sustancias líquidas/viscosas.\r\n2. Evalúa la claridad: ¿El objeto o derrame se distingue claramente? Si la imagen es borrosa o ilegible, no adivines.\r\n3. Evalúa el contexto ambiental y riesgo: Detecta si se trata de un residuo doméstico común o un vertido industrial/peligroso a cielo abierto (barriles oxidados, derrames de petróleo, aceite, Químicos o lodos tóxicos).\r\n4. Aplica el criterio local de Mazatlán:\r\n   - Orgánico: Restos de comida, cáscaras, residuos de jardín.\r\n   - Inorgánico reciclable: PET, vidrio, latas de aluminio, cartón/papel limpio y seco.\r\n   - Inorgánico no reciclable: Unicel, plásticos sucios, envolturas, papel sanitario.\r\n   - Manejo especial o peligroso: Pilas, electrónicos, medicamentos, aceite usado, tambores o barriles de grado industrial, residuos químicos, lodos con hidrocarburos, baterías o recipientes con sustancias tóxicas.\r\n\r\nREGLAS DE FORMATO Y SALIDA (OBLIGATORIAS):\r\n- Responde ÚNICAMENTE en texto plano.\r\n- Queda PROHIBIDO usar formato Markdown, negritas, cursivas, asteriscos (*), numerales (#) o guiones bajos (_).\r\n- Responde siempre en español.\r\n- Si el objeto o residuo es claro, responde STRICTAMENTE con este formato de 7 líneas:\r\n\r\nResiduo: [Indica qué es el residuo de forma concreta]\r\nMaterial: [Material principal]\r\nClasificación: [Escribe exactamente una: orgánico / inorgánico reciclable / inorgánico no reciclable / manejo especial o peligroso]\r\n¿Se recicla?: [sí / no / depende - exactamente una línea explicando por qué]\r\nDónde va: [Contenedor o punto de acopio específico en Mazatlán / Autoridad ambiental si es vertido peligroso]\r\nTiempo aproximado de degradación: [Tiempo estimado]\r\nConsejo: [1 línea práctica para reducir, reportar o manejar adecuadamente este residuo]\r\n\r\nREGLAS PARA CASOS ESPECIALES Y ERRORES:\r\n- Si la imagen es borrosa, la iluminación es insuficiente, hay múltiples residuos confundidos o no estás seguro al 100% del objeto, responde ÚNICAMENTE:\r\nNo pude identificar el residuo, envía otra foto más clara.\r\n\r\n- Si es un residuo peligroso, químico, aceite, o barriles/tambores industriales con derrames (como en vertidos clandestinos), en la línea \"Dónde va\" debes advertir explícitamente no tocarlo ni tirarlo a la basura común, y recomendar reportarlo a Protección Civil, PROFEPA o la Dirección de Ecología Municipal de Mazatlán.",
                "message": "Clasifica el residuo de la imagen.",
                "files": [
                    {
                        "fileName": "{{2.fileName}}",
                        "data": "{{2.fileOutput}}"
                    }
                ],
                "threadId": "",
                "modelConfig": {
                    "recursionLimit": "20",
                    "iterationsFromHistoryCount": "1",
                    "timeout": "",
                    "aiCompactionEnabled": true
                },
                "outputType": "text"
            },
            "metadata": {
                "designer": {
                    "x": 607,
                    "y": -40
                },
                "setupValidation": {
                    "version": 1,
                    "configuration": "5dab248cd317aa12",
                    "result": {
                        "valid": true,
                        "fields": []
                    }
                },
                "restore": {
                    "parameters": {
                        "makeConnectionId": {
                            "label": "Make's AI Provider (default)",
                            "data": {
                                "scoped": "true",
                                "connection": "ai-provider"
                            }
                        }
                    },
                    "expect": {
                        "defaultModel": {
                            "mode": "chose",
                            "label": "MediumModel: gpt-5-nano. Reasoning: low."
                        },
                        "promptCaching": {
                            "label": "Automatic (always on)"
                        },
                        "files": {
                            "mode": "chose",
                            "items": [
                                null
                            ]
                        },
                        "outputType": {
                            "label": "Text"
                        }
                    }
                }
            },
            "tools": []
        },
        {
            "id": 4,
            "module": "telegram:SendReplyMessage",
            "version": 1,
            "parameters": {
                "__IMTCONN__": 12040059
            },
            "mapper": {
                "text": "{{3.response}}",
                "chatId": "{{1.message.chat.id}}",
                "parseMode": "",
                "replyMarkup": "",
                "messageThreadId": "",
                "replyMarkupAssembleType": "reply_markup_enter"
            },
            "metadata": {
                "designer": {
                    "x": 864,
                    "y": 306
                },
                "restore": {
                    "parameters": {
                        "__IMTCONN__": {
                            "data": {
                                "scoped": "true",
                                "connection": "telegram"
                            },
                            "label": "Clasificador Residuos Equipo #"
                        }
                    }
                }
            }
        },
        {
            "id": 5,
            "module": "google-drive:ActionUploadFile",
            "version": 3,
            "parameters": {
                "account": 10796460
            },
            "mapper": {
                "data": "{{2.fileOutput}}",
                "convert": false,
                "fileName": "residuo_{{formatDate(now; \"YYYYMMDD-HHmmss\")}}.jpg",
                "folderId": "/",
                "destination": "personal"
            },
            "metadata": {
                "designer": {
                    "x": 927,
                    "y": -166
                },
                "restore": {
                    "parameters": {
                        "account": {
                            "data": {
                                "scoped": "true",
                                "connection": "google"
                            },
                            "label": "Julio's Google connection"
                        }
                    }
                }
            }
        },
        {
            "id": 6,
            "module": "google-sheets:addRow",
            "version": 2,
            "parameters": {
                "__IMTCONN__": 10796460
            },
            "mapper": {
                "from": "drive",
                "mode": "fromAll",
                "values": {
                    "0": "=ROW()-1",
                    "1": "{{replace(get(split(3.response; newline); 1); \"Residuo: \"; \"\")}}",
                    "2": "{{replace(get(split(3.response; newline); 3); \"Clasificación: \"; \"\")}}",
                    "3": "",
                    "4": "{{replace(get(split(3.response; newline); 6); \"Tiempo aproximado de degradación: \"; \"\")}}",
                    "5": "",
                    "6": "",
                    "7": "{{replace(get(split(3.response; newline); 4); \"¿Se recicla?: \"; \"\")}}",
                    "8": "{{formatDate(now; \"DD/MM/YYYY HH:mm\")}}",
                    "9": "{{5.alternateLink}}"
                },
                "sheetId": "Hoja 1",
                "spreadsheetId": "11Nk0fD1PWUW2byIX7z5Pb-XOhJDWD3ubhfgl18CMwA8",
                "includesHeaders": true,
                "insertDataOption": "INSERT_ROWS",
                "useColumnHeaders": false,
                "valueInputOption": "USER_ENTERED",
                "insertUnformatted": false
            },
            "metadata": {
                "designer": {
                    "x": 1283,
                    "y": 109
                },
                "restore": {
                    "parameters": {
                        "__IMTCONN__": {
                            "data": {
                                "scoped": "true",
                                "connection": "google"
                            },
                            "label": "Julio's Google connection"
                        }
                    }
                }
            }
        }
    ],
    "metadata": {
        "instant": true,
        "version": 1,
        "scenario": {
            "roundtrips": 1,
            "maxErrors": 3,
            "autoCommit": true,
            "autoCommitTriggerLast": true,
            "sequential": false,
            "slots": null,
            "confidential": false,
            "dataloss": false,
            "dlq": false,
            "freshVariables": false
        },
        "designer": {
            "orphans": []
        },
        "zone": "us2.make.com",
        "notes": []
    }
}
```

---

## 📚 5. Fuentes Consultadas

1. **Secretaría de Ecología y Gestión Ambiental (2025).** *Guía para la Clasificación y Manejo de Residuos Sólidos Urbanos (LGPGIR).*
2. **AMDA.** *Catálogo de Residuos Peligrosos (Características CRETIB).*
3. **Mongabay Latam (2025).** *Así se aniquila al Estero de Urías, uno de los más contaminados de México y el mundo.*
4. **PROFEPA (2026).** *Profepa ordena cierre definitivo del basurón municipal de Mazatlán.*
5. **Ríodoce / Quadratín Sinaloa (2026).** *Clausura del basurón municipal y amparo promovido por el Ayuntamiento de Mazatlán.*
6. **AGRIS / FAO.** *Microplastic contamination and fluxes in a touristic area at the SE Gulf of California (Mazatlán).*