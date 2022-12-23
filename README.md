# Entrega_AVF__Desenvolvimento_De_Aplicacoes_Para_Internet
## Avaliação Final

# Questionário:

# O que é uma Activity?
## Activity é o componente do Android responsável por mostrar telas ao usuário e permitir que ele interaja com essas telas através de toques e cliques.
Cada Activity representa uma tela e a programação por trás dela.

# Como funciona o cilco de vida de uma Activity?
## O ciclo de uma activity é definido por três momentos que são conhecidos como: fase de primeiro plano, fase visível e fase de segundo plano.
Na primeira fase ocorre quando a Activity está visível ao usuário, e é possivel que o mesmo interaja com ela.
Na fase visível ocorre quando a Activity está visível, porém não é possivel que o usuário interaja com ela.
na de segundo plano ocorre quando a Activity não está visível e obviamente o usuário não pode interajir com ela.

# O que é, e qual é a função do Adapter e do Viwholder?
## Adapter é um padrão estrutural e sua função é converter uma interface de uma classe para uma outra interface que o cliente espera encontrar.
## O Viwholder é uma abordagem utilizada para guardar um conjunto de views para que possam ser eficientemente acedidas e reutilizadas, quando necessário.
A finalidade da classe ViewHolder é guardar as views.

# O que é o Retrofit e por que utilizar ao invés de criar as chamadas manualmnete?
## O Retrofit é uma biblioteca desenvolvida pela Square que é utilizada como um REST Client no Android e Java. É utilizada na  biblioteca OkHttp para fazer os Http Requests. O Retrofit é mais viavel na utilização pois facilita na serialização dos objetos, na configuração, pois configura apenas o necessário para estabelecer uma cominucação, e a usabilidade por ser de forma mais prática para realizar uma requisição. por esses motivos é mais viável utiliza-lo ao que está criando várias funções para serializar os objetos.
