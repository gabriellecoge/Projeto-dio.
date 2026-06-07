#  Caderno de Estudos — Clean Code (Robert C. Martin) 

À medida que avanço na carreira na área de tecnologia e automação financeira, percebo que a capacidade de escrever código legível, manutenível e expressivo é tão importante quanto dominar a lógica em si. O mercado valoriza profissionais que produzem código que outros podem entender e evoluir — não apenas código que funciona.

Objetivos de Estudo
 Compreender a filosofia por trás do Código Limpo e sua dimensão profissional
 Dominar os princípios práticos: nomes significativos, funções coesas, DRY, Regra do Escoteiro
 Entender as críticas ao livro e aplicar seus conceitos com senso crítico
 Construir um repertório de boas práticas aplicáveis em projetos reais (Python, automações)
 Produzir um miniguia de consulta rápida para revisões futuras

 Curadoria de Fontes
 https://www.youtube.com/watch?v=O5aWwBXPoh4&list=PLVc5bWuiFQ8H5P-7QB1_3LOJkOZNMnnpg
https://www.youtube.com/watch?v=9BxnJi8DKqY
https://www.youtube.com/watch?v=ln6t3uyTveQ
https://www.youtube.com/watch?v=alyVXP6b-wo

Engenharia de Prompts e "Cicatrizes"
1 - Qual é a regra prática para nomear variáveis, funções e classes segundo as fontes?
Variáveis e classes → substantivos que descrevem o que representam (usuario, PedidoFinanceiro)
Funções e métodos → verbos que indicam a ação (salvarUsuario, calcularTotal)
São preferíveis a nomes curtos
DIFICULDADE: O NotebookLM não trouxe exemplos negativos (o que não fazer).

2- Por que dizem que o livro Clean Code é polêmico?
O livro foi escrito em 2008 e algumas práticas são consideradas "otimização prematura" hoje
Não é recomendável para iniciantes absolutos — é preciso "experimentar o caos" primeiro
Regras como uso excessivo de polimorfismo e injeção de dependência podem gerar complexidade desnecessária
DIFICULDADE: O notebookLM, teve tendência a defender o livro

MINI GUIA DE ESTUDO
Nomes Significativos: Nomes devem revelar a intenção — sem abreviações misteriosas
Funções Pequenas: Cada função deve fazer apenas uma coisa
DRY: Não repita lógica — centralize em uma única função reutilizáve

Definiçao das palavras
Clean Code - Código escrito de forma legível, expressiva e manutenível, focado na compreensão humana
Responsabilidade Única - Princípio pelo qual cada função ou classe deve ter apenas um motivo para mudar
Frankenstein - Metáfora usada para descrever um sistema com tantos remendos e inconsistências que se torna impossível manter
Proporção 10:1 - Relação entre tempo lendo código (10x) versus tempo escrevendo (1x), que justifica o foco em legibilidade
