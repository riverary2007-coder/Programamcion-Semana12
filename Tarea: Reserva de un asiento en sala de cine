# Matriz de asientos (3 filas x 4 columnas)
asientos = [
    [0,0,0,0],
    [0,0,0,0],
    [0,0,0,0]
]

while True:
    print("------Sistema de Reserva de Asientos del Cine------")
    print("-------Menu Principal-----")
    print("1. Ver estado de la sala")
    print("2. Reservar un asiento")
    print("3. Salir del sistema")

    opcion = int(input("Elija una opcion del menu (1,2,3): "))

    match opcion:

        case 1:
            print("-------Estado de la sala-----")
            for fila in asientos:
                for asiento in fila:
                    print(asiento, end=" ")
                print("")
            print("--"*30)

        case 2:
            f = int(input("Ingrese fila (0 a 2): "))
            c = int(input("Ingrese columna (0 a 3): "))

            if f < 0 or f > 2 or c < 0 or c > 3:
                print("Error: fila o columna fuera de rango")
            else:
                if asientos[f][c] == 0:
                    asientos[f][c] = 1
                    print("Asiento reservado con exito")
                else:
                    print("Ese asiento ya esta reservado")

            print("--"*30)

        case 3:
            print("Gracias por usar el sistema")
            break

        case _:
            print("La opcion no es valida, por favor intente nuevamente")
            print("--"*30)
