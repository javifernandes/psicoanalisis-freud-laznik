# Sueño y aparato psíquico

## Problema

*Freud usa el sueño para construir una primera teoría del psiquismo.*

En teóricos, el interés no es solo interpretar sueños. **El sueño le permite a Freud demostrar que hay procesos psíquicos inconcientes y construir un modelo del aparato.** Si durante el dormir la conciencia está disminuida, pero aun así se producen sueños con sentido, entonces **lo psíquico no puede reducirse a la conciencia**.

## Sueño

*El sueño es:*

- acto psíquico de pleno derecho;
- formación del inconciente;
- cumplimiento de deseo;
- guardián del dormir;
- vía regia al inconciente;
- relato interpretable.

*El objeto del psicoanálisis no es el sueño "puro", sino su relato.* El relato ya está ordenado y filtrado, pero es el material disponible para asociar. *Interpretar un sueño no significa traducirlo con un diccionario simbólico, sino producir asociaciones elemento por elemento.*

## Aparato psiquico

*Freud parte del arco reflejo:*

Estímulo -> polo perceptivo -> polo motor -> descarga.

Pero agrega **sistemas de huellas** entre percepción y motilidad.

Diagrama del arco reflejo:

```mermaid
flowchart LR
  A["Estimulo externo / interno"] --> B["Polo perceptivo"]
  B --> C["Polo motor"]
  C --> D["Descarga"]
```

Diagrama del aparato:

![Esquema del peine freudiano con polos, huellas y sistemas](peine.jpg)

*Esquema clásico del "peine": polo perceptivo, series de huellas mnémicas, sistemas psíquicos y polo motor.*

**El arco reflejo simple no alcanza** porque no explica memoria, deseo ni sueño. Freud necesita un aparato que pueda conservar huellas, asociarlas y permitir recorridos no lineales de la excitación.

### Checkpoint: del arco reflejo al aparato

```mermaid
flowchart LR
  A["Arco reflejo simple"] --> B["No alcanza para explicar memoria y sueño"]
  B --> C["Freud agrega huellas mnemicas"]
  C --> D["Construccion del aparato psiquico"]
```

## Percepcion y memoria

- **Percepción recibe estímulos.**
- **Memoria conserva huellas.**
- **No pueden ser el mismo sistema.**
- **La huella mnémica es una alteración permanente de un sistema.**

Si el mismo sistema percibiera y conservara huellas, quedaría saturado. Por eso Freud separa funciones: **el sistema perceptivo recibe, pero no conserva; los sistemas de memoria conservan, pero no perciben directamente**.

### Checkpoint: percepcion y memoria

```mermaid
flowchart LR
  A["Percepcion"] --> B["Recibe estimulos"]
  C["Memoria"] --> D["Conserva huellas"]
  B -. "no coincide con" .-> D
```

## Regresion

En la vigilia, la excitación va hacia la motilidad. En el dormir, **la motilidad se cierra**. La excitación retorna hacia huellas cercanas a la percepción. **Eso explica el carácter alucinatorio del sueño.**

El sueño parece percepción porque la excitación vuelve hacia el polo perceptivo. **No se descarga en acción, sino en imagen.** Esta es la vía regrediente. Por eso el sueño tiene carácter alucinatorio: **se vive como presente y real**.

Regresion en el sueño:

![Esquema del peine durante el dormir, con cierre de la motilidad y regresion al polo perceptivo](peine1.gif)

*Durante el dormir se cierra la motilidad y la excitación regresa hacia el polo perceptivo: por eso el sueño tiene carácter alucinatorio.*

## Carta 52

*\concept{Carta 52} permite pensar el aparato como serie de transcripciones:*

| Sistema | Rasgo |
|---|---|
| Sistema P | Percepción, ligado a conciencia, no deja huella |
| Signos de percepción | Primera transcripción, asociación por simultaneidad |
| Icc | Segunda transcripción, inasequible a conciencia |
| Prcc | Tercera transcripción, ligada a palabras |

## Trabajo del sueño

*Operaciones:*

1. \concept{Condensación}.
2. \concept{Desplazamiento}.
3. \concept{Figurabilidad}.
4. \concept{Elaboración secundaria}.

*Interpretar es desandar el trabajo del sueño.*

Esquema:

```mermaid
flowchart TD
  A["Pensamientos oniricos latentes<br/>+ restos diurnos<br/>+ deseo inconciente"] --> B["Trabajo del sueño"]
  B --> C["Condensacion"]
  B --> D["Desplazamiento"]
  B --> E["Figurabilidad"]
  B --> F["Elaboracion secundaria"]
  C --> G["Contenido manifiesto"]
  D --> G
  E --> G
  F --> G
  G --> H["Relato del soñante"]
```

## Formula de parcial

*El sueño es alucinatorio* porque, cerrado el polo motor durante el dormir, la excitación impulsada por el \concept{deseo inconciente} regresa hacia huellas perceptivas. *El aparato no actúa: figura.*

## Diagrama integrador

```mermaid
flowchart TD
  A["Sueño"] --> B["Acto psiquico de pleno derecho"]
  B --> C["Prueba de procesos inconcientes"]
  C --> D["Construccion del aparato psiquico"]
  D --> E["Percepcion separada de memoria"]
  E --> F["Via progrediente / via regrediente"]
  F --> G["Dormir: se cierra la motilidad"]
  G --> H["Regresion hacia huellas perceptivas"]
  H --> I["Caracter alucinatorio del sueño"]
  I --> J["Trabajo del sueño sobre el material latente"]
```
