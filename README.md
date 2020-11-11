# CriaScript

# cd CriaScript/
# mkdir OUT
# chmod 777 -R OUT

./CriaScript.sh 

		  ____        _         ____               _         _
		 / ___| _ __ (_)  __ _ / ___|   ___  _ __ (_) _ __  | |_
		| |    |  __|| | / _  |\___ \  / __||  __|| ||  _ \ | __|
		| |___ | |   | || (_| | ___) || (__ | |   | || |_) || |_
		 \____||_|   |_| \__,_||____/  \___||_|   |_|| .__/  \__(
		                                             |_|
            		Version 1.1    Author @BlackCyber
			         https://github.com/BlackCyber21/

----------------------------------------------------------------------
		        Modo de uso: ./CriaScript.sh nomedoscript.sh
----------------------------------------------------------------------

./CriaScript.sh Teste.sh

---------------------------------------------------------------------
      Remova aspas, alinhe e edite o banner de seu novo script: 
----------------------------------------------------------------------
Aqui falo aspas simples dentro da figura das letras, pois elas podem interferir na execução de seu script
letras como n geradas pelo figlet possuem aspa substitua por espaço...

#!/bin/bash
echo '
                 _____           _        
                |_   _|___  ___ | |_  ___ 
                  | | / _ \/ __|| __|/ _ \
                  | ||  __/\__ \| |_|  __/
                  |_| \___||___/ \__|\___(

            	Version 1.1    Author @BlackCyber
     https://github.com/BlackCyber21/
'
----------------------------------------------------------------------
		    Fazendo updatedb para o locate
----------------------------------------------------------------------
	      Se preferir pode colar um código manualmente: 
----------------------------------------------------------------------
		   Abre nano para Reajuste do script		   
-----------------------------------------------------------------------------------
#!/bin/bash
echo '
                 _____           _        
                |_   _|___  ___ | |_  ___ 
                  | | / _ \/ __|| __|/ _ \
                  | ||  __/\__ \| |_|  __/
                  |_| \___||___/ \__|\___|
              Version 1.1    Author @BlackCyber
              https://github.com/BlackCyber21/
'
-----------------------------------------------------------------------------------
   Atenção o código deve estar localizado em qualquer pasta no computador
-----------------------------------------------------------------------------------
		         Digite o nome do código: 
---------------------------------------------------------------------------------
CriaScript.sh
----------------------------------------------------------------------
			Buscando caminho para CriaScript.sh
----------------------------------------------------------------------
/home/test/Desktop/BASH/CRIA/OUT/CriaScript.sh

Aqui serão exibidos tanto nomes quanto conteúdos dos códigos de nome CriaScript.sh
Pra facilitar a compreensão visual observe #!/bin/bash como marcador do inicio de 
cada código conforme a listagem de seus respectivos nomes (Porque caso exista mais de
um ele exibira tudo sobre todos)

#!/bin/bash
echo '
...
...
...

------------------------------------------------------------------------------
	Agora cole abaixo o caminho do código para a contagem de linhas: 
------------------------------------------------------------------------------
/home/test/Desktop/BASH/CRIA/OUT/CriaScript.sh
			Exibindo número de linhas: 
102 /home/test/Desktop/BASH/CRIA/OUT/CriaScript.sh
		Digite o número de linhas que está aqui acima: 
102

----------------------------------------------------------------------
			Veja o topo do código...
----------------------------------------------------------------------
Aqui mostrará as primeiras 20 linhas do codigo encontrado
#!/bin/bash
echo '
		  ____        _         ____               _         _
		 / ___| _ __ (_)  __ _ / ___|   ___  _ __ (_) _ __  | |_
		| |    |  __|| | / _  |\___ \  / __||  __|| ||  _ \ | __|
		| |___ | |   | || (_| | ___) || (__ | |   | || |_) || |_
		 \____||_|   |_| \__,_||____/  \___||_|   |_|| .__/  \__(
		                                             |_|
            		Version 1.1    Author @BlackCyber
			https://github.com/BlackCyber21/
'
if [ "$1" == "" ]
then
echo "----------------------------------------------------------------------"
echo "		       Modo de uso: $0 nomedoscript.sh"
echo "----------------------------------------------------------------------"
else
sleep 2
echo '#!/bin/bash' > OUT/$1
echo "echo '" >> OUT/$1
-------------------------------------

-----------------------------------------------------------------------------
		 Atenção, faça a subtração das linhas
Subtraia 102 - Quantidade que deseja remover, digite apenas o Resultado: 
-----------------------------------------------------------------------------
No caso como nosso script ja insere a linha #!/bin/bash e eu quero inserir um novo banner
Então vou contar as linhas que quero remover e subtrai-las de 102
neste caso 11 linhas que compreende desde #!/bin/bash até a ultima aspa simples do comando echo.
Portanto 102-11

91

----------------------------------------------------------------------
		      Injetando código no arquivo Teste.sh
----------------------------------------------------------------------

#!/bin/bash
echo '
		 _____           _
		|_   _|___  ___ | |_  ___
		  | | / _ \/ __|| __|/ _ \
		  | ||  __/\__ \| |_|  __/
		  |_| \___||___/ \__|\___|
              Version 1.1    Author @BlackCyber
              https://github.com/BlackCyber21/
'
if [ "$1" == "" ]
then
..
..
..
fi

----------------------------------------------------------------------
		       Veja acima se o script está pronto: 
----------------------------------------------------------------------
----------------------------------------------------------------------
Se estiver tudo certinho saia, se ainda precisar editar, o nano vem aí...
---------------------------------------------------------------------
#!/bin/bash
echo '
		 _____           _
		|_   _|___  ___ | |_  ___
		  | | / _ \/ __|| __|/ _ \
		  | ||  __/\__ \| |_|  __/
		  |_| \___||___/ \__|\___|
              Version 1.2    Author @BlackCyber
              https://github.com/BlackCyber21/
'
if [ "$1" == "" ]
then
..
..
..
fi

----------------------------------------------------------------------
		 Mostrando ultima atualização feita com nano
----------------------------------------------------------------------
