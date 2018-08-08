# opencv_Ambiente_CMake_VC15
Montando ambiente opencv com cmake e vc15, Máquina 64 bits

Primeiro baixar o opencv 3.40 
Baixar o CMAKE
instalar o cmake

apontar o sources para o diretorio sources
o build para o diretorio build
 mandar construir
desmarcar opções relacionadas a python
depois mandar executar

depois precisará usar comando especifico do cmake para linkar

depois de tudo pronto 
fazer o setup do projeto no visual studio
la basta colocar o diretorio de include que pode ser qualquer um do cmake
depois o diretorio das libs que de preferencia será aquele onde se encontra os pbds
depois colar as dlls no local onde o arquivo executavel gerado se encontra
lembrando que se usar lib de depuração não ira compilar no modo release ou vice versa.

depois é só programar. ou rodar um exemplo


 

