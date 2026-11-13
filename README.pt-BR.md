<p align="center"><img src="assets/qilo-icon-512.png" width="120" alt="Qilo"></p>

# Qilo

**Um app gratuito para balanças QardioBase — sem anúncios, sem conta, sem nuvem.**

> 🧪 **Beta — testes finais (0.5.3).** Tudo funciona na balança do desenvolvedor; agora estamos testando em mais celulares e balanças. Relatos de erro e sugestões são muito bem-vindos — veja [Ajude a testar](#ajude-a-testar).

[English](README.md) · [Manual do usuário](docs/manual-pt-BR.md) · [Política de privacidade](PRIVACY.md#português)

O app oficial da Qardio deixou de funcionar e, com ele, muitas balanças QardioBase ficaram sem uso. O Qilo devolve a balança ao dono: ele conversa com a balança direto por Bluetooth e guarda todas as medições no seu celular.

> O Qilo é um projeto independente, **sem vínculo, apoio ou relação com a Qardio, Inc.** "Qardio" e "QardioBase" são marcas de seus donos e aparecem aqui só para indicar com quais balanças o app funciona.

## Situação

| | |
|---|---|
| Balança | QardioBase 2 (modelo B200, firmware 2.04) |
| Plataforma | Android 8.0 ou mais novo (iOS previsto) |
| Fase | Beta, testes finais — procuramos testadores |

## Recursos

- **Pesagem** com composição corporal: peso, IMC, gordura, água, músculo e ossos (estimativas da própria balança, em % e kg), massa magra e taxa metabólica basal (equação de Mifflin-St Jeor).
- **Perfis** para a família toda, cada um com seu nome no visor da balança (até 6 letras ou números, em minúsculas). A balança reconhece quem está se pesando; pesagens de convidado não são gravadas.
- **Modos da balança**: completo, Smart Feedback, só peso e gestante.
- **Metas** por ritmo ou por data, com meta da semana, progresso e a tendência das últimas semanas. A meta também vai para a balança.
- **Histórico** em gráfico, lista e calendário dos dias em que você se pesou, incluindo os próximos dias de lembrete. Na lista dá para **comparar duas pesagens** lado a lado.
- **Notas** em cada pesagem, com etiquetas prontas (em jejum, após o treino, dormi mal…) ou texto livre.
- **Lembretes**: diário, semanal, quinzenal, mensal ou a cada N dias.
- **Health Connect**: envia peso e gordura para que Google Fit, Samsung Health e outros apps possam ler.
- **Bloqueio do app** com digital, rosto ou o bloqueio de tela do celular.
- **Exportação CSV**, inclusive no formato do Excel em português.
- **Ferramentas da balança**: vincular perfis que já estavam nela, desligar o Wi-Fi, restaurar padrões de fábrica.
- Tema claro e escuro · Português (Brasil) e inglês.

## Aviso de bem-estar

O Qilo é um app de bem-estar. Ele apenas registra os valores enviados pela balança e os organiza em gráficos e histórico. **Não é um dispositivo médico e não diagnostica, trata, cura nem previne nenhuma condição.** As referências exibidas, como as faixas de IMC da OMS, são informativas e não substituem a avaliação de um profissional. Para qualquer questão de saúde, procure um profissional de saúde.

Fontes: IMC e faixas, Organização Mundial da Saúde · taxa metabólica basal, Mifflin MD, St Jeor ST et al., *Am J Clin Nutr* 1990;51(2):241-7 · composição corporal: estimativa da própria balança por bioimpedância.

## Privacidade

Tudo fica no seu celular. O Qilo não tem servidor e nem pede acesso à internet. Os dados só saem do celular quando você exporta um CSV ou liga o Health Connect. Veja a [política de privacidade](PRIVACY.md#português).

## Como obter o app

Baixe o APK mais recente na página [**Releases**](https://github.com/mattaneto/qilo/releases) deste repositório e abra no celular (o Android vai pedir para permitir a instalação de apps dessa origem). A publicação na Play Store está prevista.

## Ajude a testar

Se você tem uma QardioBase 2, pode ajudar a fechar o beta:

1. Instale o APK das [Releases](https://github.com/mattaneto/qilo/releases) e siga o [manual](docs/manual-pt-BR.md).
2. Algo deu errado? Abra o menu ☰ › **Registro (testes)** › **Copiar registro**, depois [abra um relato de erro](https://github.com/mattaneto/qilo/issues/new?template=bug.yml) e cole o texto. O registro nunca contém senhas de Wi-Fi.
3. Ideias e melhorias: [abra uma sugestão](https://github.com/mattaneto/qilo/issues/new?template=suggestion.yml).

Outras balanças Qardio (QardioBase original, QardioBase X) ainda não são suportadas. Se você tem uma e pode ajudar a testar, conte numa issue.

**Procura-se parceiro para iOS.** O Qilo é feito em Flutter, então uma versão para iPhone é principalmente trabalho de plataforma (permissão de Bluetooth, Apple Saúde, notificações). Se você tem Mac e conta de desenvolvedor Apple e quer levar o Qilo para o iOS, [entre em contato](https://github.com/mattaneto/qilo/issues/new?template=suggestion.yml).

## Apoie o projeto

O Qilo é e vai continuar gratuito. Se ele trouxe sua balança de volta, você pode apoiar o desenvolvimento pelo **GitHub Sponsors** (o botão ❤ Sponsor nesta página).

## Créditos

Desenvolvido por **Aluísio da Matta (Matta)** — [github.com/mattaneto](https://github.com/mattaneto) — com a ajuda de IA (Claude, da Anthropic).
