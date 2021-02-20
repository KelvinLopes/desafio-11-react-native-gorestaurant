# GoRestaurant

Para rodar esse app em sua máquina é necessario ter o ambiente do sistema
preparado para o **React Native**.

Essa é a versão mobile do GoRestaurant.

### Funções

* Listar pratos do cardápio
* Listar pratos do cardápio por categoria
* Listar pratos favoritos
* Procurar os pratos do cardápio

* Fazer pedidos
* Listar pedidos

## Como usar?

Baixe o repositório na opção de download ou :

Crie um diretório via terminal ou via gerenciador de arquivos.

No seu terminal acesse essa pasta e execute o comando abaixo:

```git clone https://github.com/KelvinLopes/desafio-11-react-native-gorestaurant```

Após ter acesso ao diretório do projeto rode esse comando para instalar todas as dependências:

```yarn```

Caso necessário rode também:

```yarn upgrade```

Rodar o projeto no Android:

```npx react-native start```

e após 

```npx react-native run-android```

Rodar o projeto no IOS:

```npx react-native start```

e após 

```npx react-native run-ios```

Rodar a fake api ```yarn json-server server.json -p 3333```

ou caso use o ip de sua máquina:

```yarn json-server server.json  --host mumber_ip_your_machine -p 3333```

# Dica Android

Caso não consiga acessar as informações da API no Android, 

coloque o ip de sua máquina conforme as dica do arquivo ```baseUrl.example.ts.```

e executar o comando ```adb reverse tcp:3333 tcp:3333```

Rodar os testes no projeto ```yarn test```