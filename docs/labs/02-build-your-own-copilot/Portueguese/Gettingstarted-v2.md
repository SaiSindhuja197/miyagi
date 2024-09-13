## Introdução ao laboratório

1. Após a configuração do ambiente, o seu browser irá carregar uma máquina virtual (JumpVM), utilize esta máquina virtual durante todo o workshop para realizar o laboratório. Pode ver o número na parte inferior do guia de laboratório para alternar para diferentes exercícios no guia de laboratório.

   ![](../Media/gettingstartedpagenew1-v2.png)

1. Para obter os detalhes do ambiente de laboratório, pode selecionar o separador **Ambiente**. Além disso, as credenciais também serão enviadas para o seu endereço de e-mail registado. Também pode abrir o Guia do laboratório numa janela separada e completa, selecionando **Janela dividida** no canto inferior direito. Além disso, pode iniciar, parar e reiniciar máquinas virtuais no separador **Recursos**.

   ![](../Media/gettingstartedpagenew2-v2.png)

 > Verá o valor SUFFIX no separador **Ambiente**; utilize-o sempre que aparecer SUFFIX ou DeploymentID nas etapas do laboratório.

## Faça login no Portal Azure

1. Minimize o **Docker Desktop** clicando no botão **Minimizar**.

   ![](../Media/miyagi-image1.png)

   - Se se deparar com algum problema, uma distribuição WSL do qual o Docker Desktop depende foi encerrada inesperadamente. Isto acontece normalmente como resultado de uma entidade externa terminar o WSL, clique no botão **Reiniciar**.

     ![](../Media/docker-issue.png)

1. No JumpVM, clique no atalho do portal Azure do navegador Microsoft Edge, que é criado no ambiente de trabalho.

   ![](../Media/gettingstartpage3.png)

1. No separador **Entrar no Microsoft Azure**, verá o ecrã de login. Introduza o seguinte e-mail ou nome de utilizador e clique em **Seguinte**.

     * **E-mail/Nome de utilizador**: **<inject key="AzureAdUserEmail"></inject>**

       ![](../Media/miyagi-image2.png)

1. Agora digite a seguinte palavra-passe e clique em **Entrar**.

    * **Palavra-passe**: **<inject key="AzureAdUserPassword"></inject>**

      ![](../Media/miyagi-image3.png)

1. Se vir o pop-up **Permanecer ligado?**, selecione **Não**.

   ![](../Media/miyagi-image4.png)

1. Se for apresentada uma janela pop-up **Bem-vindo ao Microsoft Azure**, selecione **Cancelar** para ignorar o tour.

   ![](../Media/miyagi-image5.png)

1. Agora que verá o Painel do Portal Azure, clique em **Grupos de recursos** no painel Navegar para ver os grupos de recursos.

   ![](../Media/miyagi-image6.png)

1. Em **Grupos de recursos**, clique em **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** grupo de recursos.

   ![](../Media/miyagi-image7.png)

1. No grupo de recursos **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>**, verifique os recursos nele presentes.

   ![](../Media/miyagi-image8.png)


> [!IMPORTANTE]<br>
> **Para uma experiência mais tranquila durante o laboratório prático, é importante rever minuciosamente as instruções e as notas que as acompanham. Ajudará a navegar pelas tarefas com facilidade e confiança.**
