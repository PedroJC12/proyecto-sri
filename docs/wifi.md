# Wi-Fi seguro

## El problema de los Wi-Fi públicos

Los Wi-Fi de cafeterías, aeropuertos u hoteles los usa mucha gente. Algunos pueden estar mal protegidos o incluso ser **falsos** (un delincuente crea una red con nombre parecido para espiar).

!!! warning "Regla de oro"
    En un Wi-Fi público **no entres en el banco ni hagas compras**. Para eso, usa los datos de tu móvil.

## Cómo proteger tu Wi-Fi de casa

### Paso 1: cambia la contraseña del router

El router (la cajita que da el internet) viene con una contraseña de fábrica. Suele estar en una pegatina. **Cámbiala** por una [contraseña fuerte](contrasenas.md).

1. Escribe en el navegador la dirección del router (suele ser `192.168.1.1`; mírala en la pegatina).
2. Entra con el usuario y clave de la pegatina.
3. Busca **Wi-Fi** o **Seguridad inalámbrica**.
4. Cambia la clave y el nombre de la red.

### Paso 2: usa un cifrado moderno

En la misma pantalla, busca **Seguridad** o **Cifrado** y elige **WPA3**. Si tu router no lo tiene, elige **WPA2**. **Nunca elijas** WEP ni "Sin seguridad".

| Tipo | ¿Es seguro? |
|---|---|
| WPA3 | ✅ Sí, el mejor |
| WPA2 | ✅ Sí, aceptable |
| WEP | ❌ No, se rompe en minutos |
| Sin contraseña | ❌ No, cualquiera entra |

### Paso 3: no publiques el nombre de tu familia

No pongas tu nombre ni tu piso en el nombre de la red (por ejemplo, `Casa_Garcia_3B`). Pon uno neutro.

## Cuando estés fuera de casa

- Confirma el nombre exacto de la red con el local (pregunta al camarero).
- Prefiere los **datos del móvil** para operaciones importantes.
- Desactiva la **conexión automática** a redes públicas.
- Usa páginas que empiecen por `https://` y muestren un candado.

=== "Windows"

    1. Abre **Configuración → Red e Internet → Wi-Fi**.
    2. Entra en **Administrar redes conocidas**.
    3. Elimina las redes públicas que no uses.

=== "macOS"

    1. Abre **Ajustes del Sistema → Wi-Fi**.
    2. Pulsa **Avanzado**.
    3. Elimina las redes públicas de la lista de redes conocidas.

- [ ] He cambiado la contraseña del router
- [ ] Mi Wi-Fi usa WPA2 o WPA3
- [ ] Evito el banco en Wi-Fi públicos

??? question "¿Qué es una VPN?"
    Es una herramienta que **cifra** lo que envías, como un túnel privado. Ayuda en redes públicas, pero no sustituye a las demás medidas. Si usas una, elige una de confianza.

??? question "¿Cada cuánto cambio la clave del Wi-Fi?"
    Si es fuerte, basta con cambiarla si sospechas que alguien la conoce o si has compartido la red con mucha gente.
