!["dio_logo"](https://digitalinnovationone.github.io/roadmaps/assets/logo-dio.svg)

# dio-lab-cibersecurity-phishing
Repositório do Desafio DIO - Criação de um Phishing com o Kali Linux

Neste projeto nós utilizamos a ferramenta setoolkit para criar um phishing para captura de senhas do Facebook.

## Ferramentas

- Kali Linux
- setoolkit

## Configuração do Phishing no Kali Linux

- Acesso root na máquina: ```sudo su```
- Iniciando o setoolkit: ```setoolkit```

![image-1](images/image-1.png)

- Tipo de ataque: ```1 - Social-Engineering Attacks```

![image-2](images/image-2.png)

- Vetor de ataque: ```2 - Web Site Attack Vectors```

![image-3](images/image-3.png)

- Método de ataque: ```3 - Credential Harvester Attack Method ```

![image-4](images/image-4.png)

- Método de ataque: ```2 - Site Cloner```

![image-5](images/image-5.png)

- Inserir o endereço da máquina que deseja usar, ou utilizar o padrão

![image-6](images/image-6.png)

- URL para clone: http://www.facebook.com

## Resultado

- O serviço iniciará uma página false de login do Facebook, e ao inserir os dados, será redirecionado para o siteoriginal.

![image-7](images/image-7.png)

- E mostrará os dados capturados no terminal

![image-8](images/image-8.png)