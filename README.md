# Cotações

Gerador de cotações de viagem para Windows. Transforma o texto copiado do GDS,
da EasyJet, do site de hotéis e do site de viaturas numa cotação pronta a colar
num email do Outlook — com os títulos, negritos e espaçamentos do formato da casa.

## Descarregar

**[⬇ Cotacoes.exe — última versão](https://github.com/McGliebs/cotacoes/releases/latest/download/Cotacoes.exe)**

Não precisa de instalação: guarde o ficheiro (por exemplo no Ambiente de
Trabalho) e abra-o. Na primeira vez o Windows pode mostrar o aviso do
SmartScreen — clique em **Mais informações → Executar mesmo assim**.

Requisitos: Windows 10 ou 11.

## Como usar

1. **Copie o texto** da reserva — o ecrã do GDS, o resumo da EasyJet, a página
   do hotel ou a da viatura.
2. **Faça Ctrl+V em qualquer lado da janela** (ou clique em **Colar**). A app
   reconhece o tipo de texto, põe-no no campo certo e a cotação aparece logo à
   direita.
3. **Escreva os valores** nas caixas que aparecem na própria cotação, ao lado
   de cada *Valor:* (e o número de quartos do hotel). Enter passa à caixa
   seguinte. Os valores escritos mantêm-se mesmo que volte a colar texto.
4. **Copiar para Outlook** e cole na resposta ao cliente.

À esquerda aparece o que foi reconhecido em cada campo (ex.: *✓ 2 voos · 1
passageiro*) ou um aviso quando não foi reconhecido nada. Clique num campo para
ver ou corrigir o texto colado, ou para o colar lá diretamente; o × apaga-o.
Se a app não reconhecer um texto, pergunta em que campo o quer pôr.

A **abertura do email** (ex.: *Bom dia! Envio abaixo cotações conforme
solicitado.*) é opcional — escreva-a por cima da cotação ou use *Texto padrão*.

### O que a app reconhece

| Campo | Texto | Resultado |
|---|---|---|
| Voos GDS | ecrã da reserva (TAP, SATA…) | passageiros, voos com horas, bagagem incluída |
| Voos EasyJet | resumo da reserva no site | voos e a nota de "nada reservado" |
| Hotel | página do hotel | apenas quartos com **alojamento e pequeno-almoço** e reembolsáveis |
| Viatura | página do aluguer | modelo, datas, recolha/entrega, preço arredondado para cima |

### Mais do que uma semana

Depois de preencher uma semana, clique em **+ Guardar semana**: fica guardada
(com o título *Semana NN*) e os campos ficam livres para a seguinte. O email
final junta todas, separadas como nos emails habituais.

### Atalho no browser (opcional)

Em **Atalho do browser** (fundo do painel esquerdo), copie o endereço do
favorito e crie com ele um favorito no Edge ou Chrome. Numa página de voos,
hotel ou viatura, um clique nesse favorito copia o texto selecionado — ou a
página inteira, se não houver nada selecionado. Depois é só Ctrl+V na app.

### Tema

**Tema escuro / Tema claro** no fundo do painel esquerdo; a escolha fica
guardada. A app não guarda mais nada: o texto colado e as cotações
desaparecem ao fechar.

## Atualizações

Pouco depois de abrir, a app verifica se há uma versão nova neste repositório.
Se houver, mostra as novidades e pergunta se quer atualizar; a nova versão é
descarregada, verificada (SHA-256) e instalada sozinha. Sem internet, a app
funciona normalmente. Também pode procurar em **Acerca → Procurar atualizações**.

O histórico de versões está em [Releases](https://github.com/McGliebs/cotacoes/releases).
