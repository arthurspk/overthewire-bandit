![image](https://i.imgur.com/VcJmvlH.png)

## Bandit Level 0 - SSH 
O objetivo deste nível é fazer login no jogo usando SSH. O host ao qual você precisa se conectar é bandit.labs.overthewire.org , na porta 2220. O nome de usuário é bandit0 e a senha é bandit0 . Uma vez conectado, vá para a página do Nível 1 para descobrir como vencer o Nível 1.

- Comandos utilizados: ssh

Materiais de leitura úteis para ajudar no nível 0
- [Secure Shell (SSH) na Wikipedia](https://pt.wikipedia.org/wiki/Secure_Shell)
- [Como usar o SSH no wikiHow](https://www.wikihow.com/Use-SSH)
- [Conexão SSH: 3 formas de realizar o acesso a um servidor](https://www.hostgator.com.br/blog/conexao-ssh-3-formas-de-realizar-o-acesso-a-um-servidor/)
- [Saiba o que é SSH (Secure Shell) e pra que serve esse protocolo](https://rockcontent.com/br/blog/ssh/)

# Anotações sobre o comando SSH 

O comando SSH (Secure Shell) é um protocolo de rede que permite aos usuários se conectarem e controlarem de forma segura outros computadores na internet. Ele é amplamente utilizado por administradores de sistema para gerenciar servidores remotamente, mas também pode ser usado por usuários comuns para se conectar a serviços como o Dropbox ou o Google Drive.

Para executar o comando SSH, você precisa abrir um terminal ou prompt de comando em seu computador e digitar o seguinte:

```bash
ssh usuario@endereco-do-servidor
```

Isso irá se conectar ao servidor especificado como endereco-do-servidor como o usuário usuario. Você será solicitado a digitar a senha do usuário para autenticar a conexão.

Por exemplo, se você quisesse se conectar ao servidor example.com como o usuário john, você poderia usar o seguinte comando:

```bash
ssh john@example.com
```

Essa é apenas uma introdução básica ao comando SSH. Ele tem muitos outros recursos e opções que podem ser explorados para fazer coisas como criptografar a conexão de forma mais segura ou redirecionar portas de rede. Para mais informações, consulte a documentação do SSH em seu sistema operacional ou pesquise online.

## Resolução do Nível 0

1º - É necessário estabelecer a conexão com o host pelo usuário `bandit0` para realizar essa etapa, utilizaremos o seguinte comando:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

![image](https://i.imgur.com/0VJXpni.png)

2º - Após se conectar ao host com o usuário `bandit0` ele irá irá pedir a senhar que também será `bandit0`

![image](https://i.imgur.com/wbIuayj.png)

3º - Ao inserir sua senha o host irá retornar uma mensagem de susseso e bem-vindo, logo após isso você estará liberado para seguir adiante para o nivel 1 » 2 e continuar sua jornada de aprendizado utilizando o bandit.

![image](https://i.imgur.com/2femMgG.png)