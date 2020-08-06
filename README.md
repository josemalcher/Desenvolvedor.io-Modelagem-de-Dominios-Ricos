# Modelagem de Domínios Ricos

https://desenvolvedor.io/



## <a name="indice">Índice</a>

1. [Apresentação (1:00)](#parte1)     
2. [Objetivos do Curso (4:00)](#parte2)     
3. [DDD não é arquitetura em camadas (6:00)](#parte3)     
4. [Quando eu devo implementar DDD? (12:00)](#parte4)     
5. [Visão global do DDD (12:00)](#parte5)     
6. [Apresentação (12:00)](#parte6)     
7. [Papeis dentro de um projeto (4:00)](#parte7)     
8. [Como extrair e definir a linguagem ubíqua (11:00)](#parte8)     
9. [Como gerenciar a linguagem ubíqua (8:00)](#parte9)     
10. [Dicas essênciais (17:00)](#parte10)     
11. [Context Map (6:00)](#parte11)     
12. [Bounded Context (12:00)](#parte12)     
13. [Definindo contextos delimitados (24:00)](#parte13)     
14. [Modelo de Negócio vs Modelo de Domínio (24:00)](#parte14)     
15. [Integridade do Modelo (7:00)](#parte15)     
16. [Tipos de relacionamento entre contextos (23:00)](#parte16)     
17. [Teste os seus conhecimentos (5:00)](#parte17)     
18. [Teste os seus conhecimentos (2:00)](#parte18)     
19. [Teste os seus conhecimentos (5:00)](#parte19)     
20. [A evolução dos estilos arquiteturais (7:00)](#parte20)     
21. [Definindo um estilo arquitetural (7:00)](#parte21)     
22. [Transaction Script Pattern (3:00)](#parte22)     
23. [Table Module Pattern (6:00)](#parte23)     
24. [Domain Model Pattern (4:00)](#parte24)     
25. [Arquitetura Cebola (7:00)](#parte25)     
26. [Arquitetura Hexagonal (14:00)](#parte26)     
27. [Camadas sugeridas para atender o Domain Model (3:00)](#parte27)     
28. [Camada de apresentação (7:00)](#parte28)     
29. [Camada de aplicação (10:00)](#parte29)     
30. [Camada de Domínio (8:00)](#parte30)     
31. [Camada de Infraestrutura (4:00)](#parte31)     
32. [Domain Module (10:00)](#parte32)     
33. [Objetos de Valor (11:00)](#parte33)     
34. [Entidades (9:00)](#parte34)     
35. [Agregações (18:00)](#parte35)     
36. [Serviços de Domínio (7:00)](#parte36)     
37. [Repositórios (6:00)](#parte37)     
38. [Eventos de Domínio (8:00)](#parte38)     
39. [Iniciando o projeto (11:00)](#parte39)     
40. [Escrevendo a primeira entidade (25:00)](#parte40)     
41. [Validações de entidades (23:00)](#parte41)     
42. [Agregando com objetos de valor (7:00)](#parte42)     
43. [Testando comportamentos (14:00)](#parte43)     
44. [Persistindo com repositórios (23:00)](#parte44)     
45. [Utilizando serviços de domínio (11:00)](#parte45)     
46. [Lançando eventos de domínio (22:00)](#parte46)     
47. [Opções de camada de application (19:00)](#parte47)     
48. [Implementando a camada de application (18:00)](#parte48)     
49. [Conectando a camada de apresentação (17:00)](#parte49)     
50. [Desenvolvendo a apresentação - Validando o funcionamento (27:00)](#parte50)     
51. [Apresentação (28:00)](#parte51)     
52. [Teorema CAP (14:00)](#parte52)     
53. [Como sincronizar as bases? (10:00)](#parte53)     
54. [Command Stack - Query Stack (16:00)](#parte54)     
55. [Utilização de Sagas (19:00)](#parte55)     
56. [Setup do BC de Vendas (11:00)](#parte56)     
57. [Objetos de Domínio (33:00)](#parte57)     
58. [Command e Command Handler (23:00)](#parte58)     
59. [Manipulando comandos na prática (33:00)](#parte59)     
60. [Tratamento de notificações (35:00)](#parte60)     
61. [Event e Event Handler (40:00)](#parte61)     
62. [Implementando Queries (Query Stack) (24:00)](#parte62)     
63. [Adicionando novas funcionalidades com comandos (43:00)](#parte63)     
64. [Integração de BC's - Processamento do pedido (38:00)](#parte64)     
65. [Integração de BC's - Pagamento (33:00)](#parte65)     
66. [Integração de BC's - Finalização do pedido (27:00)](#parte66)     
67. [Visão geral da implementação (19:00)](#parte67)     
68. [Trabalhando com Sagas, Service Bus e Filas MSMQ (34:00)](#parte68)     
69. [Sobre o que é? (14:00)](#parte69)     
70. [Fatores essenciais (15:00)](#parte70)     
71. [[Mão na massa] - Setup do ES no projeto (18:00)](#parte71)     
72. [[Mão na massa] - Persistindo eventos (24:00)](#parte72)     
73. [[Mão na massa] - Finalizando a implementação do ES (26:00)](#parte73)     
74. [Palavras finais (10:00)](#parte74)     
75. [Zerei a vida ou só comecei? (12:00)](#parte75)     
---


## <a name="parte1">1 - Apresentação (1:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte2">2 - Objetivos do Curso (4:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte3">3 - DDD não é arquitetura em camadas (6:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte4">4 - Quando eu devo implementar DDD? (12:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte5">5 - Visão global do DDD (12:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte6">6 - Apresentação (12:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte7">7 - Papeis dentro de um projeto (4:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte8">8 - Como extrair e definir a linguagem ubíqua (11:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte9">9 - Como gerenciar a linguagem ubíqua (8:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte10">10 - Dicas essênciais (17:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte11">11 - Context Map (6:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte12">12 - Bounded Context (12:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte13">13 - Definindo contextos delimitados (24:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte14">14 - Modelo de Negócio vs Modelo de Domínio (24:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte15">15 - Integridade do Modelo (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte16">16 - Tipos de relacionamento entre contextos (23:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte17">17 - Teste os seus conhecimentos (5:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte18">18 - Teste os seus conhecimentos (2:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte19">19 - Teste os seus conhecimentos (5:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte20">20 - A evolução dos estilos arquiteturais (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte21">21 - Definindo um estilo arquitetural (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte22">22 - Transaction Script Pattern (3:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte23">23 - Table Module Pattern (6:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte24">24 - Domain Model Pattern (4:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte25">25 - Arquitetura Cebola (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte26">26 - Arquitetura Hexagonal (14:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte27">27 - Camadas sugeridas para atender o Domain Model (3:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte28">28 - Camada de apresentação (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte29">29 - Camada de aplicação (10:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte30">30 - Camada de Domínio (8:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte31">31 - Camada de Infraestrutura (4:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte32">32 - Domain Module (10:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte33">33 - Objetos de Valor (11:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte34">34 - Entidades (9:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte35">35 - Agregações (18:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte36">36 - Serviços de Domínio (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte37">37 - Repositórios (6:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte38">38 - Eventos de Domínio (8:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte39">39 - Iniciando o projeto (11:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte40">40 - Escrevendo a primeira entidade (25:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte41">41 - Validações de entidades (23:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte42">42 - Agregando com objetos de valor (7:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte43">43 - Testando comportamentos (14:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte44">44 - Persistindo com repositórios (23:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte45">45 - Utilizando serviços de domínio (11:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte46">46 - Lançando eventos de domínio (22:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte47">47 - Opções de camada de application (19:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte48">48 - Implementando a camada de application (18:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte49">49 - Conectando a camada de apresentação (17:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte50">50 - Desenvolvendo a apresentação - Validando o funcionamento (27:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte51">51 - Apresentação (28:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte52">52 - Teorema CAP (14:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte53">53 - Como sincronizar as bases? (10:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte54">54 - Command Stack - Query Stack (16:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte55">55 - Utilização de Sagas (19:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte56">56 - Setup do BC de Vendas (11:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte57">57 - Objetos de Domínio (33:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte58">58 - Command e Command Handler (23:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte59">59 - Manipulando comandos na prática (33:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte60">60 - Tratamento de notificações (35:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte61">61 - Event e Event Handler (40:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte62">62 - Implementando Queries (Query Stack) (24:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte63">63 - Adicionando novas funcionalidades com comandos (43:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte64">64 - Integração de BC's - Processamento do pedido (38:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte65">65 - Integração de BC's - Pagamento (33:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte66">66 - Integração de BC's - Finalização do pedido (27:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte67">67 - Visão geral da implementação (19:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte68">68 - Trabalhando com Sagas, Service Bus e Filas MSMQ (34:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte69">69 - Sobre o que é? (14:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte70">70 - Fatores essenciais (15:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte71">71 - [Mão na massa] - Setup do ES no projeto (18:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte72">72 - [Mão na massa] - Persistindo eventos (24:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte73">73 - [Mão na massa] - Finalizando a implementação do ES (26:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte74">74 - Palavras finais (10:00)</a>



[Voltar ao Índice](#indice)

---


## <a name="parte75">75 - Zerei a vida ou só comecei? (12:00)</a>



[Voltar ao Índice](#indice)

---

