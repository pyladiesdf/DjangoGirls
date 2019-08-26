## Como contribuir com o Django Girls DF

### **Você tem contribuição nova para adicionar na documentação do DG?**

* **Tenha certeza de ter checado toda a contribuição feita até então** procurando no GitHub em nos arquivos do repositório [pyladies/DjangoGirls](https://github.com/pyladiesdf/DjangoGirls.git)

* A cada edição do evento crie um [projeto novo](https://github.com/pyladiesdf/DjangoGirls/projects/new) com o **nome do evento e o ano**, por exemplo ([Django Girls 2018](https://github.com/pyladiesdf/DjangoGirls/projects/1), [DG 2019](https://github.com/pyladiesdf/DjangoGirls/projects/2)). Nomeie as colunas e utilize a criação de [Issues](https://github.com/pyladiesdf/DjangoGirls/issues/new) para o controle e transparência do andamento das atividades.

* Mantenha a descrição das [Issues](https://github.com/pyladiesdf/DjangoGirls/issues) claras para que outras pessoas da comunidade possa contribuir, utilize labels para facilitar. Por exemplo o `midias`,`urgente`, `design`, `good firs issue`

* Mantenha o status das [Issues](https://github.com/pyladiesdf/DjangoGirls/issues) atualizadas. Se estão em backlog, se já foi iniciada ou se já foi finalizada.

* Para maior organização e distribuição de responsabilidades use o *assignees* de cada [Issue](https://github.com/pyladiesdf/DjangoGirls/issues) para atribuição de atividades. É um trabalho voluntário, então se não puder seguir com a **Issue** atualize o grupo de organização.


### **Você corrigiu a documentação?**

* Abra um novo **Pull Request** no GitHub com a correção.

* Garanta que o **PR** descreva claramento o problema e solução, que contenha toda a informação necessária para o template e que esteja relacionado a pelo menos uma Issue.

* Tenha certeza de que segue a [política de commit]()


## **Contribuindo**

#### 1. Configurando o repositório
Para poder contribuir, você precisa fazer um [fork](https://guides.github.com/activities/forking/) do repositório [pyladiesdf/DjangoGirls](https://github.com/pyladiesdf/DjangoGirls)

Em seguida clone o fork para sua máquina local:
```bash
git clone https://github.com/pyladiesdf/DjangoGirls.git
```

#### 2. Atualizando o fork

Caso você já tenha feito o [fork]() em outro momento e está desatualizado. É importante [atualizar](https://gist.github.com/rdeavila/9618969) o seu repositório. Primeiro é preciso adicionar um novo *remote*; pode chamá-lo de **djangogirls**

```bash
git add remote djangogirls  https://github.com/pyladiesdf/DjangoGirls.git
```

Obtenha todos os branches deste novo remote como djangogirls/master por exemplo

```bash
git fetch djangogirls
```

Certifique-se que está na branch master

```bash
git checkout master
```

Reescreva o seu branch master, de forma que os seus commits que não estão no projeto original apareçam, e que os seus commits fiquem no topo da lista:

```bash
git rebase djangogirls/master
```

Se você não quiser reescrever o histórico do seu branch master (talvez porque alguém já o tenha clonado) então você deve substituir o último comando por um

```bash
git merge upstream/master
```

No entanto, para fazer com que futuros [pull requests]() fiquem o mais limpos possível, é uma boa ideia fazer o rebase.

Se você fez o rebase do seu branch a partir de upstream/master, talvez você precise forçar um push para o seu próprio repositório do Github.
Você pode fazer isso com:

```bash
git push -f origin master
```

VocÊ vai precisar fazer isso com o -f apenas na primeira vez que você faz um rebase.

#### 3. Configure o ambiente de desenvolvimento
Para a edição dos arquivos *markdown* é preciso um editor de texto apenas.


#### 4. Pull Request
Acesse o seu fork do repositório oficial (ex: https://github.com/pyladiesdf/DjangoGirls) e clique em "Pull Requests" no painel. Na próxima página, pressione "New pull request" no canto superior direito.

Selecione como base a branch **master** do repositório oficial(**pyladiesdf/djangogirls**) e compare com a branch referente a novas informações ou materiais, por exemplo **feat#material_introducao_python**, em seguida clique em "Create new pull request".

Preencha o template sugerido com as informações necessárias para descrever a mudança proposta, conecte o Pull Request a **Issue** relacionada e confirme a criação do Pull Request.

O seu Pull Request será analizado e a equipe responsável pelo projeto garante prover o feedback mais claro possível para sua proposta de mudança.

Com :heart:,

**PyLadies DF**.
