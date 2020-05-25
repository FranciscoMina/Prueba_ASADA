# Prueba_ASADA
Cómo empezar a crear código para el proyecto de una ASADA
def Login():
    nombreusuario=input("usted esta creando un usuario, ingrese su nombre:")
    numcontra=input("usted está creando un usuario, digite su contraseña:")
    cont1=True
    while cont1:
        usuario=input("digite su nombre de usuario"   )
        if usuario != nombreusuario:
            print("Usuario incorrecto; vuelva a intentarlo")
        else:
            cont1=False
    print("usuario correcto ",nombreusuario)
    cont=True
    while cont:
        contraseña=input("digíte su contraseña:   ")
        if contraseña !=numcontra:
            print("Contraseña_incorrecta; vuelva a intentarlo")
        else:
            cont=False
    print("acceso permitido")
    return
Login()
