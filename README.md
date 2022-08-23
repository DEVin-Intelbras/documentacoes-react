<center>
    <img alt="Logo DEVinHouse" title="DEVinHouse" src="./assets/devinhouse-banner.png" />
</center>

## Documentações úteis para configurações de ferramentas em projetos utilizando ReactJS

### Configuração de ESLint

O ESLint é uma ferramenta que analisa o código e aponta quaisquer problemas que encontrar. Ele pode encontrar bugs, áreas potencialmente problemáticas, estilos de codificação ruins e questões de estilo.

A documentação de configuração pode ser acessada [aqui](/lint.md)

---

### Configuração do Prettier

O Prettier é um code formatter livre (MIT) e de código aberto, que tem por finalidade "forçar" um padrão de código. Ele realiza isso analisando o seu código e alterando-o de acordo com regras pré-definidas.

A documentação de configuração pode ser acessada [aqui](/prettier.md)

---

### Configuração de Path Aliases(apelidos)

Em projetos maiores onde há vários diretorios acaba sendo um pouco complexo a utilização de imports com caminhos relativos '../../../meuArquivo', pois precisamos ir navegando vários níveis até chegar ao arquivo desejado, e se movermos esse arquivo para outro diretório, novamente precisaremos reconfigurar esses caminhos.
Para evitar esse e outros problemas podemos utilizar o conceito de Path Alias, onde é dado apelido para esses caminhos relativos.

A documentação de configuração pode ser acessada [aqui](./alias.md)
