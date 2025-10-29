# Primeiro-teste-de-formulario-web
Realizei a minha primeira atividade pratica, consegui com sucesso realizar o desafio do bootcamp Santander de cibersegurança.

O desafio consistia em conseguir acesso de administrador a um formulario web.
Tive bastante dificuldades ate conseguir o que eu queria, mas tive ajuda de um camarada, e fiz o seguinte caminho.

1° Usei o NMAP para mapear o site, descobrir as portas que estavam abertas, e os serviços disponiveis
2° Apos descobrir os serviços eu entrei no site que eu descobri com o NMAP e vi que era um formulario web
3° E eu fiz falso login para conseguir ver como e feita a requisição
4° Então usei a ferramenta HYDRA para fazer o brute force do formulario
5° As possiveis senhas e possiveis logins a professora passou, então eu usei a wordlist da professora
6° O HYDRA me retornou o login e a senha que eu useo
FINAL - e assim obtive acesso com privilegios de administrador do servidor web
