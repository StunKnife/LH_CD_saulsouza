# LH_CD_saulsouza

Projeto de precificação.

Para rodar o modelo de precificação basta ler o arquivo PKL e utilizar os novos dados para previsão. por exemplo,

with open('seu_modelo.pkl', 'rb') as file:
    modelo_carregado = pickle.load(file)

Suponha que você tenha novos dados em uma variável chamada 'novos_dados'
previsoes = modelo_carregado.predict(novos_dados)

No repositório esta disponibilizado o notebook em jupiter com todo o código e raciocínio utilizado para desenvolver o case.
