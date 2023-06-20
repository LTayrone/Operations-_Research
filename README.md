# Resolução de Problema de Programação Linear

Este é um projeto de resolução de um problema de programação linear que envolve a configuração de envio de automóveis das fábricas para os centros de distribuição, buscando minimizar o custo total. O problema é um exemplo clássico de um problema de rede de distribuição.

## Requisitos

Para executar o código deste projeto, você precisará ter o seguinte:

- Python 3.x instalado em seu sistema.
- A biblioteca ortools instalada. Você pode instalá-la usando o seguinte comando:

!pip install ortools


## Como executar o projeto

1. Clone este repositório para o seu computador ou faça o download do arquivo `main.py`.
2. Certifique-se de que você tem o Python e a biblioteca ortools instalados.
3. Abra um terminal ou prompt de comando e navegue até o diretório onde o arquivo `main.py` está localizado.
4. Execute o seguinte comando para iniciar a execução do código:


python main.py


## Resultado

Após a execução do código, você verá o resultado do problema de programação linear, incluindo a solução ótima encontrada e o custo total. Aqui está um exemplo de resultado:

Resultado Ótimo encontrado!/
Da Bahia para Minas: 200.0/
Da Bahia para o Rio: 150.00000000000003/
Da Bahia para Goiás: 150.0
De São Paulo para Minas: 0.0
De São Paulo para o Rio: 200.0
De São Paulo para Paraná: 300.0
De São Paulo para Santa Catarina: 100.00000000000001
De São Paulo para Rio Grande do Sul: 0.0
De Minas para o Rio: 0.0
De Minas para Goiás: 0.0
De Santa Catarina para o Rio Grande do Sul: 0.0
Distribuidor de Minas deixa de receber: 0.0
Distribuidor do Rio deixa de receber: 0.0
Distribuidor de Goiás deixa de receber: 0.0
Distribuidor do Paraná deixa de receber: 0.0
Distribuidor de Santa Catarina deixa de receber: 49.999999999999986
Distribuidor do Rio Grande do Sul deixa de receber: 250.0
Custo Total: R$ 28000.0



## Explicação do código

O código consiste em uma implementação do problema de programação linear usando a biblioteca ortools. Ele define as variáveis, restrições e a função objetivo do problema, e então chama o solver para encontrar a solução ótima. Após a resolução do problema, os resultados são exibidos na saída.

## Contribuição

Se você quiser contribuir para este projeto, sinta-se à vontade para fazer um fork e enviar suas melhorias por meio de pull requests.

## Licença

Este projeto está licenciado sob a licença MIT. Leia o arquivo [LICENSE](./LICENSE) para obter mais informações.
