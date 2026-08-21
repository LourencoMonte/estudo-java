ESTADO - 20/08/2026 (sessão 45min)
CAPITULO ATUAL: 02 - Orientacao a Objetos (revisao antes de avancar)
ULTIMA SESSAO: 20/08/2026 - formato 45min (esqueleto+super / ==vs.equals)
FECHOU (passou no teste de saida):
- Esqueleto de classe (abstrata + construtor nomeado + super no construtor
  da subclasse) - fechou apos reescrever 3x, corrigindo: parenteses
  indevido no nome da classe, "Super" com maiuscula, e falta do parametro
  (int valor) na assinatura do construtor filho. Teste de saida (explicar
  por que o parametro precisa ser declarado na assinatura) respondido
  corretamente com palavras proprias.
- super() - fechou junto com o item acima (mesma trava).
- == vs .equals() em String - fechou. Reconstruiu corretamente com
  analogia propria (endereco = casa, .equals = comparar conteudo da
  casa). BONUS: entendeu tambem o String Pool (por que
  String a="ana"; String b="ana"; da true no ==, mas new String("ana")
  da false) - ponto que nem estava no roteiro original, adicionado por
  duvida genuina do proprio aluno durante o teste de saida.
  FILA DE RECUPERACAO (por ordem de prioridade - teto: 5 itens):
1. Overload - conceito errado ("varias classes repetidas"). Correto: mesmo
   metodo, mesma classe, parametros diferentes. Nao trabalhado nesta
   sessao - segue pendente de reconstrucao.
2. Heranca e polimorfismo (extends, override) - override respondeu certo
   em sessao anterior, mas ainda sem teste de saida formal (escrever do
   zero). Manter na fila.
   REGRA DA FILA: 2/5 - fila esvaziou de 5 para 2. Folga real agora - pode
   receber 1 item novo na proxima sessao sem estourar o teto.
   EM ABERTO / TRAVADO:
- Estruturacao de classe sem consulta - RESOLVIDO nesta sessao apos 3a
  tentativa. Recomendacao: ainda pedir para reescrever do zero na abertura
  de mais 1-2 sessoes para confirmar retencao antes de considerar
  definitivamente consolidado (nao e so 1 acerto = dominio permanente).
  PROJETO DE EXERCICIO (Cap.2): sistema de pagamentos - Pagamento (abstrata),
  PagamentoCartao, PagamentoPix, ValorInvalidoException, Main.
  PENDENTE: subir ao GitHub com README e commits.
  PROJETO DE PORTFOLIO (Cap.5, ainda nao iniciado): API de gestao de expedicao.
  VETADO / PULADO:
- Capitulo 3 (Collections/Streams) - TRAVA TEMPORAL ate 03/09. Fila
  esvaziou bem hoje - prazo parece viavel agora, mas overload e
  heranca/polimorfismo ainda precisam de teste de saida formal antes
  de considerar Cap.2 fechado de verdade.
  HABITOS ATIVOS:
- README caprichado em cada repo
- Commit semantico; meta de 5 dias por semana
- Relatorio de aprendizado ao fim da sessao