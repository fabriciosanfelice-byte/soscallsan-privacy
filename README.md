# Política de Privacidade — SOSCallSan

**Última atualização:** 22 de outubro de 2026

O **SOSCallSan** tem como compromisso respeitar e proteger a privacidade dos seus usuários. Esta Política de Privacidade explica de forma clara como as informações são tratadas ao utilizar nosso aplicativo.

---

## 1. Relatórios Técnicos de Falhas (Firebase Crashlytics)

O SOSCallSan utiliza o **Firebase Crashlytics**, um serviço fornecido pela Google LLC, para identificar falhas técnicas, investigar travamentos e melhorar a estabilidade e a qualidade do aplicativo.

* **Coleta Automática de Diagnósticos:** Na versão distribuída aos usuários, a coleta de relatórios de falhas técnicas é automática. Esses relatórios incluem o tipo e a mensagem da exceção, a sequência de chamadas de código (*stack traces*), a versão do aplicativo, informações técnicas do dispositivo e do sistema operacional (como modelo e versão do Android), dados de sessão e identificadores técnicos de instalação (providos pelas dependências *Firebase Installations* e *Firebase Sessions*).
* **Metadados de Uso:** Para ajudar a localizar a origem do erro, registram-se apenas nomes fixos da tela em uso e da etapa de execução do aplicativo.
* **Isenção de Dados Pessoais:** Os metadados personalizados do Crashlytics **não incluem** nomes, telefones ou notas de contatos pessoais, mensagens de texto digitadas, consultas de busca, país selecionado ou coordenadas de localização geográfica. O aplicativo não define nenhum identificador de usuário baseado em nome, e-mail ou telefone para o Crashlytics.
* **Transmissão e Retenção de Dados:** Os dados técnicos são transmitidos ao Firebase por conexão criptografada via HTTPS. Conforme a documentação oficial do Firebase, o Crashlytics mantém os rastreamentos de falha e os identificadores técnicos associados por **90 dias** antes de iniciar o processo de remoção dos sistemas ativos e de backup.
* **Analytics:** O SDK do Google Analytics **não** está incluído nesta versão do aplicativo.
* **Mais informações:** Para saber mais sobre como o Google gerencia dados técnicos, consulte a página [Privacidade e segurança no Firebase](https://firebase.google.com/support/privacy).

---

## 2. Localização Opcional e Serviço de Geocodificação do Android

O aplicativo pode solicitar acesso à sua localização aproximada ou precisa **apenas** para sugerir o país onde você se encontra e exibir os números de emergência locais adequados.

* **Serviço de Geocodificação do Sistema (`android.location.Geocoder`):** Para converter coordenadas geográficas (latitude e longitude) no código ISO do país (ex: "BR", "US"), o aplicativo utiliza o serviço de geocodificação nativo do sistema operacional Android. Esse serviço do sistema operacional pode realizar consultas externas protegidas por HTTPS via serviços do sistema (como o Google Play Services) para interpretar o país.
* **Processamento Local e Sem Rastreamento:** O SOSCallSan **não salva histórico de localização, não rastreia seus deslocamentos e não envia coordenadas de localização a nenhum servidor próprio nem aos relatórios de falha do Crashlytics**.

---

## 3. Armazenamento Local de Contatos e Preferências

* **Agenda Pessoal de Emergência:** Todos os dados de contatos de emergência cadastrados por você (nomes, telefones, categorias e notas) e suas preferências de idioma ficam armazenados **exclusivamente na memória interna do seu próprio dispositivo** (`SharedPreferences`).
* **Sem Servidores Próprios:** Não enviamos, armazenamos nem processamos seus contatos em servidores externos do desenvolvedor.
* **Backup do Sistema Android:** Caso o recurso de backup automático do Android esteja ativado no seu dispositivo, as preferências locais do aplicativo poderão fazer parte do backup gerenciado pela sua conta Google na nuvem do sistema operacional.

---

## 4. Comunicação e Links Externos por Ação do Usuário

O aplicativo permite acionar canais oficiais de emergência (ligações telefônicas, WhatsApp, Telegram, e-mail, SMS ou sites governamentais). 
* Qualquer envio de mensagem, chamada ou navegação para site externo **depende exclusivamente de ação direta e confirmação consciente do usuário**.
* O aplicativo não realiza chamadas ou envios de mensagens de forma oculta ou automática.

---

## 5. Direitos do Usuário e Exclusão de Dados

Como seus contatos e preferências são armazenados localmente no seu dispositivo:
* **Alteração e Exclusão:** Você pode criar, editar ou excluir seus contatos de emergência salvos a qualquer momento pela interface do aplicativo.
* **Remoção Completa:** Ao desinstalar o aplicativo do seu dispositivo, todos os dados mantidos localmente serão apagados.

---

## 6. Alterações nesta Política de Privacidade

Esta Política de Privacidade pode ser atualizada periodicamente para refletir melhorias no aplicativo ou mudanças em exigências regulatórias. Recomendamos a consulta desta página regularmente.

---

## 7. Contato e Responsável pelo Aplicativo

Se você tiver dúvidas ou solicitações sobre esta Política de Privacidade, entre em contato com o desenvolvedor responsável:

* **Aplicativo:** SOSCallSan
* **Desenvolvedor / Responsável:** Fabricio Vieira Sanfelice
* **E-mail de Contato:** suportetradevsan@gmail.com
