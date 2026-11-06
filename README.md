# 📝 Preenchedor de Vagas

> Uma extensão inteligente para o Google Chrome que acelera e simplifica o preenchimento de formulários de vagas de emprego. Você no controle dos seus dados, preenchendo apenas o que quiser, com um único clique.

---

## 🚀 Como Instalar

Como a extensão ainda não está na Chrome Web Store, a instalação é feita manualmente (Modo Desenvolvedor). Siga os passos:

1. **Descompacte** o arquivo baixado em uma pasta de fácil acesso no seu computador.
2. Abra o seu navegador e acesse: `chrome://extensions`
3. No canto superior direito da tela, ative a chave **Modo do desenvolvedor**.
4. Clique no botão **Carregar sem compactação** (no canto superior esquerdo).
5. Selecione a pasta `preenchedor-vagas` que você descompactou.
6. *Pronto! A extensão já está instalada e o ícone aparecerá na sua barra de extensões.*

---

## ⚙️ Como Funciona

A extensão foi pensada para ser não-intrusiva. Nada é preenchido sem a sua autorização.

* 🔍 **Detecção Inteligente:** Em páginas que contêm formulários, um painel flutuante aparecerá discretamente no canto inferior direito. O sistema vasculha a página e faz o pareamento de cada campo (analisando *rótulo, placeholder, autocomplete, name e id*) com os dados que você já tem salvos.
* ✨ **Sugestão e Preenchimento:** Os campos reconhecidos pela extensão aparecem na aba **“Prontos para preencher”**. Você pode desmarcar qualquer item que não deseje enviar naquela vaga específica. Clicou em **Preencher**? O trabalho está feito.
* ➕ **Mapeamento de Campos Novos:** Encontrou um campo desconhecido? Ele vai para a aba **“Campos novos”**.
* Você pode atrelar a ele um dado já salvo ou criar um **Novo dado**.
* Digite o valor, clique em **Salvar e preencher** e pronto: na próxima vez, a extensão já reconhecerá esse campo automaticamente.
* *Dica:* Se você digitar o valor diretamente no campo da página, o painel já puxa esse texto, deixando tudo no jeito para salvar.


* 📦 **Dados Prontos (Templates):** A extensão já vem com um esqueleto dos campos mais comuns no mundo corporativo (nome, e-mail, telefone, CPF, endereço, LinkedIn, pretensão salarial, *“por que quer trabalhar aqui?”*, etc.). Basta você abrir o popup, preencher os valores com as suas informações e usar.

---

## 🎛️ Ligar e Desligar

Se o formulário for complexo demais ou você não quiser usar a extensão em um site específico, o controle está a um clique (ou atalho) de distância:

* **Interruptor Geral:** Disponível no popup da extensão. Quando desligado, o ícone do Chrome mostrará uma badge **OFF**.
* **Interruptor por Site:** Uma chave **"Neste site"** no popup permite bloquear a extensão apenas no domínio atual.
* **Atalho Rápido:** Pressione `Alt + Shift + F` para ligar/desligar instantaneamente.
* **Ações no próprio Painel:** No balão flutuante da página, você tem botões rápidos de **Desligar neste site** e **Desligar tudo** (conta com a opção de **Desfazer** caso clique sem querer).

---

## 💾 Backup e Segurança

A extensão não envia seus dados para nenhum servidor; fica tudo no seu navegador.

Para não perder suas informações (ou para transferir para outro computador), abra o popup da extensão e utilize as ferramentas de **Exportar** e **Importar** para gerar um arquivo `.json` com o seu backup atualizado.
