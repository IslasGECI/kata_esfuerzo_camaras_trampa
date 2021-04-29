# 🥋-📸🐱 Kata para calcular el esfuerzo de cámaras trampa
Kata para calcular el esfuerzo de cámaras trampa a partir de bases de datos con diferentes formatos.

## 🥋 Kata 1
### 📆 Semana 0
Empezamos el experimento con las 6 cámaras del cerco activas

| ID_camara_trampa_anterior  | ID_camara_trampa | Zona | Coordenada_Este | Coordenada_Norte | Ubicacion | Revisión | Estado |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ED | CA-01-001-ED | 1 | 373960 | 3196309 | cerco | si | A |
| EF | CA-01-002-EF | 1 | 373993 | 3196320 | cerco | si | A |
| OD | CA-01-003-OD | 1 | 373893 | 3196557 | cerco | si | A |
| OF | CA-01-004-OF | 1 | 373942 | 3196581 | cerco | si | A |
| PF | CA-01-005-PF | 1 | 373993 | 3196320 | cerco | si | A |
| PD | CA-01-006-PD | 1 | 373960 | 3196309 | cerco | si | A |

### 📆 Quincena 1
Vamos un día a campo a revisar las cámaras del cerco, el día es nublado
y no alcanzamos a revisar la camara 2, el estado de las otras 5 son: A,D,A,D,A.
1. ¿Cuáles pudieron haber sido las causas para encontrar las 2 cámaras desactivadas (3 y 5)?
    
    R1. Se le acabó la pila a la cámara
    R2. se llenó la memoria
    R3. Dejó de funcionar

2. ¿Cómo vamos a señalar que desactivamos la trampa 01?

    R1. Vamos a cambiar el interruptor a apagado

| ID_camara_trampa_anterior | ID_camara_trampa | Zona | Coordenada_Este | Coordenada_Norte | Ubicacion |Revisión |Estado |
|-----|-----|-----|-----|-----|-----|-----|-----|
|ED | CA-01-001-ED | 1 | 373960 | 3196309 | cerco | si | A |
|EF | CA-01-002-EF | 1 | 373993 | 3196320 | cerco | no | NA |
|OD | CA-01-003-OD | 1 | 373893 | 3196557 | cerco | si | D |
|OF | CA-01-004-OF | 1 | 373942 | 3196581 | cerco | si | A |
|PF | CA-01-005-PF | 1 | 373993 | 3196320 | cerco | si | D |
|PD | CA-01-006-PD | 1 | 373960 | 3196309 | cerco | si | A |

### 📆 Quincena 2
La siguiente 15na hay mejor tiempo y podemos revisar las 6 cámaras.
- La cámara 1 la desactivamos la 15na pasada, por eso está desactivada.
- Ahora si alcanzamos a revisar la cámara 2 y la encontramos desactivada.
- Las cámaras 3 y 5 las activamos la 15na pasada y las encontramos funcionando.
- Las cámaras 4 y 6 siguen funcionando.

| ID_camara_trampa_anterior | ID_camara_trampa | Zona | Coordenada_Este | Coordenada_Norte | Ubicacion |Revisión |Estado |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ED | CA-01-001-ED | 1 | 373960 | 3196309 | cerco | si | D |
| EF | CA-01-002-EF | 1 | 373993 | 3196320 | cerco | si | D |
| OD | CA-01-003-OD | 1 | 373893 | 3196557 | cerco | si | A |
| OF | CA-01-004-OF | 1 | 373942 | 3196581 | cerco | si | A |
| PF | CA-01-005-PF | 1 | 373993 | 3196320 | cerco | si | A |
| PD | CA-01-006-PD | 1 | 373960 | 3196309 | cerco | si | A |

Calcula el esfuerzo a partir de la información anterior.

## 🥋 Kata 2

### 📆 Semana 0
Empezamos el experimento con las 6 cámaras del cerco activas

| ID_camara_trampa_anterior | ID_camara_trampa | Zona | Coordenada_Este | Coordenada_Norte | Ubicacion |Revisión |Estado |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ED | CA-01-001-ED | 1 | 373960 | 3196309 | cerco | si | A |
| EF | CA-01-002-EF | 1 | 373993 | 3196320 | cerco | si | A |
| OD | CA-01-003-OD | 1 | 373893 | 3196557 | cerco | si | A |
| OF | CA-01-004-OF | 1 | 373942 | 3196581 | cerco | si | A |
| PF | CA-01-005-PF | 1 | 373993 | 3196320 | cerco | si | A |
| PD | CA-01-006-PD | 1 | 373960 | 3196309 | cerco | si | A |

### 📆 Quincena 1
Vamos un día a campo a revisar las cámaras del cerco, el día es nublado
y no alcanzamos a revisar la camara 2, el estado de las otras 5 son: A,D,A,D,A.

1. ¿Cuáles pudieron haber sido las causas para encontrar las 2 cámaras desactivadas (3 y 5)?

    R1. Se le acabó la pila a la cámara
    R2. Se llenó la memoria
    R3. Dejó de funcionar

2. ¿Cómo vamos a señalar que desactivamos la trampa 01?

    R1. Vamos a cambiar el interruptor a apagado

| ID_camara_trampa_anterior | ID_camara_trampa | Zona | Coordenada_Este | Coordenada_Norte | Ubicacion |Revisión |Estado |
|-----|-----|-----|-----|-----|-----|-----|-----|
| ED | CA-01-001-ED | 1 | 373960 | 3196309 | cerco | si | D |
| OD | CA-01-003-OD | 1 | 373893 | 3196557 | cerco | si | D |
| OD | CA-01-003-OD | 1 | 373893 | 3196557 | cerco | si | A |
| PF | CA-01-005-PF | 1 | 373993 | 3196320 | cerco | si | D |
| PF | CA-01-005-PF | 1 | 373993 | 3196320 | cerco | si | A |

### 📆 Quincena 2
La siguiente 15na hay mejor tiempo y podemos revisar las 6 cámaras.

- La cámara 1 la desactivamos la 15na pasada, por eso está desactivada.
- Ahora si alcanzamos a revisar la cámara 2 y la encontramos desactivada.
- Las cámaras 3 y 5 las activamos la 15na pasada y las encontramos funcionando.
- Las cámaras 4 y 6 siguen funcionando.

| ID_camara_trampa_anterior | ID_camara_trampa | Zona | Coordenada_Este | Coordenada_Norte | Ubicacion |Revisión |Estado |
|-----|-----|-----|-----|-----|-----|-----|-----|
| EF | CA-01-002-EF | 1 | 373993 | 3196320 | cerco | si | D |

Calcula el esfuerzo a partir de la información anterior.
