# ConversorDBU
ConversorDBU(Decimal, Binário, Unicode(0 a 65535)) é uma aplicação de conversão de valores. Unicode &lt; 65536 devido **tkinter.TclError** causado pelo tkinter em valores decimais maiores.

Você pode converter valores digitando em qualquer campo e pressionando **Enter** ou então no botão **Converter**.
  - **Copiar** copia o campo para a área de transferência.
  - **Colar** cola da área de transferência.
    - Você também pode colar pressionado o botão direito do mouse na caixa de entrada.
  - **Apagar** apaga o campo selecionado.

Os botões maiores são para a aplicação inteira
  - **Fixo: Ativado** deixa os campos de entradas fixo, valores maiores não irão aparecer na tela.
  - **Fixo: Desativado** deixa os campos de entradas ajustado ao tamanho dos valores colocados.
    - O tamanho dos campos muda ao converter os valores.
  - **Erros: Ativado** ativa as mensagens de erros. ***Adicionado v1.1***.
  - **Erros: Desativado** desativa mensagens de erros. ***Adicionado v1.1***.
    - **caixa de mensagem** verifica se o usuário tem certeza ao desativar erros. ***Adicionado v1.1***.
  - **Apagar** apaga todos os campos.
  - **Sair** fecha a aplicação.
  
###### RELEASES 
**v1.0** Decimal, Binário, Unicode(0 a 65535);
 - Decimal, Binário, Unicode **botões** *Copiar, Colar, Apagar*;
 - Aplicação **botões** *Converter, Apagar, Sair, Fixo*.

![captura de tela 4 1](https://user-images.githubusercontent.com/32652300/50496209-99eb6a80-0a04-11e9-99f8-c367846c318a.png)

**v1.1** Octal, Hexadecimal;
  - Adicionado sistema de cores;
  - Mudança de layout;
  - Aplicação **botões** *Erros*;
    - caixa de mensagem *Desativar mensagens de erro*.
  
![captura de tela 8](https://user-images.githubusercontent.com/32652300/50541356-75190380-0b7a-11e9-95a2-afed498355a9.png)
