# HolaMundo 
import tkinter as tk

def imprimir_mensaje():
    print("¡Hola, mundo!")

# Crear la ventana
ventana = tk.Tk()
ventana.title("Hola Mundo")

# Crear un botón
boton = tk.Button(ventana, text="Mostrar mensaje", command=imprimir_mensaje)
boton.pack(pady=10)

# Ejecutar el bucle principal de la ventana
ventana.mainloop()
