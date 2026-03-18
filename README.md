# Figma vs DevTools

🎨 QA + Figma
Guia prático para validação de layout com precisão

Este repositório foi criado para ajudar QAs a utilizarem o Figma como ferramenta principal na validação de interfaces, garantindo consistência visual, fidelidade ao design e redução de bugs em produção.

📌 Objetivo

Capacitar QAs a:

Validar telas com base no Figma

Identificar divergências visuais

Garantir consistência entre design e desenvolvimento

Melhorar a comunicação com designers e devs

🧠 Por que usar Figma no QA?

O Figma não é só uma ferramenta de design — ele é a fonte da verdade do layout.

Sem validação com base nele, você corre risco de:

Layout quebrado em produção

Espaçamentos inconsistentes

Cores e fontes incorretas

Experiência do usuário prejudicada

🛠️ O que validar no Figma
🎯 1. Estrutura geral

Hierarquia dos elementos

Organização dos blocos

Presença/ausência de componentes

📏 2. Espaçamentos

Margens (margin)

Espaçamento interno (padding)

Distância entre elementos

💡 Dica: use a tecla ALT (Option) no Figma para medir espaçamentos

🎨 3. Cores

Cor de fundo

Cor de texto

Botões e estados (hover, active, disabled)

🔤 4. Tipografia

Fonte (family)

Tamanho (font-size)

Peso (font-weight)

Altura de linha (line-height)

🧱 5. Componentes

Botões

Inputs

Cards

Modais

Verifique se estão seguindo o padrão do design system

📱 6. Responsividade

Desktop

Tablet

Mobile

⚠️ Sempre validar se o comportamento bate com o Figma (não só visual, mas adaptação)

🖼️ 7. Imagens e ícones

Tamanho correto

Qualidade

Posicionamento

Proporção

🔍 Como validar na prática
Passo a passo:

Acesse o Figma do projeto

Compare com o ambiente (dev/homolog/prod)

Use ferramentas como:

Inspecionar elemento (DevTools)

Extensões de comparação (ex: PerfectPixel)

Valide item por item

Documente divergências

🐞 Exemplo de bug (padrão QA)

Título: Divergência de espaçamento no botão CTA

Descrição:
O botão apresenta espaçamento inferior diferente do especificado no Figma.

Esperado:
Espaçamento de 24px conforme Figma

Atual:
Espaçamento de 16px

Evidência:
(Print do Figma + Print do site)

💬 Boas práticas

Sempre valide com o Figma aberto

Nunca confie “no olho”

Utilize zoom (100%, 125%, 150%)

Alinhe dúvidas com o designer

Evite suposições — valide tudo
