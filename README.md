<img width="258" height="25" alt="Captura de tela 2025-10-01 192358" src="https://github.com/user-attachments/assets/d9f53fc3-1a29-484d-afb9-5cfe1a5e46a3" /># dio-cibersecurity-siteclone
Clonagem de sites no Kali Linux utilizando Setoolkit

Nos meus testes não consegui replicar a atividade igual a da aula, tive divergências na prática. Imagino que sites com Facebook e outros tenham mudado seus metódos de segurança e a clonagem não é 100% perfeita, digo isso pois não consegui capturar o campo de senha, apenas o campo do e-mail. Quando usei os templates prontos da própria ferramenta obtive o resultado esperado. Ao tentar usar no X (Antigo Twiiter)e também não consegui, a clonagem do site acontece com perfeição porém não existem campos de autenticação na própria plataforma. Dito isso, esse documento serve apenas para mostrar um teste totalmente sintético.

Requisitos:
- Um computador com acesso a internet
- Kali Linux

Ferramentas Principais:
- Kali Linux
- Setoolkit

Passo a passo:
- Acessar o terminal
- Logar no root utilizando "sudo su"
- Digitar "setoolkit" para acessar a ferramenta
- Escolher opção 1 - "Social-Engineering Attack"
- Depois escolher opção 2 - "Website Attack Vectors"
- Em seguida, opção 3 - "Credential Havester Attack Method"
- Aqui temos três opçôes, Web Template, Site Cloner e Custom Import, não cheguei a utilizar a Custom Import, apenas as outras. Como descrevi anteriormente, o Web Template me entrega algumas opções prontas para uso, enquanto o Site Cloner faz um cópia do site desejado e hospeda localmente na sua máquina. Irei uilizar o Web Template aqui para termos um resultado positivo. 
- Confirme seu IP ou insira um novo IP
- Selecione a opção Google (No outro metódo você precisaria utilizar a URL do site à ser copiado.)
- Um site no seu IP colocar irá subir, você pode acessar no navegador digitando "localhost" ou via o IP utilizado.
- As credenciais digitadas nesse site irão aparecer no terminal do setoolkit.

<img width="258" height="25" alt="Captura de tela 2025-10-01 192358" src="https://github.com/user-attachments/assets/53ac9a30-5aad-4ec8-91c6-8735f0c6f551" />

O seu site estar disponível para outras pessoas ou não, vai depender totalmente das suas configurações de rede utilizadas, na máquina virtual ou na máquina fisíca, e vai depender também do ambiente de rede que você vai estar, se ele é público, privado, etc...









- 
