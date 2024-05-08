import tkinter as tk
from tkinter import ttk

# Função para criar a mensagem com o coração
def criar_mensagem():
    # Criando a janela
    janela = tk.Tk()
    janela.title("Mensagem Especial")
    janela.configure(bg="black")

    # Criando o texto da mensagem
    mensagem = tk.Label(janela, text="Marcia ❤️ Denilson", font=("Arial", 18), fg="white", bg="black")
    mensagem.pack(pady=20)

    # Criando um coração usando caracteres unicode
    coracao = ttk.Label(janela, text="\u2764", font=("Arial", 40), fg="red", bg="black")
    coracao.pack()

    # Exibindo a janela
    janela.mainloop()

# Chamando a função para criar a mensagem
criar_mensagem()

