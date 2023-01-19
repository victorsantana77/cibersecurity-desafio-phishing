# cibersecurity-desafio-phishing
Aqui temos um desafio lançado pelo bootcamp da plataforma DIO, para a utilização da ferramenta Setollkit, ferramenta tal que tem por intuito gerar um teste de penetração utilizando a técnica de engenharia social, assim obtendo informações de acesso a um sistema.

**ferramentas utilizadas** 

Kali Linux

setoolkit


**Instalação e Configuração**

Neste tópico não entraremos em detalhes, já que a mesma se encontra na git oficial da ferramenta, lá encontrará como baixar, instalar e configurar, link abaixo:

https://github.com/trustedsec/social-engineer-toolkit


**Desafio**

Utilizar a ferramenta para conseguir dados de acesso de um site.

Tipo de ataque:Social-Engineering Attacks
Vetor de ataque:Web Site Attack Vectors
Método de ataque:Credential Harvester Attack Method 
Método de ataque:Site Cloner
URL para clonar: http://www.facebook.com

**Vamos para a prática**

1- Será necessário primeiro estar logado como root no terminal linux, logo basta digitar o seguinte comando:
"sudo su", digite a senha do super user;

2- agora digite o seguite comando "setoolkit", escolha a opção 1 -"Engineering Attacks":
![Screenshot_2023-01-19_08_52_11](https://user-images.githubusercontent.com/101285866/213507067-bc8a1fde-44a2-4dbe-9f80-8580e5391bdd.png)

3- escolha a seguda opção 2-Web Site Attack Vectors

![Screenshot_2023-01-19_08_52_25](https://user-images.githubusercontent.com/101285866/213522968-355cf81e-55a7-4985-8e26-d494d0181802.png)


4- Agora na opções, digite 3 - Credential Harvester Attack Method:
![Screenshot_2023-01-19_08_52_36](https://user-images.githubusercontent.com/101285866/213511583-66927629-a4a7-4de3-bc02-60be34e229bb.png)

5 - Neste tela poderemos utilizar a primeira opção que seria caso ja tivessemos um template totalmente estruturado para pegar mais informações
dai vai de sua imaginação, mas trabalharemos com a opção 2 - Site Cloner.

![Screenshot_2023-01-19_08_52_46](https://user-images.githubusercontent.com/101285866/213524032-f9b45a4e-30d0-4cc2-bba2-a2c31b54e0ad.png)

6 - Na tela abaixo veja que no retangulo verde de numero 1, temos o ip de nossa máquina, onde neste momento irá se torna um servidor, para os dados capturados iram,
ja no retangulo laranja de numero , temos o site ao qual iremos clonar:

![penultima tela](https://user-images.githubusercontent.com/101285866/213525677-15aa9702-7637-4e1d-8673-554f6ffa306f.png)

7 - Agora temos os dados sendo exibido em nosso terminal, para facilitar a captur esta em um retangulo amarelo, veja abaixo:

![ultima tela](https://user-images.githubusercontent.com/101285866/213526361-952b31b1-27b1-4315-acfa-7b33d5ebb31b.png)


Espero que com isso seja mais fácil o entendi da ferramenta, que a curiosidade te mova e faça testar as demais configurações, para que assim tenha um entedimento total 
da utilização da mesma.
