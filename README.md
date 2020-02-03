# PacMan Assembly x8086

# Jogo PacMan

## Cópia do jogo PacMan feito em linguagem Assembly x8086

### Descrição do Projeto
   * Trata-se de uma cópia do jogo PacMan feito na linguagem Assembly x8086. Alguns dos pré-requisitos do projeto eram ter seleção de mapas, contador de "score", vidas para o personagem, mecânica de “Power-Up”, algo que lhe concedia mais poder temporariamente, pílulas energéticas do personagem permitiam que, por um tempo limitado, ele pudesse devorar os fantasmas;
* Tela Inicial do jogo.
![telainicial](https://user-images.githubusercontent.com/32877842/73675820-eab2a580-4691-11ea-949b-c60a73cd22e8.PNG)


 ### Pré-requisitos

#### Sistema Operacional
* Foi utilizado o Windows 10, mas pode ser realizado em outro sistema operacional, necessita instalar o compilador compatível com o sistema operacional.

 #### Simulador
* Foi utilizado o software DOSBOX para simulação e execução de todo o projeto.
* <a> [DOSBOX: Necessário para desenvolvimento do projeto](https://www.dosbox.com/download.php?main=1)


### Guia de instalação
* Para executar o programa na linguagem Assembly x8086, no qual o algoritmo foi realizado, necessita apenas do software DOSBOX, podendo ser instalado no computador ou apenas realizando o download do executável e desenvolvendo o projeto com ele, como já descrito, não precisando de nenhuma outra ferramenta adicional ou especial, esse programa pode ser obtido no link acima.

### Desenvolvimento
* Git clone https://github.com/giulysanfins/Pacman-Assembly.git
* Se realizar "Download ZIP", necessita de um descompactador de arquivos.
* Após ter instalado o DOSBOX, os seguintes passos devem ser feitos:  
 1-)Fazer o "mount" no dosbox (colocar o diretório que o programa está).Ex: mount j c:\users\giuliano\desktop\pacman.  
  ![mount](https://user-images.githubusercontent.com/32877842/73677495-200cc280-4695-11ea-96cf-661ec93600f9.PNG)   
 2-)Usar compiladores tasm e tlink para gerar os executáveis. Ex: tasm pacman.asm e em seguido tlink pacman.obj.
  ![tasm](https://user-images.githubusercontent.com/32877842/73675541-5c3e2400-4691-11ea-9b04-b46cf1d740a5.PNG)
  ![tlink](https://user-images.githubusercontent.com/32877842/73675542-5c3e2400-4691-11ea-8320-9e69ffbcc4bb.PNG)
* Logo em seguida, digite "pacman.exe" para executar o programa.  
  ![exe](https://user-images.githubusercontent.com/32877842/73675532-55afac80-4691-11ea-8d03-8385c5b4453b.PNG)

### Dentro do jogo
* Menu principal do jogo.  
![menu_certo](https://user-images.githubusercontent.com/32877842/73675787-da022f80-4691-11ea-954a-f0d5ad333964.png)
* Após selecionar os "Levels" existirão 3 mapas disponíveis.  
![mapas_certo](https://user-images.githubusercontent.com/32877842/73675898-15046300-4692-11ea-81ad-a754660f6536.png)
* Mapa 1.  
![Imagem1](https://user-images.githubusercontent.com/32877842/73675366-07021280-4691-11ea-91a3-c71ec6565dc1.png)
* Mapa 2.  
![mapa2_certa](https://user-images.githubusercontent.com/32877842/73675559-695b1300-4691-11ea-85f9-0d684b468513.png)
* Mapa 3.  
![mapa_3](https://user-images.githubusercontent.com/32877842/73678425-1dab6800-4697-11ea-9620-c37db6acb51e.PNG)
* Após comer pastilha power-up.  
![comendo_certo](https://user-images.githubusercontent.com/32877842/73675611-85f74b00-4691-11ea-9297-3c0899dc7f75.png)


### Desenvolvedores
* Giuliano Marques Sanfins
* Jefferson Menezes Santos

### Contribuições
- Contribuições e possíveis melhorias, no nosso ponto de vista são sempre bem-vindas.
