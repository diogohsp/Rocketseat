# Empresa sem DevOps.

	Desenvolvimento - Frontend, Backend, e Mobile
	Operações - Infra

	Centralização de conhecimento
	Falta de feedback
	Falta de Aprendizado contínuo
	Falta de Automatização

	DevOps (nasceu em 2008/2009) buscando:

	Descentralização de conhecimento
	Feedback continuo
	Automatização (idependente da automzação é um pratica devops)
	Escala (e se eu precisar realizar um processo para mais cenarios)

# Empresa com DevOps

	Integração entre times
	Documentação contínua
	Aprendizado e feedback
	Automatização
	Errar rapido para corrigir rapido
	
# SRE - Site Reliability Engineer

	a pessoa SRE é quem irá fazer a parte técnica da cultura DevOps (EXP: automatização do deploy)
	
	Sindrome da pessoa heroi - problema: pessoa no contexto individual que conheçe bem os fluxos desenvolvimento, ao inves de lidar em como resolver o problema sempre depende dessa pessoa


# CALMS

	CALMS - Framework que visa medir a capacidade de transformação da empresa (medir se realmente esta utilizando o devops)

	C ulture - Caso tiver um problema e buscar uma pessoa culpada ao inves de rever o processo(equipe) nao é devops (exp: deploy de alguem deu errado é problema de processo do time ), aprender com os erros.

	A utomation - Atumatizar tudo que de para deixar automatico - (Entrega continua: deve ser automatizada para reduzir o tempo gasto em tarefas repetitivas e garantir agilidade na implantação) e (GitOps/IAC: visa estabeleceruma unica fonte de verdade para recursos em nuvem, centralizando o gerenciamento no GIt e garantindo maior segurança, economia e manutenabilidade)

	L ean - Focar no MVP, focar em tarefas que trazem valor, visa entregas rápidas e iteráveis, focando em alto valor e baixa complexidade. (realizar o minimo da ideia macro, oque for por fora do core vc vai iterando conforme a necessidade), realizar o mvp para experimentar o basico da ideia (errar rapido para corrigir rapido)

	M easurement - A aplicação precisa ser mensurada para entender as metricas negociais e tecnicas (exp: qnts pessoas acessaram meu 'site/aba...etc' no ultimo mes)

	S haring - Compartilhamento de conhecimento (mecanismo de documentação, calls de aprendizado, etc...)

-----------------------------

# "Três Maneiras" como um guia para implementar a cultura DevOps e melhorar o fluxo de trabalho:
	

	- Primeira maneira (acelerar o fluxo de desenvolvimento - proximidade entre dev e o ops) ACELRAR FLUXO:
	 
	-Fluxo de trabalho rapido (Entregar o maior valor e o menor tempo possivel)
	-Foco em visibilidade (Transparencia no que foi feito e no que sera feito, como foi feito... como funciona, como roda em produção... visando em nao construir pessoas herois)
	-Otimizações constantes (Mensurar os fluxos mais importantes da aplicação, para saber quando otimizar algum cenario)
	-Intervalos concisos (Realizar deploy constantes para ter feedbacks constantes)
	-Automatização (Tudo que der para ser automatizado tem que ser automatizado)

	(DEV -> OPS)

	- Segunda maneira (Estabelecer um feedback em qualquer nivel do fluxo) AMPLIAR FEEDBACK:

	-Feedback rapido e constate
	-Detecção de erros
	-Recuperação mais rapida

	(DEV -> OPS -> DEV -> OPS...)

	- Terceira maneira () EXPERMIENTAR E APRENDER: 

	-Foco em produtividade
	-Aprendizado organizacional (incetivar o aprendizado continuo na equipe)
	-Features locais e globais (problemas locais que podem ser features globais)

	(DEV <-> OPS <-> DEV <-> OPS...) 