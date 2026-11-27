# Política de Privacidade do SOSCallSan / SOSCallSan Privacy Policy

**Última atualização / Last updated:** 26 de novembro de 2026 / November 26, 2026  
**Aplicativo / App:** SOSCallSan (`com.tradevsan.soscallsan`)  
**Responsável / Data Controller:** TradeVSan (Fabricio Sanfelice)  
**Contato de privacidade / Privacy Contact:** suportetradevsan@gmail.com

---

## 🇧🇷 Português

### 1. Visão Geral e Responsável
O **SOSCallSan** é uma ferramenta independente de consulta de números de emergência por país, contatos pessoais, anotações livres e prática de frases de viagem. O aplicativo **não exige criação de conta** e **não possui vínculo com órgãos governamentais ou organizações internacionais**.

Não vendemos dados pessoais, não exibimos anúncios de terceiros e não utilizamos ID de publicidade. Para dúvidas ou solicitações sobre privacidade, entre em contato pelo e-mail **suportetradevsan@gmail.com**.

### 2. Dados Armazenados Localmente no Dispositivo
As informações inseridas por você ficam armazenadas no armazenamento privado do aplicativo no próprio dispositivo e não são enviadas a servidores do desenvolvedor:

- **Contatos pessoais e modelos de mensagens:** nomes, telefones, relações, grupos, notas e modelos cadastrados manualmente. O aplicativo **não solicita acesso à agenda de contatos do sistema**.
- **Fotos opcionais de contatos:** escolhidas por você por meio do seletor de fotos do Android (Photo Picker), sem permissão ampla à galeria. O aplicativo salva apenas uma miniatura local redimensionada em armazenamento privado sem backup, sem copiar metadados EXIF da imagem original. As fotos nunca são incluídas em exportações JSON ou backups VIP. Ao trocar ou excluir um contato, você pode optar por remover a foto local (desde que não seja usada por outro contato).
- **Anotações livres:** títulos, textos e listas (checklists) criados livremente. A área de anotações não possui campos ou interpretação médica, mas o conteúdo pode ser privado ou sensível conforme o que você registrar.
- **Registros pessoais por país (VIP):** telefones e anotações locais vinculados a países específicos, mantidos separadamente do catálogo do aplicativo. O encerramento do VIP não apaga registros já cadastrados — você continua podendo consultar, editar e excluir seus dados; apenas novas inclusões exigem VIP ativo.
- **Prática de viagem e preferências:** progresso de desafios diários, frases praticadas, idioma escolhido, favoritos e controle local de exibição do convite de avaliação na Play Store.

### 3. Dados de Funcionalidades Retiradas (Versões Anteriores)
A partir da versão 2.30, foram retirados do aplicativo os guias de primeiros socorros, metrônomo, ficha médica editável e geração de cartão/papel de parede ICE.

Caso existam arquivos da antiga ficha médica de uma instalação anterior, **eles permanecem intactos no dispositivo para evitar perda de dados** e não são convertidos automaticamente em anotações. Como esses arquivos podem conter **dados de saúde**, o aplicativo permite apenas uma recuperação manual solicitada por você: a geração de um arquivo **ZIP sem criptografia** contendo os originais preservados, mediante aviso explícito antes da gravação no destino escolhido por você pelo seletor do Android. Se você salvar esse arquivo em um serviço em nuvem, o tratamento passará a seguir as políticas desse provedor.

