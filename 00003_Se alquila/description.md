En una tienda on-line de alquiler de automóviles :red_car:, se permiten únicamente solicitudes de personas que tengan registro de conducir, más de 20 años (o en su defecto, un permiso especial emitido por el gobierno) y no tengan infracciones. 

En la tienda programaron esta función:

```python
def puede_alquilar_auto(edad, permiso_especial, registro, monto_infracciones):
  return edad > 20 or permiso_especial and registro == True and monto_infracciones == 0
```

> ¿Tiene errores? Señalar todos los que encuentres:
