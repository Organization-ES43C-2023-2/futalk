# 1. Requisitos Não Funcionais
A ***tabela 2 a seguir*** contém os **Requisitos Não Funcionais (RNF)** utilizando a técnica de Brainstorm.
ID   | Requisitos NF   | Categoria/Tipo  | Prioridade | Requisitos Relacionados
--------- | ------------------ | --------------- | ---------- | -----------------------
RNF01 | O sistema deve verificar se o email para conta é valido. | Confiabilidade/Segurança | Alta | RF01 |
RNF02| O sistema deve estabelecer um limite para certas personalizações relacionadas ao perfil do usuário (como a quantidade de caracteres que o usuário pode colocar no nome). | Implementação | Alta | RF02 |
RNF03 | O sistema deve restringir pedido de participações em jogos, campeonatos, ligas, onde o administrador do mesmo designou uma idade especifica (como: Partida com idade minima 40 anos, restringir pessoas que tenham 5 ou mais anos de diferença entre a idade exigida de forma automática). | Padrões | Baixa | RF03 |
RNF04 | O sistema não deve permitir postagens textuais com mais de 2000 caracteres. | Implementação | Média | RF01, RF05 |
RNF05 | O sistema não deve permitir postagens de vídeos acima de três minutos. | Implentação | Média | RF01, RF05 | 
RNF06 | O sistema não deve permitir postagem de arquivos maiores que um gigabyte. | Implementação | Média | RF01, RF05 |
RNF07 | O sistema deve emitir um alerta de públicação com conteúdo sensível. | Privacidade | Baixa | RF01, RNF08 |
RNF08 | O sistema deve pedir que um usuário aceite os termos para criação de uma comunidade dentro do app. | Ético | Baixa | RF01, RF06 |
RNF09 | O sistema deve notificar pedidos interação com usuários de perfis | Entrega | Média | RF01, RF07, RNF10|
RNF10 | O sistema deve notificar noticias | Entrega | Média | RF01, RF03 |

Tabela 2: Requisitos Não Funcionais
# 2. Referências
