# Calculadora
O software Calculadora foi a primeira interface de interação com o usuário que desenvolvi. Apesar de ser um software bem simples, é bastante funcional e demonstra o quanto um programa com poucas linhas pode ser tão útil.   
No código do programa foi usado apenas a biblioteca tkinter.
A respeito dessa biblioteca, considero relevante destacar alguns comandos que foram usados nesse programa e que serão usados nos próximos programas (e certamente na versão final do software desenvolvido nesse projeto).   Esses comandos são:

* **janela=tk.Tk():**
  * Cria uma janela de nome "janela".

* **janela.geometry("LxH+E+T"):**
  * Define as dimensões da janela, que terá largura L e altura H.
  * Ao o programa ser executado, a janela aparecerá na tela a uma distância E em relação à borda esquerda do monitor e a uma distância T em relação à borda superior do monitor.

* **lb=tk.Label(janela, text="Texto",bg="cor de fundo da label",fg="cor dos caracteres impressos na label"):**
  * Adiciona à janela uma Label de nome "lb".

* **v=(tk.Entry(janela,width=largura)):**
  * Adiciona à janela uma caixa de texto de nome "v", aonde o usuário poderá digitar.

* **bt1=tk.Button(janela,width=largura,text="Texto",command=func):**
  * Adiciona à janela um botão que ao ser clicado, executa a função "func", que já deve estar definida.

* **janela.mainloop():**
  * Executa a janela em um loop infinito. 