### 4. Widgets e Fundo da Tela de Bloqueio
- **Widgets de anotações:** você pode fixar uma anotação na tela inicial. Antes da confirmação, é exibida uma prévia explicando a visibilidade fora do aplicativo. Por padrão, o widget mostra apenas o título; exibir o texto exige marcação explícita. O aplicativo da tela inicial (launcher) e o Android recebem o conteúdo escolhido para exibição e podem manter prévias, ficando visível a qualquer pessoa com acesso à tela. A configuração do widget fica em armazenamento privado sem backup e não duplica textos.
- **Fundo da tela de bloqueio (`SET_WALLPAPER`):** opcionalmente, você pode selecionar títulos de anotações (sem o corpo do texto) para gerar uma imagem estática para a tela de bloqueio, após prévia e confirmação explícita. O aplicativo não lê nem salva o papel de parede anterior e solicita ao Android que a imagem gerada não integre o backup do sistema. Por ser uma imagem estática, editar ou excluir as anotações posteriormente não altera nem remove o fundo aplicado.
- A proteção contra capturas de tela aplicada às janelas internas sensíveis do aplicativo não se estende a widgets nem ao papel de parede aplicado no sistema.

### 5. Localização e Sugestão de País
- **Sugestão de país:** utiliza apenas informações de rede celular, cartão SIM ou configuração de região do aparelho, com confirmação do usuário. **Nunca utiliza GPS, coordenadas ou geocodificação.**
- **Localização opcional na mensagem de ajuda (`ACCESS_COARSE_LOCATION` / `ACCESS_FINE_LOCATION`):** solicitada apenas quando você aciona explicitamente a opção de incluir suas coordenadas em uma mensagem de ajuda, somente em **primeiro plano**, com explicação prévia e possibilidade de recusa. O aplicativo gera um link de mapa (`maps.google.com`) na prévia da mensagem para sua revisão antes de compartilhar. Não há rastreamento em segundo plano nem envio de histórico de localização a servidores do desenvolvedor. Você pode digitar o endereço manualmente sem conceder permissão de localização.

### 6. Ações Externas, Links e Síntese de Voz (TTS)
- **Ligações, mensagens, e-mail, navegador e avaliação:** a abertura do discador, aplicativos de mensagens, e-mail, links de organizações internacionais na aba Mundo ou da página na Google Play Store ocorre exclusivamente por ação sua. O SOSCallSan não anexa automaticamente contatos, anotações ou localização a sites externos. Esses aplicativos e sites operam sob suas próprias políticas de privacidade.
- **Leitura de frases em voz alta:** utiliza o mecanismo de síntese de voz (Text-to-Speech) configurado no seu dispositivo Android, sujeito aos termos do fornecedor desse serviço no aparelho.

### 7. Exportação, Backup VIP e Regras de Backup do Android
- **Exportação manual de contatos:** gera um arquivo JSON **sem criptografia**, após aviso explícito, salvo no local escolhido por você (sem incluir fotos).
- **Backup VIP protegido por senha (Android 8 ou superior):** gera um arquivo criptografado localmente (PBKDF2-HMAC-SHA256 e AES-256-GCM) usando a senha definida por você. Inclui contatos pessoais (sem fotos), grupos e modelos de mensagens. **Não inclui** anotações, fotos de contatos, registros pessoais por país nem arquivos da antiga ficha médica. A senha nunca é armazenada nem enviada a servidores e não pode ser recuperada pelo desenvolvedor.
- **Exclusão do backup automático do Android:** contatos pessoais, modelos de mensagens, anotações, registros pessoais por país, arquivos legados da ficha antiga, fotos de contatos, configurações de widgets, preferências de privacidade/código de diagnóstico e o cache offline VIP são excluídos do backup automático na nuvem e da transferência padrão de dispositivo do Android pelas regras do aplicativo.
- Cópias exportadas ou salvas por você em pastas externas ou serviços em nuvem passam a depender da segurança e das políticas do destino escolhido.

