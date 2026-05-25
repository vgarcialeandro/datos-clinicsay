# Estrategia
Procesamiento Incremental (Por fases)  
Los datos a migrar corresponden a pacientes, odontologos, citas, pagos y tratamientos.
Para el procesamiento lo vamos a realizar de forma incremental, segun el siguiente orden:
1. Pacientes
2. Odontologos
3. Tratamiento
4. citas
5. Pagos.

Riesgos detectados





Plan de validaciones (pre/post migración)
Estrategia de rollback
Problemas encontrados y cómo los resolviste