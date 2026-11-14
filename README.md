<p align="center">
  <img src="assets/tiger-media-tools.png" width="128" alt="Tiger Media Tools">
</p>

<h1 align="center">Tiger Media Tools</h1>

<p align="center">
  Ferramentas para quem grava, trata e entrega vídeo em volume.<br>
  <b>Speed Batch</b> · <b>Smart Frame</b> · <b>Camera Ingest</b>, num só lugar.
</p>

---

## O que é

O **Tiger Media Tools** é o aplicativo que reúne as ferramentas da Tiger. Você baixa só ele, entra na sua
conta uma vez e, de dentro dele, instala, abre e atualiza os outros três:

| Aplicativo | Para que serve |
|---|---|
| **Speed Batch** | Processa lotes de vídeo: rampas de velocidade, LUT, exposição, música e rotação, exportados em paralelo. |
| **Smart Frame** | Tira fotografias em qualidade total dos seus vídeos, em lote, com LUT e ajustes de cor. |
| **Camera Ingest** | Traz os arquivos direto da câmera para o Mac, por cabo ou Wi-Fi, numa pasta de trabalho. |

Os três funcionam sozinhos, mas foram feitos para trabalhar juntos: o Camera Ingest entrega os arquivos numa
pasta, e o Speed Batch e o Smart Frame podem **monitorar essa pasta** e receber cada arquivo assim que ele chega.

**Um plano único dá acesso aos três.** Todo o processamento é feito no seu Mac: nenhum vídeo é enviado para a internet.

---

## Speed Batch

Para quem precisa entregar muitos vídeos com o mesmo tratamento, sem abrir um editor para cada um.

- **Fila de vídeos:** arraste arquivos ou pastas inteiras. Cada vídeo é analisado sozinho e entra na fila.
- **Rampas de velocidade (curvas):** escolha uma curva por vídeo, ou deixe a *Distribuição automática* repartir
  os vídeos entre as curvas ativas. Crie, duplique e renomeie curvas em **Ajustes**.
- **FPS automático:** o FPS de gravação é lido do próprio arquivo (e do XML das câmeras Sony). Dá para corrigir à mão
  quando a câmera não informa, como em Canon e Nikon.
- **LUT com intensidade** e **Exposição** de −2 a +2 EV. A imagem do painel mostra exatamente o que será exportado.
- **Música:** mantenha o áudio original, troque por uma faixa da sua biblioteca ou remova o áudio.
- **Rotação automática** de vídeos gravados na vertical.
- **Exportação em paralelo**, com pausa, cancelamento, progresso por vídeo e tempo restante do lote.
  Com **Exportar automaticamente**, cada vídeo sai assim que fica pronto.
- **Seguro com seus arquivos:** os originais nunca são apagados nem movidos, e um arquivo exportado nunca é
  sobrescrito sem perguntar.

## Smart Frame

Para tirar fotos dos vídeos sem perder qualidade.

- **Biblioteca** em grade ou lista, com importação por arraste, clique, pasta monitorada ou pelo Camera Ingest.
- **Frames por vídeo:** escolha quantas fotos tirar de cada vídeo, ou por segundo de vídeo.
- **Escolher frame manualmente:** um player com barra de rolagem para exportar o quadro exato que você quer.
- **LUT (0 a 200 %), exposição e ajustes de cor**, com prévia do tratamento.
- **Exportação em qualidade total**, lida direto do vídeo original, com pausa e cancelamento.
- **Aviso de arquivos repetidos** ao importar. Nada é apagado.

## Camera Ingest

Para tirar os arquivos da câmera sem leitor de cartão.

- **Sony:** câmeras compatíveis com o Camera Remote SDK, por Wi-Fi ou USB. Validado em ZV-E1, A6700 e A7 V
  (a A7 III não funciona).
- **Canon (EOS R)** por USB ou Wi-Fi (CCAPI) e **Nikon (Z)** por USB: já disponíveis, ainda em validação com câmeras reais.
- **Fujifilm:** a câmera não permite acesso aos arquivos pelo computador. Use um leitor de cartão.
- **Importação automática por regra:** escolha quais tipos de mídia entram sozinhos e se valem os arquivos novos,
  os que já estavam no cartão, ou os dois.
- O app traz um guia **Como conectar uma câmera**, marca por marca.

---

## Download

<p align="center">
  <a href="https://github.com/tigerlabco-png/tiger-media-tools-releases/releases/download/hub/Tiger-Media-Tools.dmg"><b>⬇︎ Baixar Tiger Media Tools para Mac</b></a><br>
  <sub>Sempre a versão mais nova</sub>
</p>

### Requisitos

