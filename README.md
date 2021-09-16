# ByteBank

O projeto ByteBank foi meu primeiro projeto utilizando o Framework Angular. Nele pude trabalhar com novas linguagens,como: <strong>TypeScript</strong> e <strong>SCSS</strong>, além do HTML.<br>
<br>
A ideia do projeto é realizar uma simulação de transferência bancária, no qual, o formulário apresenta dois inputs, um de valor e outro de destino. Depois que o usuário coloca as informações e clica no submit de transferir o sistema manda o usuário para outra página, no caso esse que apresenta os valores, horários e contas de destino que foram feitos.
<br><br>
Comecei primeiro construindo as propriedades componentes, construindo o componente extrato e o componente nova transferência, e durante esse processo se deu a necessidade de converter as informações que estão em inglês em pt-br, pois são formatos que o usuário não está acostumado. Logo depois,surgiu a necessidade de manter os dados persistentes, já que toda a vez que a página era atualizada os dados erão perdidos,dai então criei uma classe de serviço, no caso um arquivo chamado service, que têm a responsabilidade de manter esses dados dentro dessa classe.<br><br>
Mas ao preparar essa classe percebi que com ela em mãos poderíamos utilizar uma API externa, inclusive, para guardar esses dados. E com esses dados persistentes em uma API externa os nossos componentes estavam prontos. Então o próximo passo foi dar algumas rotas para ele. Transformei ele em página através do serviço de roteamento do angular. Com isso a aplicação estava pronta, a funcionalidade estava entregue e o projeto finalizado.<br><br>
<img class="imagens">
![ByteBank 01](https://user-images.githubusercontent.com/83931417/133691877-c5f59ddf-e5dc-4ccc-8f53-cd7183d11635.png)
![ByteBank 02](https://user-images.githubusercontent.com/83931417/133691879-e844d43d-0805-4922-ae4e-d5dd9f423b76.png)
![ByteBank 03](https://user-images.githubusercontent.com/83931417/133691881-54c65e65-941a-445c-bae5-05ceb1422f88.png)
</img>

