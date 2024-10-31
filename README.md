# **AppProva2 (Folha de pagamento)**

> Um aplicativo Android desenvolvido para calcular uma formula de folha de pagamento.

## Descrição
O **AppProva2** permite ao usuário poder calcular o seu IR, INSS e seu salário liquido assim fazendo uma simulação de folha de pagamento para o usuário.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Folha-de-pagamento
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal onde ocorrera o calculo da folha de pagamento
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal 
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/eda6ffd9-878d-4f5b-8ba2-6ec6f22e4835)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 3 EditText para, Nome do funcionário, o Salário Bruto do usuário e a quantidade de filhos se caso ele tiver, Um RadioGroup onde estarão dois RadioButton para os sexos masculino e feminino serem escolhidos, um botão para processar a conta total informada adequadamente para o usuário, e no final o TextView para mostrar o resultado final no, IR, INSS e o salário liquido total do calculo com as informações insiridas de maneira certa, e o titulo principal da pagina.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