- Mac com chip **Apple Silicon** (M1, M2, M3, M4 ou mais novo). Macs com chip Intel ainda não são compatíveis.
- **macOS 13 (Ventura)** ou mais recente.
- Internet para entrar na conta e instalar. Depois disso, os apps funcionam até **7 dias** sem internet.

---

## Como instalar

**1. Baixe e copie para Aplicativos.**
Clique em **Baixar Tiger Media Tools para Mac**, acima. Abra o arquivo `Tiger-Media-Tools.dmg` e arraste o
**Tiger Media Tools** para a pasta **Aplicativos**.

**2. Libere a primeira abertura (uma vez só).**
Os aplicativos ainda não têm o certificado pago da Apple, então na primeira vez o macOS pode dizer que
*"não é possível verificar o desenvolvedor"* ou que *"o app está danificado"*. Isso é esperado. Para liberar:

1. Abra o **Terminal** (Finder → Aplicativos → Utilitários → Terminal).
2. Cole o comando abaixo e pressione Enter:

   ```bash
   xattr -cr "/Applications/Tiger Media Tools.app"
   ```

3. Feche o Terminal e abra o Tiger Media Tools pela pasta Aplicativos.

O comando vale só para o Tiger Media Tools e não muda nenhuma outra configuração do seu Mac. O Speed Batch,
o Smart Frame e o Camera Ingest, instalados por ele, não precisam disso.

**3. Entre na sua conta.**
Clique no botão redondo da conta, no canto superior direito.
- **Já usa o Speed Batch:** entre com o mesmo e-mail e senha.
- **Conta nova:** clique em **Criar Conta**, preencha os dados e confirme pelo link enviado ao seu e-mail.
  Depois volte e clique em **Entrar**.

**4. Escolha o plano.**
Clique em **Instalar** em qualquer aplicativo. Sem plano ativo, abre a tela de planos: escolha **Mensal** ou
**Anual**, pague com **cartão de crédito** ou **PIX** e clique em **Assinar**. O pagamento abre no navegador;
ao terminar, volte e clique em **Já Paguei, Verificar**.

**5. Instale os aplicativos.**
Com o plano ativo, clique em **Instalar** no Speed Batch, no Smart Frame ou no Camera Ingest. O Tiger Media Tools
baixa, confere e instala na pasta Aplicativos. Depois é só clicar em **Abrir**.

---

## Atualizações

Quando sair uma versão nova, o aplicativo mostra **Atualizar** no Tiger Media Tools. Você pode atualizar na
hora ou continuar abrindo a versão instalada. Não é preciso voltar a esta página.

---

## Conta e assinatura

- A conta é feita só no Tiger Media Tools. Os três aplicativos usam a mesma conta e não pedem login.
- Cada aplicativo confere a licença ao abrir e de hora em hora. Sem internet, ele continua funcionando por até
  7 dias e mostra o aviso *"Não foi possível verificar sua conta"*.
- Na barra de menus de cada aplicativo ficam **Verificar Conta** e **Sair da Conta**. Sair de um sai de todos.
- Pagamento e cancelamento ficam no menu da conta do Tiger Media Tools: **Regularizar Pagamento** e
  **Cancelar Assinatura**.
- A conta é pessoal: pedimos que não seja compartilhada entre pessoas diferentes.

---

## Privacidade

- Os vídeos são processados **inteiramente no seu Mac**. Nada é enviado para a internet.
- Nome, e-mail e assinatura servem só para o login e o acesso aos aplicativos.
- O pagamento é feito por um provedor especializado. Os aplicativos nunca guardam os dados do seu cartão.

---

## Perguntas frequentes

**O macOS diz que o app está danificado. É vírus?**
Não. É o aviso padrão para apps sem o certificado pago da Apple. Siga o passo 2 de *Como instalar*.

**Funciona em Mac com chip Intel?**
Ainda não. Só em Macs com chip Apple Silicon (M1 ou mais novo).

**Preciso pagar cada aplicativo separado?**
Não. Um plano dá acesso aos três.

**Os meus vídeos originais são alterados?**
Nunca. Os aplicativos só leem os originais e salvam o resultado na pasta que você escolher.

**Posso usar sem internet?**
Sim, por até 7 dias seguidos. Depois disso, conecte para o app conferir sua conta.

**Como levo os arquivos do Camera Ingest para o Speed Batch ou o Smart Frame?**
No Speed Batch ou no Smart Frame, ative **Monitorar pasta** e aponte para a mesma pasta onde o Camera Ingest entrega.

---

## Suporte

Encontrou um problema, algo confuso ou tem uma sugestão? Fale com a equipe Tiger Media Tools pelo canal
combinado com você.

<sub>Este repositório guarda só os instaladores e o arquivo de atualizações, assinado pela Tiger. Não há código-fonte aqui.</sub>
