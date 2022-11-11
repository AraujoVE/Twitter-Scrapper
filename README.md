# Twitter-Scrapper
**0** - Observações  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**0.1** - Para baixar os arquivos necessários, basta clicar em 'Code' nessa página, e depois em 'Download ZIP' e depois descomprimir a pasta no local de sua preferência. Também é possivel ir no diretório em que se deseja baixar a pasta e executar o comando `git clone https://github.com/AraujoVE/Twitter-Scrapper`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**0.2** - Essa pasta na qual está esse README.md será referenciada nesse arquivo como ".". Dessa forma, o arquivo README, por exemplo, é representado por "./README" e o arquivo TwitterScrapper.jar por "./TwitterScrapper.jar".  
**1** - Escolher quais vão ser os tweets capturados.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**1.1** - Em ./searchParams temos o arquivo ./searchParams/searchText.txt nesse arquivo deve ser colocada a query desejada. No arquivo ./searchParams/README se encontram as instruções para como preencher esse arquivo.  
**2** - Colocar o ChromeDriver na pasta. É necessário ter o chromedriver para executar o programa. Para isso, devem-se seguir alguns passos.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.1** - Baixar o Google Chrome.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.2** - Verificar a versão do Chrome, isso pode ser feito adentrando no link chrome://settings/help e lendo qual versão aparece do chrome.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.3** - Adentrar no site https://chromedriver.chromium.org/downloads e clicar no link da sua versão correspondente.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.4** - Após o link abrir, basta clicar para fazer download na versão de acordo com o seu sistema operacional. No caso do Mac, existem 2 opções, o mac64, e o arm64. O primeiro, mac64, deve ser escolhido para sistemas com o chip da Intel. Caso o chip seja M1 ou M2, a versão com o arm64 deve ser escolhida. Para saber qual o seu chip, basta executar (⌘ + space) e pesquisar por `About This Mac`. Nessa janela se encontram as informações sobre o chip utilizado no computador. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.5** - Descomprimir o arquivo ou executar outras ações para ter como resultado final o arquivo "chromedriver". No caso do Windows, esse arquivo é um .exe  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.6** - Arrastar esse arquivo para dentro da pasta ./ChromeDriver  
**3** - Baixar o Java18  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**3.1** - Baixar o java SE 18 para o seu sistema operacional https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html  . Novamente, é necessário verificar corretamente quando existirem mais de uma opção, tal como no caso do Mac em que existe o arm (para chips M1 ou M2) e o x64 (para chips da Intel). Outros exemplos são o do Linux, em que para certas distros que se utilizam de Debian - tal como Ubuntu - é possível usar o instalador Debian, enquando que para outras, como o Arch, não é.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**3.2** - Caso você possua diversas versões do java jdk, é necessário escolher a versão 18 antes de rodar o programa. A forma como isso pode ser feito varia de sistema operacional para sistema operacional, e pode se tornar algo muito complexo. Uma pesquisa com os termos "How to change jave version on " seguido do nome do sistema operacional normalmente retorna resultados úteis.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**3.3** - Descomprimir quando necessário.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**3.4** - Executar os passos para instalar de acordo com cada sistema operacional.  
**4** - Executar o programa  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**4.1** - Entrar no terminal do seu sistema operacional  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**4.2** - Navegar até onde se encontra o ./  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**4.3** - Rodar o programa com o comando: java -jar TripAdvisorScrapper.jar  
