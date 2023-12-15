# DesafioTrelica_MECSOL
Desafio final da matéria Mecânica dos sólidos. Criar a melhor treliça dado alguns parâmetros de entrada usando Algoritmos genéticos.

![animacao](https://github.com/Gugarauj07/DesafioTrelica_MECSOL/assets/92393578/c634a848-7bac-444f-94ee-8f2e45df0146)

# Enunciado:
A ATIVIDADE 6 terá dois estudos de caso:
   - CASO 1 (1,0 pts): 
Otimizar a treliça tendo como variáveis as áreas das seções transversais das barras das treliças (A1,...., A13) e os comprimentos das barras 6, 8 e 10 (l6, l8 e l10);

   - CASO 2 (1,5 pts):  Otimizar a treliça tendo como variáveis as áreas das seções transversais das barras das treliças (A1,...., A13) e os comprimentos das barras 1, 2, 3, 4, 6, 8 e 10 (l1, l2, l3, l4, l6, l8 e l10). Atentar que a treliça deve ter vão livre mínimo de 8 metros.

Dados:
1) massa específica do aço: 7870 kg/m^3;
2) Módulo de elasticidade do aço: 200 GPa;

## Desafio: 
Refaça a otimização das treliças da T6 - Caso 2. Mas, desta vez, por questões de segurança, considere como restrição de otimização que as tensões axiais das barras da treliça devem ficar abaixo ou igual a sigmaE/Sg.
sendo:
sigmaE -> limite de escoamento do aço estrutural ASTM A36 = 300 MPa;

Sg -> coeficiente de segurança = 2;

Para consideração e implementação desta restrição de projeto utilize o método das penalidades.

Atenção para as regras do desafio:

1) Enviar a solução do T6_Caso 2 da treliça ótima em pdf que atenda as restrições de segurança e o vídeo explicando o algoritmo implementado (até 5 min) até às 12h00 do dia 20/08/2023 (nota ZERO após este horário) por este campo da atividade "DESAFIO" no classroom;

2) O arquivo pdf deverá conter:
   2.1) valores de deslocamento no ponto C (mm); 
   2.2) valor da massa total da treliça (kg); 
   2.3) valores das áreas das seções transversais (metro quadrado); 
   2.4) valores dos comprimentos de todas as barras em metros; 
   2.5) valores dos das forças axiais das barras (kN); 
   2.6) valores das tensões axiais das barras (MPa);
3) Esta atividade DESAFIO é individual;
2) A solução do T6_Caso 2 deve estar correta considerando as restrições de segurança;
3) Somente as três primeiros alunos(as) a entregar corretamente os resultados pontuarão no Desafio. Sendo que o primeiro aluno que entregar corretamente ficará com 10 de média, o segundo que entregar corretamente ficará com 9,5 de média e a terceiro aluno que entregar corretamente ficará com 9 de média, o quarto aluno que entregar corretamente ficará com 8,5 de média e o quinto aluno que entregar corretamente ficará com 8,0 de média. Não terá nota atribuída do sexto em diante aluno que enviar corretamente esta atividade DESAFIO;
4) O aluno que envia a atividade desafio terá automaticamente nota ZERO na atividade 6 (T6).