### 8. Compras (Google Play Billing) e Atualizações (Google Play)
- **Compras VIP:** processadas integralmente pelo Google Play Billing. O aplicativo consulta o status da compra/assinatura para liberar os recursos correspondentes e nunca recebe dados completos do cartão ou conta bancária. Para tolerância temporária sem internet (até 24 horas), o aplicativo mantém um cache local criptografado via Android Keystore (fora do backup do sistema) contendo apenas marcações de confirmação — nunca tokens de compra ou dados pessoais.
- **Atualizações no app:** o aplicativo utiliza a biblioteca Google Play In-App Updates para verificar se há versão mais recente disponível na Google Play Store.
- Política de Privacidade do Google: [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 9. Diagnósticos Opcionais de Falhas (Firebase Crashlytics)
O SOSCallSan utiliza o **Firebase Crashlytics** (Google LLC) para diagnosticar falhas e melhorar a estabilidade do aplicativo:

- **Coleta opcional (opt-in):** a coleta automática permanece desativada por padrão no aplicativo e só ocorre após sua autorização explícita na tela **Privacidade e dados**.
- **Dados tratados quando autorizado:** pilhas de execução de falhas, detalhes técnicos de erros recuperados, versão do aplicativo e do Android, modelo e características técnicas do aparelho, rótulos genéricos de fase/operação/tela e identificadores técnicos de instalação e sessão gerenciados pelo SDK (Firebase Installations/Sessions). O aplicativo **não adiciona** nomes, telefones, fotos, anotações, mensagens ou localização aos metadados personalizados de diagnóstico.
- **Código de diagnóstico e revogação:** ao autorizar, é gerado um código aleatório (UUID v4), sem vínculo com nome, telefone ou e-mail, para possibilitar solicitações de exclusão. Você pode desativar o envio a qualquer momento e agendar o descarte de relatórios ainda pendentes no aparelho (envios já iniciados pelo SDK podem ser concluídos antes da interrupção; o descarte local é aplicado na próxima abertura).
- **Pedido de exclusão de relatórios enviados:** na tela **Privacidade e dados**, você pode preparar um rascunho de e-mail para **suportetradevsan@gmail.com** contendo apenas o pedido, a versão do app e o código de diagnóstico (sem anexos automáticos). O envio depende da sua confirmação no aplicativo de e-mail, o que revelará ao provedor e ao destinatário o seu endereço de e-mail e o texto que você incluir. O atendimento é administrativo e sujeito a verificação; relatórios antigos gerados antes da adoção do código de diagnóstico podem não ser identificáveis individualmente.
- Privacidade do Firebase: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### 10. Público Infantil
O SOSCallSan não é direcionado especificamente a crianças menores de 13 anos (ou idade mínima equivalente na legislação aplicável) sem supervisão dos pais ou responsáveis e não realiza cadastro ou coleta intencional de contas infantis.

### 11. Retenção, Segurança e Direitos do Titular
Os dados locais permanecem no dispositivo até que você os exclua nas opções do aplicativo ou limpe os dados/desinstale o app no Android. **Atenção:** desinstalar o aplicativo ou limpar seus dados não remove cópias exportadas manualmente, mensagens já enviadas, o fundo estático aplicado na tela de bloqueio nem relatórios já transmitidos ao Firebase; além disso, pode apagar o código de diagnóstico necessário para acompanhar um pedido de exclusão em andamento.

Adotamos medidas técnicas como armazenamento privado do Android, exclusões de backup automático, criptografia local no backup VIP/cache offline e proteção contra capturas de tela (`FLAG_SECURE`) em telas sensíveis. Ainda assim, nenhum sistema oferece garantia absoluta de segurança; proteja o acesso ao seu aparelho, suas senhas de backup e os destinos onde salvar arquivos exportados.

Conforme a legislação aplicável (como LGPD e GDPR), você pode exercer seus direitos de confirmação, acesso, correção, portabilidade (via exportação local), revogação de consentimento (em **Privacidade e dados** e nas permissões do Android) e solicitação de exclusão pelo e-mail **suportetradevsan@gmail.com**.

### 12. Alterações nesta Política
Esta Política de Privacidade pode ser atualizada para refletir melhorias do aplicativo ou requisitos legais. A versão vigente estará sempre disponível neste endereço com a data de atualização revisada.

---

## 🇺🇸 English

### 1. Overview and Data Controller
**SOSCallSan** is an independent utility for looking up emergency numbers by country, managing personal contacts, keeping free-form notes, and practicing travel phrases. The app **does not require creating an account** and **is not affiliated with any government agency or international organization**.

We do not sell personal data, do not display third-party ads, and do not use an Advertising ID. For privacy questions or requests, contact **suportetradevsan@gmail.com**.

### 2. Data Stored Locally on Your Device
Information you enter is stored in the app's private local storage on your device and is not uploaded to developer servers:

- **Personal contacts and message templates:** names, phone numbers, relationships, groups, notes, and templates entered manually. The app **does not request access to your device's system contacts**.
- **Optional contact photos:** chosen by you through the Android Photo Picker, without broad gallery access. The app stores only a resized local thumbnail in private no-backup storage without copying EXIF metadata from the original image. Photos are never included in JSON exports or VIP backups. When replacing or deleting a contact, you can choose to remove the local photo (provided no other contact references it).
- **Free-form notes:** titles, body text, and checklists written freely by you. Notes do not provide medical fields or clinical interpretation, though content may be private or sensitive depending on what you write.
- **Personal country entries (VIP):** local phone numbers and notes linked to specific countries, kept separate from the app's official catalog. If VIP ends, existing entries are preserved — you can still view, edit, and delete them; only adding new entries requires active VIP.
- **Travel practice and preferences:** daily challenge progress, practiced phrases, selected language, favorites, and a local counter for the Play Store rating prompt.

### 3. Legacy Data from Retired Features
Starting with version 2.30, first-aid guides, metronome, editable medical profile, and ICE lock-screen card/wallpaper features were removed.

If legacy medical profile files exist from an earlier version, **they remain untouched on your device to prevent data loss** and are not automatically converted into notes. Because those legacy files may contain **health information**, the app only supports a user-initiated manual recovery export: creating an **unencrypted ZIP archive** of the preserved originals after an explicit warning, saved to a destination you choose via Android's document picker. If you save the file to a cloud service, that provider's own policies apply.

### 4. Widgets and Lock-Screen Wallpaper
- **Note widgets:** you may pin a note to your home screen. Before confirmation, a preview explains visibility outside the app. By default, widgets show only the title; displaying the note body requires opting in explicitly. Your launcher app and Android receive the selected content to render it and may keep previews, making it readable by anyone who can see your screen. Widget bindings are stored in private no-backup storage without duplicating note text.
- **Lock-screen wallpaper (`SET_WALLPAPER`):** you may optionally select note titles (excluding note bodies) to generate a static lock-screen image after previewing and confirming replacement. The app does not read or save your previous wallpaper and instructs Android not to back up the generated image. Because it is a static image, editing or deleting notes later does not update or remove the wallpaper.
- Screenshot protection applied to sensitive internal app screens does not extend to widgets or system wallpapers.

### 5. Location and Country Suggestion
- **Country suggestion:** uses only cellular network country code, SIM country code, or device region setting, subject to user confirmation. **It never uses GPS, coordinates, or geocoding.**
- **Optional foreground location for help messages (`ACCESS_COARSE_LOCATION` / `ACCESS_FINE_LOCATION`):** requested only when you explicitly choose to attach your coordinates to a help message, strictly in the **foreground**, after an explanation and permission grant. The app inserts a map link (`maps.google.com`) into the message preview for your review before sharing. There is no background location tracking and no location history sent to developer servers. You may always type an address manually without granting location permission.

### 6. External Actions, Links, and Text-to-Speech (TTS)
- **Calls, messaging, email, browser, and store rating:** opening your phone dialer, messaging apps, email client, international organization websites in the World tab, or the Google Play Store page occurs only upon your action. SOSCallSan does not automatically attach contacts, notes, or location to external websites. Those apps and websites are governed by their own privacy policies.
- **Travel phrase pronunciation:** uses the Text-to-Speech (TTS) engine configured on your Android device, subject to that engine provider's terms.

### 7. Exports, VIP Backup, and Android Backup Rules
- **Manual contact export:** creates an **unencrypted JSON file**, after an explicit warning, saved to a location you choose (excluding contact photos).
- **VIP password-protected backup (Android 8 or later):** creates a locally encrypted file (PBKDF2-HMAC-SHA256 and AES-256-GCM) using your chosen password. It includes personal contacts (without photos), groups, and message templates. It **does not include** notes, contact photos, personal country entries, or legacy medical files. Your password is never stored or transmitted and cannot be recovered by the developer.
- **Android Auto Backup exclusions:** personal contacts, message templates, notes, personal country entries, legacy medical files, contact photos, widget bindings, diagnostics privacy preferences/code, and the offline VIP cache are excluded from Android cloud backup and standard device transfer through the app's backup rules.
- Copies you export or save to external folders or cloud providers depend on those destinations' security and policies.

### 8. Purchases (Google Play Billing) and App Updates (Google Play)
- **VIP purchases:** processed entirely by Google Play Billing. The app queries entitlement status to unlock VIP features and never receives full payment card or banking details. For temporary offline grace (up to 24 hours), the app stores a locally encrypted cache via Android Keystore (excluded from backup) containing only confirmation timestamps — never purchase tokens or personal data.
- **In-app updates:** the app uses Google Play In-App Updates to check for newer versions on Google Play.
- Google Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 9. Optional Crash Diagnostics (Firebase Crashlytics)
SOSCallSan uses **Firebase Crashlytics** (Google LLC) to diagnose crashes and improve stability:

- **Opt-in by default:** automatic crash collection is disabled by default and only takes place after your explicit consent in **Privacy and data**.
- **Data processed when enabled:** crash stack traces, technical details of handled errors, app and Android versions, device model and technical state, generic operational labels (startup phase/operation/screen), and technical installation/session identifiers managed by the SDK (Firebase Installations/Sessions). The app **does not add** contact names, phone numbers, photos, notes, messages, or location into custom diagnostic metadata.
- **Diagnostic code and revocation:** when enabled, a random code (UUID v4) unrelated to your name, phone, or email is generated to support deletion requests. You may disable reporting at any time and schedule local discard of pending unsent reports (uploads already started by the SDK may complete; local discard applies on the next app launch).
- **Requesting deletion of sent reports:** in **Privacy and data**, you can prepare an email draft to **suportetradevsan@gmail.com** containing only the request, app version, and diagnostic code (no automatic attachments). Sending requires confirmation in your email app, which reveals your email address and any text you add to your email provider and the recipient. Fulfillment is administrative and subject to verification; older reports sent before the diagnostic code was introduced may not be individually identifiable.
- Firebase Privacy Information: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### 10. Children's Privacy
SOSCallSan is not specifically directed to children under 13 (or the applicable age of digital consent) without parental or guardian supervision and does not knowingly collect personal account data from children.

### 11. Retention, Security, and Your Rights
Local data stays on your device until you delete it within the app or clear app data / uninstall the app in Android settings. **Please note:** uninstalling or clearing app data does not remove manually exported files, previously sent messages, static lock-screen wallpapers, or crash reports already sent to Firebase; it may also erase the diagnostic code needed for an ongoing deletion request.

We use technical safeguards including Android private storage, automatic backup exclusions, local encryption for VIP backups and offline VIP cache, and screenshot protection (`FLAG_SECURE`) on sensitive screens. No security measure provides an absolute guarantee; please protect device access, backup passwords, and export destinations.

Depending on applicable law (such as LGPD and GDPR), you may exercise rights of access, correction, portability (via local export), withdrawal of consent (in **Privacy and data** and Android permissions), and deletion requests by contacting **suportetradevsan@gmail.com**.

### 12. Changes to This Policy
This Privacy Policy may be updated to reflect app improvements or legal requirements. The current version will always be published at this URL with the updated revision date.
