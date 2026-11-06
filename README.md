# Cadastro de Pessoas — Mundo 3, Missão 1

Exercícios Java de programação orientada a objetos com cadastro de pessoas físicas e jurídicas e persistência em arquivos binários.

## Projetos

| Pasta | Entrada | Comportamento |
| --- | --- | --- |
| `CadastroPOO/` | `model.CadastroPOO` | Demonstra inclusão, gravação e recuperação de pessoas |
| `CadastroPOO2/` | `model.CadastroPOO2` | Menu de terminal para incluir, alterar, excluir, buscar, listar, salvar e carregar |

Cada pasta contém seu próprio `build.xml`, `nbproject/` e `src/`. As propriedades dos dois projetos declaram **Java 17**, codificação UTF-8 e construção pelo Apache Ant/NetBeans.

## Executar no NetBeans

```sh
git clone https://github.com/alvesvslucas/Missao-1-Mundo-3.git
cd Missao-1-Mundo-3
```

1. Instale um JDK compatível com o nível Java 17.
2. No Apache NetBeans, use **Abrir Projeto** e selecione `CadastroPOO` ou `CadastroPOO2`.
3. Confira a plataforma Java nas propriedades e use **Limpar e Construir**.
4. Execute o projeto. No segundo exercício, interaja pelo terminal de entrada/saída da IDE.

## Persistência

Os exercícios gravam e recuperam arquivos `.bin` no diretório de execução. A primeira versão usa `listaPessoasFisicas.bin` e `listaPessoasJuridicas.bin`. Use uma cópia de trabalho e dados fictícios: executar a demonstração pode regravar esses arquivos.

Os fontes consultados utilizam armazenamento em arquivos; não exigem instalação de banco de dados para esses fluxos.

## Estado e créditos

Compilação e execução não foram realizadas nesta revisão documental. Os comentários dos fontes de entrada registram `@author grego`; esse crédito foi preservado, sem atribuir autoria exclusiva do código a este perfil.
