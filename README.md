# JavaAPIBasicoOlaMundo
Anotação sobre como criar e subir uma api básica java olá mundo

# Primeiro acessa o site do spring boot
           1)Acessa:  https://start.spring.io/
           2)Selecione MAVEN, Java 8 ou 11, e como dependencia Java WEB.
           3)Baixe e importe no Eclipse
           
# Dentro do Eclipse
           1)Crie um pacote controller
           2)Uma classe Java Controller:
           
           @Controller
           public class olaController {
	
           	@RequestMapping("/")
	          @ResponseBody 
           	public String Ola() {
		
		       return "e ae ";
	         }

           }
# Pode dar start na aplicação e testar a porta 8080
         
