# Manual do Qilo

Versão do app: **0.5.3** · [English](manual-en.md)

> **Aviso de bem-estar.** O Qilo apenas registra os valores enviados pela balança. Não é um dispositivo médico e não diagnostica, trata, cura nem previne nenhuma condição. Para qualquer questão de saúde, procure um profissional de saúde.

## 1. Primeiros passos

1. Instale o APK e abra o Qilo. Na primeira abertura aparece o **aviso de bem-estar**; toque em **Entendi** para continuar.
2. Toque em **Criar perfil** e preencha nome, **Nome no visor**, sexo, data de nascimento, altura, unidade e modo.
   - O **Nome no visor** é o que a balança mostra: até 6 letras ou números, sempre em minúsculas. Acentos viram a letra simples (Antônio → `antoni`). Se você deixar vazio, o app usa o primeiro nome.
3. Na aba **Medição**, toque em **Conectar** e permita o acesso ao Bluetooth.
4. Toque na balança ou suba nela para acordá-la. Quando aparecer **Conectada**, o app envia o perfil para a balança.
5. Suba na balança descalço. O seu nome aparece no visor e a pesagem chega ao app.

O app continua esperando a balança: toda vez que ela acordar, ele reconecta sozinho. Para economizar bateria, ele para de procurar depois de 3 minutos sem encontrar a balança e enquanto o app está em segundo plano (volta a procurar quando você abre o app). Para parar na hora, toque em **Desconectar**; para encerrar tudo, use **Sair do app** no menu ☰.

Uma reconexão sem mudanças não grava nada na balança. O app só escreve nela quando você altera um perfil ou uma meta, e para acertar o relógio na primeira conexão, depois de um reset ou a cada 7 dias (o relógio é necessário para a composição corporal).

## 2. Tela Medição

- **Data e hora** da última pesagem.
- **Peso** em destaque, com **gordura** e **músculo** logo abaixo.
- **Carinha e variação de 7 dias**: compara o peso atual com o de pelo menos 7 dias atrás.
  - Feliz (verde) quando o peso baixou, neutra quando ficou praticamente igual (menos de 0,1 kg de diferença) e triste (laranja) quando subiu.
  - Se a sua meta for **ganhar** peso, a regra se inverte: subir deixa a carinha feliz.
  - Com menos de 7 dias de histórico, a carinha fica neutra.
- **Meta**: o botão abre a tela de meta do perfil selecionado.
- **IMC** colorido pela faixa (abaixo do peso, normal, sobrepeso, obesidade), com a barra e o marcador.
- **Adicionar nota »**: veja a seção 6.
- Com mais de um perfil, os botões com os nomes no topo trocam o perfil exibido.

## 3. Várias pessoas na mesma balança

- Cada perfil do app é gravado na balança. Ela reconhece quem subiu pelo peso.
- Quando a balança fica em dúvida, ela mostra no visor a lista com os perfis e **guest** (convidado). Toque na balança com o pé para trocar a opção; a escolha vale depois de alguns segundos sem toque. O app mostra a mesma lista na tela, com a opção atual destacada.
- **Pesagens de convidado não são gravadas** nem aparecem no app.
- Para corrigir uma pesagem atribuída à pessoa errada: **Histórico › Lista**, toque na pesagem e escolha **Mudar perfil**.

## 4. Metas

Toque em **Definir meta** (ou no botão **Meta**) na tela Medição.

- **Peso desejado**: o app mostra a faixa saudável para a sua altura (IMC 18,5 a 24,9) e avisa se a meta ficar abaixo de IMC 18,5.
- **Ritmo**: 0,25, 0,5, 0,75 ou 1 kg por semana, sem ritmo, ou **Até uma data** — nesse caso o app calcula o ritmo e avisa se passar de 1 kg por semana.
- O cartão **Progresso da meta** mostra a meta da semana, quanto falta, a data prevista pelo plano, se você está à frente ou atrás, a data estimada no ritmo atual e a tendência por semana (calculada com as pesagens dos últimos 28 dias).
- A meta também é enviada para a balança, que a usa no modo Smart Feedback.
- O modo gestante não tem meta.

## 5. Histórico

- **Gráfico**: peso, IMC, gordura, água, músculo e ossos (só aparecem os que têm dados), em 30 dias, 90 dias, 1 ano ou tudo. A meta aparece como linha tracejada.
- **Lista**: todas as pesagens. Toque em uma para ver o detalhe numa janela que sobe da parte de baixo da tela, com os valores em linhas alternadas; o **X** no canto fecha a janela. Ali dá para editar a nota, mudar de perfil ou excluir.
  - **Comparar**: toque em **Comparar**, marque duas pesagens e toque em **Ver**. A tela mostra os valores lado a lado (a mais antiga primeiro, com a data em dd/mm/aaaa), a diferença de cada um na coluna **Δ** e quantos dias se passaram entre elas. Se marcar uma terceira, ela substitui a primeira.
  - O detalhe mostra cada percentual também em kg, a **massa magra** (peso − gordura) e a **taxa metabólica basal** (equação de Mifflin-St Jeor, a partir de peso, altura, idade e sexo; não aparece para menores de 18 anos nem no modo gestante).
  - Gordura, água, músculo e osso são estimativas da própria balança por bioimpedância.
- **Calendário**: os dias com pesagem ficam marcados com ✓, o dia de hoje tem contorno, e os **próximos dias de lembrete** aparecem com um relógio. Mostra também quantos dias com pesagem houve no mês e a sequência de dias seguidos. Toque em um dia marcado para ver as pesagens dele.
- **+**: adiciona um peso digitado à mão.

