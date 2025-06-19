# Pokédex de Hoenn

## Pokémon Iniciales

Los Pokémon iniciales de la región de Hoenn son tres criaturas únicas que cada entrenador puede elegir al comenzar su aventura.

=== "Treecko"

    ```yaml
    Nombre: Treecko
    Tipo: Planta
    Número: #252
    Altura: 0.5 m
    Peso: 5.0 kg
    Habilidad: Espesura
    ```

=== "Torchic"

    ```yaml
    Nombre: Torchic
    Tipo: Fuego
    Número: #255
    Altura: 0.4 m
    Peso: 2.5 kg
    Habilidad: Mar Llamas
    ```

=== "Mudkip"

    ```yaml
    Nombre: Mudkip
    Tipo: Agua
    Número: #258
    Altura: 0.4 m
    Peso: 7.6 kg
    Habilidad: Torrente
    ```

## Pokémon Legendarios

### Rayquaza - El Señor de los Cielos

```python
# Estadísticas de Rayquaza
rayquaza_stats = {
    "numero": 384,
    "tipo": ["Dragón", "Volador"],
    "ps": 105,
    "ataque": 150,
    "defensa": 90,
    "at_especial": 150,
    "def_especial": 90,
    "velocidad": 95,
    "total": 680
}

def mega_rayquaza():
    """Transformación Mega de Rayquaza"""
    return {
        "habilidad": "Ráfaga Delta",
        "ataque": 180,
        "def_especial": 120,
        "total": 780
    }
```

### Trío Legendario

=== "Kyogre"
    
    **Pokémon Cuenca Marina**
    
    - Tipo: Agua
    - Habilidad: Llovizna
    - Movimiento característico: Hidrocañón

=== "Groudon"
    
    **Pokémon Continente**
    
    - Tipo: Tierra
    - Habilidad: Sequía  
    - Movimiento característico: Abismo

=== "Rayquaza"
    
    **Pokémon Cielo Alto**
    
    - Tipo: Dragón/Volador
    - Habilidad: Aire Puro
    - Movimiento característico: Dragoascenso

## Pokémon Exclusivos de Esmeralda

- **Surskit** y **Masquerain**: Tipo Bicho/Agua
- **Meditite** y **Medicham**: Tipo Lucha/Psíquico  
- **Roselia**: Tipo Planta/Veneno
- **Zangoose**: Tipo Normal
- **Seviper**: Tipo Veneno

[Regresar al inicio](index.md) | [Ver consejos útiles](consejos.md)