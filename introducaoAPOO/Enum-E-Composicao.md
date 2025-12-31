🧾 Enumerações e Composição
📌 Enumerações (Enum)

Usadas para representar valores fixos e pré-definidos.

```
public enum StatusPedido {
    PENDENTE,
    PAGO,
    CANCELADO
}
```

Uso:
```
StatusPedido status = StatusPedido.PAGO;
```

Benefícios:

- Código mais seguro
- Evita valores inválidos
- Melhor legibilidade

📌 Composição

Relacionamento onde uma classe possui outra.

```
public class Endereco {
    String rua;
    String cidade;
}

public class Pessoa {
    String nome;
    Endereco endereco;
}
```

Uso:

```
Pessoa p = new Pessoa();
p.endereco = new Endereco();
p.endereco.cidade = "Rio de Janeiro";
```

Conceito-chave:

Uma Pessoa tem um Endereço
