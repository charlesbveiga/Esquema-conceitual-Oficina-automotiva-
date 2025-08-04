# Esquema-conceitual-Oficina-automotiva-
Modelagem de Decisões
Adicionado numero de telefone, para possível contato. 
Restrição de exclusividade na placa do veículo: Adicionada uma restrição de exclusividade, pois é a forma legal de identificar um veículo. 
Nome da equipe: Não especificado na narrativa, mas incluído como um atributo opcional para facilitar a identificação. 
Valores de referência de serviço: Incluídos diretamente na entidade SERVIÇO, pois a narrativa Pede uma "tabela de referência de mão de obra".
Associação de peças e serviços com OS: Como uma OS pode ter vários serviços e peças, tabelas associativas foram criadas. 
Quantidade de peças e serviços: Incluída para permitir casos em que mais de uma unidade é usada/executada. 
Conexão mecânica — OS: Nenhum link direto foi feito, pois a narrativa afirma que uma OS é realizada por uma equipe, e os mecânicos são associados à equipe, não diretamente à OS. 
Valor total da OS: Assume-se que seja a soma dos valores de serviço e peça associados. 
Status da OS: Não especificado, mas será um atributo enumerado (por exemplo, "Em andamento", "Concluído", "Aguardando aprovação").
