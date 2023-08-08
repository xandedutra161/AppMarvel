###### Sobre a API Marvel
A API da Marvel Comics é um conjunto de interfaces de programação de aplicativos fornecido pela Marvel Entertainment. 
Essa API permite que desenvolvedores de software acessem e interajam com uma ampla variedade de informações relacionadas ao universo das histórias em quadrinhos da Marvel.

# AppMarvel(Android)
O aplicativo apresenta a função de pesquisar e favoritar seus personagens favoritos, utilizando o padrão de Arquitetura MVVM e Clean Architecture.

###### Setup
- O aplicativo depende da chave privada e pública, que pode ser obtida na API Marvel Comics, mais informações em "https://developer.marvel.com/".
- Se você não possui uma conta, deverá ser criado uma conta para obter as chaves da API.
- Informe as chaves nos campos **"PUBLIC_KEY"** e **"PRIVATE_KEY"** no arquivo Constants do projeto antes de compilar o projeto.

###### Bibliotecas externas usadas
- Room -> Componente do Android Jetpack que facilita a criação, o gerenciamento e a interação com bancos de dados locais em App's.
- Dagger-Hilt -> Biblioteca padrão para incorporar a injeção de dependência do Dagger em um aplicativo Android.
- Navigation -> Simplifica a implementação da navegação em um aplicativo Android.
- Coroutines -> Para funções assíncronas.
- Retrofit & OkHttp3 -> Construir as APIs REST.
- DiffUtil -> Melhora o desempenho do RecyclerView.
- StateFlow -> Fluxo observável de detentor de estado que emite as atualizações de estado atual e novo para seus coletores.
- Gson -> Converter objetos Java (ou Kotlin) em formato JSON e vice-versa.
- Flow -> Biblioteca usada para modelar fluxos de dados.
- ViewBinding -> É uma abordagem mais segura e conveniente para lidar com a interação entre a interface de usuário em aplicativos Android.
- Glide -> Biblioteca de carregamento e cache de imagens para Android focada em rolagem suave.
- Timber -> Ferramenta de registro de log de código aberto.

![marvel](https://github.com/xandedutra161/AppBrasileirao/assets/141428908/f87b3064-c6db-495d-86c5-ddf236f4bc19)
