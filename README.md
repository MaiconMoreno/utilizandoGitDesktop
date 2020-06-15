# Utilizando o Git
Será descrito brevemente os passos necessário para utilização do Git.  
Passaremos rápidamente pela processo de instalação, cópia de um diretório já existente, 
commit das alteração e push para o repositório no GitHub.


## Instalação

Primeiramente instale o git em sua máquina, procure a fonte oficial.
Será possível localizar o arquivo para download da ferramenta em [Git](https://git-scm.com/downloads).
Não é necessário nenhuma configuração durante a instalação, aperte _Next_ em todas as telas. 

Após instalação será possível localizar a pasta criada no sistema, localize **Git Bash**, será nele que executaremos todos os comandos a seguir.


## Clonando diretório existente do GitHub
1. Abra o **Git Bash** e vá até o local onde deseja clonar a pasta do projeto.

2. Vá até o **GitHub**, copie o link do diretório que deseja clonar.   

Para isso há um botão "Clone or Download", onde será exibido o link completo. 

   ![Legenda](https://i.stack.imgur.com/PrvYK.png)

3. Digite _git clone_ e cole a URL que copiou no passo anterior.

   ```git clone https://hostname/YOUR-USERNAME/YOUR-REPOSITORY```


4. Pressione **Enter** para iniciar o processo. 

5. Aguarde que todo o conteúdo será copiado.

Pronto, agora você pode utilizar a pasta do projeto normalmente.

> Para esta utilização o git deverá está iniciado com um diretório remoto configurado. 


**Importante!**  
Realize esta etapa somente se não houver feito anteriormente, uma vez clonado não é mais necessário repetir o processo, pois iremos utilizar o **Git Desktop**, que fará o gerenciamento dos arquivos.


## Git Desktop

1. Realize o download da aplicação em https://desktop.github.com/. 
A instalação é bem simples, basta aceitar os termos, e inserir sua conta no GitHub.

2. Ao finalizar agora é importante informar qual o local está o projeto, então clique aba da lateral esquerda em **Current Repository**, **Add** e depois em **Add New Repository...**

3. Também será necessário criar um Branch onde irá trabalhar, para isso clique na aba **Current branch** e depois no botão **New branch**, 
insira um nome e confirme em **Create branch**. Fique atento se houveram modificações e se irá levá-laspa para o branch que está criando, caso não tenha feito nada basta continuar.  

4. Pronto agora o Git Desktop irá controlar os arquivos.


## Commit 

Todas as modificações serão capturadas pelo Git Desktop, e pode ser visto na barra lateral de **Changed files**.  

#### Realizando Commit 
Quando finalizar altura etapa de desenvolvimento que já validou o funcionamento dos códigos, será possível enviá-los facilmente. 
1. Selecione na barra de **Changed files** as alterações que deseja enviar.
2. Insira um titulo no sumário para essa alteração e uma descrição. 
3. Clique em Commit para confirmar.
4. Agora basta criar um _Pull Request_ no GitHub, então clique no botão **Create Pull Request** que te ajudará levando para a página das alterações no GitHub.  
5. As informações serão enviadas para um formulário no GitHub, clique em **Create Pull Request** e assim as alterações ficarão disponiveis para verificação dos demais. 
> Esta etapa é utilizada pelas equipes para que os desenvolvedores analisem os códigos dos demais.  
> Em grandes equipes, há um desenvolvedor Senior que irá analisar tudo que foi feito e confirmará se a alteração pode entrar ou não. 
6. Se não houver ninguém para auditar, então na aba **Files Changed**, marque **Viewed** e confirme no botão **Review changes** e depois em **Submit review**.
> Assim confirmados as alterações, os arquivos serão inseridos na brach Master e o time conseguirá baixar as alterações.

## Fetch 
No Git Desktop o download das alterações acontece de forma simples, basta clicar em **Fetch Origin** que todos os arquivos do diretório 
local serão atualizados com o conteúdo da branch Master no GitHub.




