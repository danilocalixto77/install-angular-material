### PROJETO TESTE PARA INSTALAÇÃO DO ANGULAR MATERIAL NO ANGULAR 15 ###
-----------------------------------------------------------------------
### PASSO A PASSO PARA TESTAR O FUNCIONAMENTO DO ANGULAR MATERIAL   ###
-----------------------------------------------------------------------

   O Angular Materil após ser instalo para testarmos o seu funcionamento podemos seguir os passos abaixo:
   
   1 - Crie um component no projeto para inserir os componentes do Angular Material: 
	
	Crie uma pasta views:
	-> md views
	Crie o conponent:
	-> ng g c views/home
	Insira um componente de exemplo da pagina do : https://material.angular.io/components/
	
	Exemplo "Toolbar"

	No ícone <> View Code copie o código HTML para dentro do arquivo:

	home.component.html

	Caso haja código CSS copie o código css para dentro do 

	home.component.css


   2 - Os imports do componentes dentro de API devem ser copados para dentro do:

	app.module.ts

	import {MatToolbarModule} from '@angular/material/toolbar';

	imports: [
	    MatToolbarModule
	]


   3 - Após salvar todas alterações:

	ng serve --open

   ✔✔✔ Processo finalizado. ✔✔✔

-----------------------------------------------------------------------
