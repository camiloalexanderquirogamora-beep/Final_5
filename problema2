# Crear la matriz base
menu = [
    ["Hamburguesa", "Comida rapida", 18000],
    ["Pizza", "Comida rapida", 14000],
    ["Salchipapas", "Comida rapida", 15000],

    ["Ensalada", "Entrada", 12000],
    ["Sopa de tomate", "Entrada", 10000],
    ["Crema de champiñones", "Entrada", 12000],

    ["Lasaña", "Plato principal", 22000],
    ["Arroz con pollo", "Plato principal", 20000],
    ["Bistec", "Plato principal", 24000],

    ["Cheesecake", "Postres", 14000],
    ["Brownie con helado", "Postres", 15000],
    ["Flan", "Postres", 10000],

    ["Gaseosa", "Bebidas", 4000],
    ["Jugo", "Bebidas", 7000],
    ["Limonada", "Bebidas", 5000]
]

def calcular_precio_final(categoria, precio_base, categoria_objetivo, umbral):

    if categoria == categoria_objetivo and precio_base > umbral:
        descuento = precio_base * 0.15
        precio_final = precio_base - descuento

    else:
        precio_final = precio_base

    return precio_final

for producto in menu:
    nombre = producto[0]
    categoria = producto[1]
    precio = producto[2]

    precio_final = calcular_precio_final(
        categoria,
        precio,
        "Postres",
        12000
    )
    
    print(f"{nombre} | Base: {precio} | Final: {precio_final:.0f}")
