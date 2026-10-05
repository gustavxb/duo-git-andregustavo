### Reflexão sobre o Conflito

**1. O que exatamente causou o conflito?**
Ambas as pessoas alteraram a mesma linha do arquivo `README.md` simultaneamente. Como tentamos enviar as alterações para o repositório remoto (GitHub) sem antes sincronizar o histórico do colega (`git pull`), o Git detectou que as edições colidiam na mesma linha.

**2. Como vocês decidiram qual versão manter?**
Nós conversamos e decidimos apagar os marcadores de conflito, unindo a ideia dos dois em um título novo que representasse o trabalho conjunto, ao invés de manter apenas a edição isolada de um.

**3. O que vocês fariam diferente para evitar conflitos?**
Manteríamos uma comunicação mais próxima para avisar em qual arquivo estamos mexendo naquele momento e, o mais importante, rodaríamos `git pull` com mais frequência (sempre antes de começar uma nova alteração) para ter certeza de que estamos editando a versão mais recente do projeto.
