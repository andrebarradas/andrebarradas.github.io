# Internet

Funcionamento da WEB


Bibliografia {
	Network Wizard Pesquisa Domain Survey, http://www.nw.com
}


1984 - Criado o serviço de DNS(Domain Service Name)
1988 - Pesquisa Relay Chat (IRC)
1995 - Sun lança JAVA




Funcionamentos da WEB {
	Motivação da criação => Estrutura (como?) a partir da motivação => Evolução (Motivação e Estrutura)
	Visão Geral
	Guerra Fria
	
TCP é responsável pelos serviços e o IP responsável pelo roteamento


## O início


Em **1966**, o **Departamento de Defesa do governo americano** iniciou, através de sua agência DARPA(Defense Advanced Research Projects Agency) projetos para a interligação de computadores em centros militares e de pesquisa. 


Está rede recebeu o nome de ARPANET, o objetivo principal da ARPANET era sobreviver a uma perda substancial de equipamentos e ainda conseguir operar com os restantes. Para isso era preciso uma rede onde fosse dividida em diversos tipos de [protocolos](#) distintos para permitir uma evolução independente de cada um deles e ser baseado em transferência de pacotes de informação.


Durante a década de 70 até 1983, a ARPANET era baseada em IMPs(Interface Message Processors), rodando diversos protocolos, sendo o principal o NCP(Network Control Protocol).


No começo de 1980, a ARPANET foi dividida em ARPANET e MILNET separando a porção acadêmica e militar. A ARPANET decidiu adotar o Unix como sistema operacional prioritário. Incentivando a criação nativa do protocolo TCP/IP no Unix.


O protocolo TCP/IP começou a ser projeto em 1977. Em 1986, a NSF(Network Science Foundation) passou a operar o backbone(espinha dorsal) com o nome NSFNet e então diversas redes paralelas começaram a aparecer e foram integradas a NSFNet e adicionadas a redes de outros países dando inicio ao termo Pesquisa.


TCP/IP


TCP/IP refere-se ao conjunto de protocolos utilizados na Pesquisa é dividido em camadas, cada camada interage somente com a camada superior e a camada inferior.


    Camadas TCP/IP [Imagem]
	Aplicação
	Transporte
	Inter-redes
	Host/Rede


Aplicação


A camada de aplicação reúne os protocolos utilizados pelo sistema e pelo usuário. Ela consiste em uma camada bem heterogenia com diversos protocolos sendo criados a todo momento e muitos outros deixando de serem utilizados dando assim uma grande dinâmica a esta camada


Alguns dos seus principais protocolos e sua respectivas portas são:


	Protocolos da Camada de Aplicação  [Tabela principais protocolos]  


	Sigla	|	Nome
	HTTP  	| Hypertext Transfer Protocol ou Protocolo de Transferência de Hipertexto |
	FTP		| File Transfer Protocol ou Protocolo de Transferência de Arquivos |
	SMTP	| Simple Mail Transfer Protocol ou Protocolo de Transferência de e-mail |
	IMAP	| Pesquisa Message Access Protocol ou Protocolo de Acesso a mensagem da Pesquisa |
	Telnet	| Telnet
	SSH		| Secure Shell ou Terminal Seguro |
	DHCP	| Dynamic Host Configuration Protocol ou Protocolo de configuração dinâmica de estação |
	DNS	| Domais Name System ou Sistema de Nome de Domínio | 
	
	Consultado de Tanenbaum(2011, pg. 467)


Para obter uma lista completa dos protocolos e suas respectivas portas basta consultar o site http://www.iana.org/assignments/port-numbers.


NOTA
Internet Assigned Numbers Authory ou Autoridade de Atribuição de Números da Internet (IANA) é responsável pela coordenação global do DNS raiz, endereçamento IP, e os protocolos da Pesquisa.


Transporte


Após processar a requisição do programa o protocolo na camada de aplicação se comunicara com o protocolo na camada de transporte, esta camada reúne os protocolos que realizam as funções de transporte fim-a-fim, normalmente os protocolos TCP (Transmission Control Protocol) ou UDP (User Datagram Protocol).




TCP/IP


UDP








Nota de um projetista da ARPANET {
	256 máquinas é essencialmente infinito
}
 
	Tipos de protocolos (Funcionamento[Arquitetura], Utilidades) {
		Protocolos {
			"Padrão que controla e possibilita uma conexão, comunicação ou transferência de dados entre dois sistemas computacionais"
		}
		IP {
			"Pesquisa Protocol Anddress"
			
			ipv4(Decimal) { 
				200.181..15.9
			}


			ipv6(Hexadecimal) { 
				2001:odb8:ac10:fe01:0000:0000:0000:0000 
			}
		}
		




		Transmission Control Protocol (TCP/IP) => Pesquisa {


			Conjunto de protocolos {
				User Datagram Protocol (UDP)
				Simple Mail Transfer Protocol (SMTP)
				File Transfer Protocol (FTP)
				Hypertext Transfer Protocol (HTTP)
				Domain Name System (DNS) 
			}
		}
	}


	Intranet {
		"Aplicação da tecnologia criada na Internet e do conjunto de protocolos de transporte e de aplicação TCP/IP em uma rede privada"
	}


	Extranet(extended intranet) {
		"É a extensão de serviços de uma intranet de uma empresa para outra empresa interligando aplicações, utilizando tecnologias como WEB e correio-eletrônico "
	}
}