## 6. Notas

Em **Adicionar nota »** (na tela Medição ou no detalhe de uma pesagem) escolha etiquetas prontas — em jejum, após refeição, antes ou após o treino, após ir ao banheiro, com roupa, dormi mal, estresse, doente, bebida alcoólica, viagem, menstruação — e/ou escreva um texto de até 280 caracteres. As notas aparecem no detalhe e no CSV.

## 7. Lembretes

Na aba **Lembretes**, toque em **Novo lembrete**:

- **Horário**.
- **Repetir**: diário; semanal (escolha os dias); quinzenal (um dia da semana, semana sim, semana não); mensal (dia 1 a 31 — o dia 31 vira o último dia nos meses mais curtos); ou personalizado, a cada N dias.
- **Para**: todos ou um perfil. **Descrição** opcional.

Na primeira vez o Android pede permissão para notificações. Os lembretes podem chegar alguns minutos depois do horário, porque o app não usa a permissão de alarme exato. Use a chave ao lado de cada lembrete para ligá-lo ou desligá-lo.

## 8. Balança

Abra pelo ícone de Bluetooth no topo ou pelo menu ☰ › **Balança**. O ícone de pessoas, ao lado, abre os **Perfis**.

- **Aparelho**: modelo, firmware, bateria e Wi-Fi.
- **Desligar Wi-Fi**: sempre visível, ativo só com a balança conectada. Sem a nuvem da Qardio, o Wi-Fi ligado pode travar a balança. **O app nunca liga o Wi-Fi.**
- **Perfis na balança**: cada perfil gravado nela. Pelo menu de cada um: **Atualizar na balança** ou **Remover da balança**.
- **Perfil desconhecido** (criado em outro celular ou no app antigo): use **Vincular a um perfil** para associá-lo a um perfil existente ou novo. A balança só guarda um código, então você completa os dados; o nome no visor aparece assim que essa pessoa se pesar. O código é mantido, e a balança continua reconhecendo a pessoa.
- **Restaurar perfis na balança**: aparece depois de um reset, para gravar de novo os perfis do app com os mesmos códigos.
- **Acertar o relógio da balança**: grava a hora atual na balança, se a composição corporal parar de aparecer.
- **Restaurar padrões de fábrica**: apaga perfis, Wi-Fi e relógio da balança. O histórico no app é mantido. Pede confirmação duas vezes.
- **Esquecer esta balança**: para usar outra balança.

**Balança travada** (fica no emoji inicial e não pesa): é o Wi-Fi ligado sem a nuvem. Faça o reset pelo botão embaixo da balança e cadastre de novo pelo app.

## 9. Perfis

Menu ☰ › **Perfis**. Toque em um perfil para editar; as mudanças vão para a balança na hora (ou na próxima conexão). Para excluir, toque na lixeira — o app pede confirmação duas vezes e apaga também o histórico daquele perfil.

## 10. Configurações

Menu ☰ › **Configurações**:

- **Idioma**: igual ao celular, português (Brasil) ou inglês.
- **Tema**: igual ao celular, claro ou escuro.
- **Bloquear com biometria**: pede digital, rosto ou o bloqueio de tela do celular ao abrir o app e depois de 30 segundos em segundo plano.
- **Health Connect**: escolha **um** perfil (o dono do celular). Cada nova pesagem dele (da balança ou digitada) é enviada **automaticamente** ao Health Connect assim que é salva, onde Google Fit, Samsung Health e outros apps podem ler. **Enviar histórico** só é necessário uma vez, para mandar as pesagens antigas; reenviar não duplica.
- **Exportar dados (CSV)**: um perfil ou todos, no formato padrão ou no formato do Excel em português.


## 11. Menu lateral

No rodapé do menu ☰:

- **Registro (testes)**: só nas versões de teste. Mostra tudo o que o app conversou com a balança, o fluxo de conexão e os erros, com filtros. Use **Copiar registro** para copiar o texto (ou **Compartilhar registro** para enviar como arquivo) quando algo der errado. Cada pesagem salva ganha uma linha explicando o que a balança mandou e, se a composição faltar, o provável motivo. Senhas de Wi-Fi nunca aparecem.
- **Sobre**: versão, aviso de bem-estar, fontes das fórmulas, créditos e link para o GitHub do desenvolvedor.
- **Sair do app**: para a busca pela balança, desliga o Bluetooth do app e fecha a tela. O Android pode manter o app parado na memória, como faz com qualquer app, mas ele não procura a balança nem gasta bateria. Os lembretes continuam chegando.

## 12. Dúvidas frequentes

- **A balança não aparece**: confira se o Bluetooth está ligado e toque na balança para acordá-la. No Android 11 ou anterior, a localização também precisa estar ligada.
- **Meu nome não aparece no visor**: confira o **Nome no visor** do perfil (só minúsculas e números, até 6).
- **Sem gordura/músculo**: o perfil está em "Só peso" ou "Gestante", ou a pesagem foi de meias/sapatos.
- **Por que não aparecem gordura visceral, idade metabólica ou proteína?** Essas medidas dependem de fórmulas fechadas dos fabricantes, sem estudo publicado. O Qilo só mostra o que a balança envia, contas simples sobre esses valores e equações publicadas.
- **A pesagem veio sem gordura/músculo**: a balança não mediu a impedância (pés com meia, secos ou fora das placas metálicas). Pese de novo descalço, com os pés sobre as placas.
- **Onde ficam meus dados?** Só no celular. Desinstalar o app apaga tudo; exporte um CSV antes.
