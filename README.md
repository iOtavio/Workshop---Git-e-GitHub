# Workshop - Skyrats (EP01)

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/524b78a8-49ed-4354-96c8-0ef4c385d7e9)

# Linux
- O **Linux** é um kernel escrito por Linus Torvalds em 1991;
- **Kernel** é o softwarre de baixo nível do OS que interage com o hardware do computador;
- Apesar de ser um kernel, o Linux é tradado popularmente como o sistema operacional em si;
- O Linux (software, nesse contexto) permite, em relação a outros sistemas operacionais, maior personalização e acesso a funções que estavam mais ocultadas, ou que simplesmente sua manipulação não era permitida. Por isso, o Linux é muito almejado por programadores (Ubuntu é o querido da Sky).

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/f368e096-4580-4093-a8aa-fe0765390ed9)

## Distros
- **Distros** são o resultado da junção entre o núcleo Linux e uma coleção de software e gerenciadores de pacotes específicos;
- Tanto o Linux quanto os gerenciadores de pacotes são open source. Ou seja, todos possuem liberdade para alterar, e por isso há várias distros circulantes.

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/07224965-682b-4fac-8e0b-77598ccefbce)

# Sistema de arquivos e armazenamento
- O Linux utiliza o Filesystem Hierarchy Standard (FHS) do sistema Unix. Assim, diferentemente do que ocorre com o Window, não há mais sistemas de armazenamento baseados em discos (C: e D:, por exemplo). O FHS parte do princípio de que **tudo são arquivos**, e esses arquivos são protegidos e armazenados em diretórios específicos;
- Na maioria dos sitemas tipo UNIX, há cerca de **20 diretórios principais**. A pasta root é o repositório do administrador, enquanto outras desempenham tarefas específicas.

 ![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/a0446a9c-d80d-4133-8136-5e6f4b908256)

# Terminal
- No Linux, cada função que se deseja executar é realizada via terminal. No terminal, digita-se os códigos das funções que se deseja atingir;
- A maioria das funções do Linux são feitas via terminal. Assim, não há uma interface gráfica que facilte a visualização do acesso a determinadas funções, como ocorre em outros sistemas operacionais (Windows e MAC, por exemplo).


![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/ece21fad-78b3-41ce-bc9e-24be8ee3ce03)


# Terminal - Comandos
- Comandos utilizados no workshop: **mkdir, touch, nano, cd e ls**;
- **Mkdir**: Cria um novo diretório no PC;
- **Touch**: Cria um arquivo dentro de um determinado diretório;
- **Nano**: Permite que se modifque o conteúdo do arquivo;
- **Cd**: Acessa um determinado diretório. Por exemplo, ao digitar "cd Documents", o usuário "entra" no diretório Documents;
- **ls**: Exibe os arquivos dentro de um diretório.

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/57e86a53-d2b1-42a5-9d12-63b0baf1050f)


# Git
- O Git é um **Sistema de Controle de Versões Distribuído (DVCS)**, também desenvolvido por Linus Torvalds;
- O sistema do Git permite que os desenvolvedores armazenem os seus trabalhos, bem como a modificação de tais trabalhos, sejam eles próprios ou de outros desenvolvedores;
- Ele mantém um repositório local no computador com uma cópia de todos os arquivos do trabalho (projeto) desenvolvido, além um histórico de todas as alterações feitas nesses arquivos. Quando essas alterações são feitas, o Git realiza a função **commit**, que consiste em salvar as modificações realizadas num arquivo;
- O Git é muito útil para o trabalho em grupo, pois permite que os membros façam modificações nos projetos de cada um sem, necessariamente, alterar os trabalhos originais dos autores;
- Os projetos são salvos de maneira organizada e eficaz.

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/ce60f9c7-443b-43d2-9d14-a4ec2aeccf62)

# Git - Comandos

- O Git apresenta uma série de comandos, cada uma com a sua função específica. Entre as utilizadas no workshop e para fazer o EP, é possível citar:
- **Git init**: É a função utiilizada para inicializar o git dentro de um diretório. Esse é o primeiro comando a ser realizado para que faça sentido utilizar os outros. Portanto, é necessário digitar "git add" antes de qualquer operação com o git. Com esse comando, é criado/acessado um diretório especialmente para realizar as funções com o git (geralmente termina com /.git).
- **Git add**: Função empregada para adicionar um arquivo ao git, para que ele seja trabalhado postteriormente. É importante usar o git add, já que esse comando estará solicitando que, por exemplo, o arquivo adicionado vá para o diretório /.git, e com isso ser salvo. Por exemplo, supondo que um arquivo chamado "teste.py" foi criado com o comando nano. Para salvar, digita-se "git add teste.py".
- **Git status**: Exibe o status dos arquivos, tanto aqueles que foram salvos quanto os que não foram. Então, se o "teste.py" não foi adicionado com o git add, o status deverá exibir que, de fato, esse arquivo não foi salvo (geralmente, ele será exibido na cor vermelha) Se foi salvo, o "teste.py" ficará na cor verde.
- **Git commit**: Possui a função de gravar as alterações realizadas num arquivo. No caso, ao dar o commit, é necessário anexar uma mensagem com "--m"mensagem"" explicando a alteração feita, facilitando o entendimento de outros usuários.

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/6ba49ae6-513a-48d4-8f08-43a0bbd5bb46)

# GitHub
- O Github é um serviço em nuvem que hospeda o Git. Ele permite que os desenvolvedores colaborem e façam mudanças em projetos compartilhados enquanto mantêm um registro detalhado do seu progresso.
- No GitHub, é possível ver as alterações realizadas por todos os desenvolvedores dentro de um mesmo projeto, por exemplo. Isso acaba por auxiliar o grupo na organização de várias mudanças em um mesmo código. Caso as novas mudanças sejam problemáticas, ainda há o histórico das versões estáveis.

![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/59d6f47a-4576-4944-a1e8-ee367beb7ab1)

# Obrigado pela sua atenção!


![image](https://github.com/iOtavio/Workshop-sky/assets/124748405/c51bae39-d100-4d23-9ef0-571c5421b8bb)




