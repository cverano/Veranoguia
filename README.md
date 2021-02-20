import tkinter as tk
from tkinter import ttk
from tkinter import messagebox as mb
nn
class Aplicacion:
    def __init__(self):
        self.ventana1=tk.Tk()
        self.labelframe1=ttk.LabelFrame(self.ventana1, text="Calculo Tercer Corte")
        self.labelframe1.grid(column=0, row=0, padx=10, pady=10)
        self.agregar_componentes()
        self.agregar_menu()
        self.ventana1.mainloop()
