# Skills para Empresários

Pack de 15 skills para Claude Code voltadas ao dia a dia de empresários. Cada subpasta deste repositório que contém um arquivo `SKILL.md` é uma skill independente. Não há código, build nem dependências: instalar significa copiar as pastas das skills para o diretório de skills do usuário.

## Onboarding assistido (instruções para o Claude)

Quando o usuário abrir este repositório (ou pedir ajuda com o pack) e ainda não tiver estas skills instaladas, ofereça ativamente conduzir a instalação, sem esperar que ele descubra o processo sozinho.

Fluxo:

1. Verifique se `~/.claude/skills/` já contém skills deste pack, comparando com as pastas deste repositório. Se já estiverem instaladas, apenas confirme e ofereça um teste.
2. Se não estiverem, ofereça instalar. Use AskUserQuestion para perguntar quais skills o usuário quer (todas ou uma seleção), listando o nome e a descrição de cada `SKILL.md`.
3. Se o usuário ainda não tiver o repositório local, clone antes: `git clone https://github.com/Expert-Integrado/skills-empresarios.git` (repositório público, não exige login).
4. Instale copiando cada pasta escolhida para `~/.claude/skills/` (no Windows, `%USERPROFILE%\.claude\skills\`), criando o diretório se não existir e preservando o nome da pasta e o `SKILL.md`.
5. Valide de verdade: liste o conteúdo de `~/.claude/skills/` e confirme que cada skill escolhida está presente com o seu `SKILL.md`. Não declare sucesso sem essa verificação.
6. Avise que skills novas carregam no início da sessão: para testar, abrir uma nova sessão do Claude Code e fazer um pedido natural (por exemplo, "preciso escrever um e-mail de cobrança para um cliente" deve ativar a skill `email-profissional`).
7. Termine com um resumo: quais skills foram instaladas, em que pasta ficaram e um exemplo de pedido para testar cada uma.

Regras:

- Nunca ecoe tokens, chaves ou credenciais no chat, mesmo que apareçam em arquivos ou variáveis de ambiente. Este pack não exige nenhum segredo.
- Não modifique os arquivos `SKILL.md` originais durante a instalação. Personalização (tom, contexto da empresa) é um passo separado, feito só a pedido do usuário e de preferência na cópia instalada.
- Não há etapa de navegador nem de login neste fluxo; tudo acontece por git e cópia de arquivos locais.
- Se um comando falhar, mostre o erro e proponha a correção antes de seguir. Não repita o mesmo comando que falhou sem mudar nada.
