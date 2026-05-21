---
layout: default
title: Política de Privacidade e Direitos Autorais
---

[Português](./privacy-policy-pt.html) | [English](./privacy-policy-en.html) | [Español](./privacy-policy-es.html)


# Política de Privacidade e Termos de Direitos Autorais - Stealth Notes

**Última atualização:** 21 de Maio de 2026

**Website:** [https://andrec84j.github.io/](https://andrec84j.github.io/)

O **Stealth Notes** ("nós", "nosso" ou "aplicativo") é um software utilitário de anotações ultrassecretas, capturas de tela seguras, gravação de vídeo, gerenciamento de documentos e senhas, desenvolvido com foco absoluto em privacidade e armazenamento local-first. Esta Política de Privacidade e Termos de Direitos Autorais descreve como lidamos com seus dados e os termos sob os quais o software é licenciado.

---

## PARTE 1 - POLÍTICA DE PRIVACIDADE

### 1. Coleta e Armazenamento de Dados

#### 1.1 Arquitetura Local-First (Cofre Criptografado)
O Stealth Notes é um aplicativo **100% Local-First**. Isso significa que:
*   Todas as notas comuns, notas flutuantes (Post-its), capturas de tela, gravações de vídeo, documentos importados e senhas gerenciadas são salvos e armazenados **exclusivamente no seu próprio dispositivo**.
*   Para garantir a segurança máxima, todas as suas informações confidenciais são salvas dentro de um cofre local seguro criptografado (`vault.enc`).
*   **Não enviamos** seus arquivos, mídias, textos ou senhas para nossos servidores. Nós não possuímos servidores de nuvem para armazenar seus dados pessoais.
*   **Ausência de Telemetria:** O aplicativo não coleta, rastreia ou envia telemetria, dados analíticos ou logs de utilização para os desenvolvedores. Tudo é processado localmente.

#### 1.2 Recursos de IA (Inteligência Artificial) e OCR
Para oferecer recursos de alta tecnologia, como reconhecimento de texto e assistência por IA:
*   **OCR (Reconhecimento Óptico de Caracteres):** É realizado localmente no seu dispositivo utilizando APIs nativas do Windows. Suas imagens de captura de tela não são enviadas para a internet para fins de processamento OCR.
*   **Serviços de IA Opcionais:** O aplicativo permite a integração com APIs de Inteligência Artificial (OpenAI, Google Gemini, Anthropic Claude) para ajudar a redigir, resumir ou traduzir anotações.
*   **Chaves de API do Usuário:** O uso de IA é totalmente opcional e requer que você insira suas próprias chaves de API (tokens). Estas chaves são armazenadas localmente no seu computador de forma segura e criptografada.
*   **Tráfego de Dados de IA:** Quando você aciona um recurso de IA, apenas os dados e textos estritamente necessários para aquela solicitação específica são enviados diretamente do seu computador para o provedor de IA escolhido. Nenhums dado passa por intermediários ou servidores do desenvolvedor do Stealth Notes. O uso de tais chaves e dados é regido pelas políticas de privacidade de seus respectivos provedores.

---

### 2. Permissões do Dispositivo

O Stealth Notes necessita das seguintes permissões do sistema para realizar suas tarefas:
*   **Captura e Gravação de Tela:** Necessária para tirar printscreens da área de trabalho e realizar gravações de vídeo quando solicitado por você.
*   **Gravação de Áudio/Microfone (Opcional):** Necessário apenas se você desejar incluir áudio do microfone em suas gravações de vídeo locais.
*   **Execução na Inicialização (Startup):** Permite que o aplicativo seja opcionalmente iniciado junto com o Windows para conveniência. Esta opção pode ser ativada ou desativada facilmente no menu do ícone da bandeja do sistema (System Tray) ou nas configurações do app.
*   **Acesso ao Sistema de Arquivos:** Utilizado para ler e gravar suas mídias exportadas, arquivos de configuração e o arquivo do cofre criptografado.

---

### 3. Modo Stealth (Proteção contra Captura de Janela)
O aplicativo implementa o **Modo Stealth**, que utiliza APIs de baixo nível do Windows para ocultar as janelas do Stealth Notes e Post-its flutuantes de capturas de tela ou gravações externas executadas por outros softwares. Isso impede que terceiros bisbilhotem ou gravem de forma não intencional as suas notas confidenciais enquanto você compartilha sua tela.

---

### 4. Compartilhamento de Dados com Terceiros
Como o aplicativo opera inteiramente de forma local, **nós não vendemos, alugamos, compartilhamos ou divulgamos** nenhuma informação pessoal sua. Você tem controle absoluto e exclusivo sobre suas chaves de segurança e mídias geradas.

---

## PARTE 2 - DIREITOS AUTORAIS E LICENCIAMENTO

### 5. Propriedade Intelectual e Direitos Autorais
Todo o código-fonte, elementos visuais, ícones, marca e design do **Stealth Notes** são de propriedade exclusiva do desenvolvedor.
*   **Copyright © 2026 André CJ. Todos os direitos reservados.**
*   É terminantemente proibido descompilar, fazer engenharia reversa, redistribuir, modificar ou sublicenciar o software sem a autorização prévia por escrito do detentor dos direitos autorais.

---

### 6. Modelo de Licença Freemium e Compras In-App

O Stealth Notes é distribuído sob um modelo **Freemium** por meio da Microsoft Store:
*   **Versão Gratuita (Limites de Criação):** O uso básico do aplicativo é gratuito e desbloqueia todas as ferramentas, mas limita a quantidade de itens que você pode manter criados:
    *   Capturas de Tela: limite de **5** itens
    *   Documentos: limite de **3** itens
    *   Gravações de Vídeo: limite de **3** itens
    *   Notas Comuns: limite de **5** itens
    *   Notas Flutuantes (Post-its): limite de **3** itens
    *   Senhas: limite de **5** itens
*   **Desbloqueio Premium:** O usuário poderá remover permanentemente todos os limites de quantidade realizando uma compra única in-app (Upgrade Premium) processada com total segurança diretamente pela Microsoft Store.

---

### 7. Isenção de Responsabilidade (Disclaimer)
O software é fornecido "no estado em que se encontra" (as is), sem garantias de qualquer tipo, expressas ou implícitas.
*   **Responsabilidade sobre a Senha Master:** Como não mantemos nenhum servidor de recuperação de chaves, **a guarda e lembrança da Senha Master e da Chave de Recuperação do cofre criptografado são de inteira e exclusiva responsabilidade do usuário**. Se você esquecer sua senha master ou perder sua chave de recuperação, será tecnicamente impossível recuperar os dados contidos no cofre.
*   O desenvolvedor não se responsabiliza por perdas de dados ocorridas por falhas de hardware, exclusões acidentais de arquivos ou perda de chaves de acesso.

---

### 8. Contato e Suporte
Para relatar problemas, buscar suporte ou esclarecer dúvidas, visite a página oficial do desenvolvedor em [https://andrec84j.github.io/](https://andrec84j.github.io/) ou utilize os canais oficiais fornecidos na Microsoft Store.
