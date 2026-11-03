# Cotações

Gerador de cotações de viagem para Windows. Transforma o texto copiado do GDS,
da EasyJet, da Jet2, da Wizz Air, da TUI fly, da Eurowings, do site de hotéis e do site de viaturas numa cotação pronta a colar
num email do Outlook — com os títulos, negritos e espaçamentos do formato da casa.

## Descarregar

**[⬇ Cotacoes.exe — última versão](https://github.com/McGliebs/cotacoes/releases/latest/download/Cotacoes.exe)**

Não precisa de instalação: guarde o ficheiro (por exemplo no Ambiente de
Trabalho) e abra-o. Na primeira vez o Windows pode mostrar o aviso do
SmartScreen — clique em **Mais informações → Executar mesmo assim**.

Requisitos: Windows 10 ou 11.

## Como usar

1. **Copie o texto** da reserva — o ecrã do GDS, o resumo da EasyJet, da Jet2, da Wizz Air, da
   TUI fly ou da Eurowings,
   a página do hotel ou a da viatura.
2. **Faça Ctrl+V em qualquer lado da janela** (ou clique em **Colar**). A app
   reconhece o tipo de texto, põe-no no campo certo e a cotação aparece logo à
   direita.
3. **Escreva os valores** nas caixas que aparecem na própria cotação, ao lado
   de cada *Valor:* (e o número de quartos do hotel). Enter passa à caixa
   seguinte. Os valores escritos mantêm-se mesmo que volte a colar texto.
   Com mais do que um preço, a cotação termina com o **Total:** — a soma
   dos voos, hotel e viatura, atualizada enquanto escreve (no email só sai
   quando todos os valores estão preenchidos, e não sai quando há opções).
4. **Copiar para Outlook** e cole na resposta ao cliente.

À esquerda aparece o que foi reconhecido em cada texto colado (ex.: *✓ 2 voos ·
1 passageiro*) ou um aviso quando não foi reconhecido nada. Clique numa linha
para ver ou corrigir esse texto; o × apaga-o. Se a app não reconhecer um texto,
pergunta em que campo o quer pôr.

### Várias opções de voo e de hotel

Cada texto de voos (GDS ou low-cost) ou de hotel que colar é **mais uma opção**:
não substitui o anterior. Na cotação aparecem como *Opção 1:*, *Opção 2:*… — os
voos por data — cada uma com o seu valor. À esquerda cada opção tem a sua linha
(com o primeiro voo ou o nome do hotel) e o seu ×, para a tirar. Para acrescentar
uma opção escrita à mão, clique no nome do campo (**+ opção**). Para mudar a
ordem, use as setas **▲ ▼** ao lado de cada *Opção N:* na cotação — os voos (GDS
e low-cost juntos) e os hotéis, cada um na sua secção; o valor escrito acompanha
a opção, e a ordem mantém-se se colar mais opções (as novas vão para o fim). Colar o mesmo
texto duas vezes não o repete. A viatura é uma só: colar outra substitui-a.

A **abertura do email** (ex.: *Bom dia! Envio abaixo cotações conforme
solicitado.*) é opcional — escreva-a por cima da cotação ou use *Texto padrão*.

### O que a app reconhece

| Campo | Texto | Resultado |
|---|---|---|
| Voos GDS | ecrã da reserva (TAP, SATA…) | passageiros (com título e *(CHD)* nas crianças), voos com horas, bagagem incluída |
| Voos low-cost | cesto/resumo da reserva no site da **EasyJet**, da **Jet2** (com o painel **Open all** aberto) da **Wizz Air** da **TUI fly** (com **Show booking overview** aberto) ou da **Eurowings** (o *Booking overview* da página dos passageiros) | voos, a bagagem incluída na tarifa e a nota de "nada reservado" |
| Hotel | página do hotel no **smytravel**, **GoGlobal** (PT ou EN), **W2M** ou **TBO** | apenas tarifas com **alojamento e pequeno-almoço** e reembolsáveis; número de quartos lido da página |
| Viatura | página do aluguer | modelo, datas, recolha/entrega, preço arredondado para cima |

Os voos de cada origem (GDS, low-cost) aparecem num só bloco — ida e volta
juntas, com um só valor — em colunas alinhadas, e o percurso vem com o nome dos
aeroportos (*Funchal - Lisboa*) em vez dos códigos. Se o texto do GDS trouxer também a
reserva anterior (ecrã do Amadeus), só conta a última.

Na EasyJet, na Jet2, na Wizz Air, na TUI fly e na Eurowings a linha da bagagem (*•( Inclui: … )*) é lida da própria
página — malas de cabine e de porão de cada voo, por passageiro — por isso
acompanha a tarifa escolhida (EasyJet Light, Smart+, Extra, All-in; Wizz Smart, Go, Plus…), com as medidas de cada companhia, e as malas
compradas à parte. Se a ida e a volta tiverem bagagem diferente, sai uma linha
por voo. Na Jet2, abra **Open all** (por baixo de *Total so far*), e na TUI fly
**Show booking overview** (por baixo do preço total), antes de copiar ou enviar
a página: é aí que estão os voos, o número do voo e a hora de chegada. Na
Eurowings, abra **Services included and additional services booked** para a
linha da bagagem — sem isso os voos aparecem, mas a app avisa que falta a
bagagem.

### Mais do que uma semana

Depois de preencher uma semana, clique em **+ Guardar semana**: fica guardada
(com o título *Semana NN*) e os campos ficam livres para a seguinte. O email
final junta todas, separadas como nos emails habituais.

### Enviar a página do browser (sem copiar)

A extensão do **Gerador Faturas** (a do SIGAV, versão 1.8.0 ou mais recente)
envia a página aberta diretamente para o Cotações. Numa página de voos, hotel
ou viatura, clique no ícone da extensão → **Enviar esta página**, ou use o
atalho **Alt+Shift+C**. Vai o texto selecionado ou, sem seleção, a página
inteira — e aparece logo no campo certo. Pode enviar o voo, o hotel e a
viatura seguidos e só depois vir à app. O Cotações tem de estar aberto.

Sem a extensão, em **Extensão do browser** (fundo do painel esquerdo) há um
favorito alternativo, «Copiar p/ Cotações», que copia a página com um clique
para depois fazer Ctrl+V na app.

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
