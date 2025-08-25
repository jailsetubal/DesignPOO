# Esse reposiório descreve 3 ténicas dentro de POO

# Herança

- O conceito de herança como o próprio nome já diz, tem a função de herdar funcões de uma classe superior (SuperClass). Neste código por exemplo, podemos observar que a classe "Animal" é o escopo onde há todas as entidades pré definidas, Ex: "Nome", e as Subclasses por exemplo "Cavalo", herda da classe animal as funções de "Nome", "Raça", "Cor", "Idade". Basta um escopo com entidades pré definidas e apartir disso novas classes podem herdar suas funções e realizar alterações com o método @Override

# Composição / Associação

- Já neste conceito, podemos observar que a implementação da composição é feita através de um novo método, diferente da Herança que herda de uma classe superior, a composição ela vem através de outro método, através de uma instância para ser implementada ao código. Ex: Na classe "Main", a classe "Cavalo" recebe um novo método para ser composto a sua funcionalidade através de uma instancia e se torna cavalo.dormir. Ou seja, O método dormir está sendo composto a classe cavalo através de uma instância

# Injeção de Dependencia

- Na injeção de dependência eu consegui observar que as implementações são feitas a partir da criação do objeto. Ou seja, o objeto é criado e nos parâmetros é feito a instância do método que você quer atribuir ao objeto criado