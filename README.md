# impactaMeet
Comandos git a fins didáticos para a equipe de alunos ao qual participo da faculdade Impacta.

## Introdução aos Comandos Básicos do Git

Git é um sistema de controle de versão amplamente utilizado por desenvolvedores para gerenciar o histórico de alterações no código-fonte de seus projetos. Ele permite que você acompanhe e reverta mudanças, colabore com outros desenvolvedores, e mantenha o código organizado ao longo do tempo.

Nesta seção, você encontrará uma explicação dos principais comandos básicos do Git. Eles são essenciais para iniciar o trabalho com Git e GitHub, facilitando o gerenciamento de versões e a colaboração em projetos. Vamos explorar o que cada comando faz e como utilizá-los de forma prática no dia a dia.

## Comandos e explicações

1. **`git init`**: Caso seja sua primeira vez utilizando o projeto, este comando irá inicializar um repositório Git local, permitindo que você use os comandos Git a seguir.

2. **`git remote add origin`**: Esse comando é usado para conectar o repositório local a um repositório remoto (como no GitHub). No exemplo dado, ele conecta o repositório local ao repositório no GitHub com o link especificado.

3. **Exemplo:** `git remote add origin https://github.com/BredexBR/impactaMeet.git`
   - Esse comando está adicionando o repositório remoto chamado "origin", que aponta para o endereço do repositório no GitHub.

4. **`git remote -v`**: Mostra a lista de repositórios remotos associados ao seu repositório local, junto com as URLs. É útil para confirmar que o repositório remoto foi adicionado corretamente.

5. **`git add .`**: Adiciona todas as mudanças feitas nos arquivos (novos ou modificados), preparando-os para serem incluídos no próximo commit.

6. **`git commit -m "Deixe a mensagem do que voce fez aqui"`**: Salva as mudanças adicionadas com uma mensagem que descreve o que foi feito. A mensagem deve ser curta e clara, sem acentos, cedilha, ou caracteres especiais.

7. **Caso seja seu primeiro commit:** Se você nunca fez um commit antes, Git pode pedir para você configurar seu nome de usuário e e-mail, que serão usados para identificar quem fez o commit.

   - **`git config --global user.name "Seu nome"`**: Configura seu nome globalmente para todos os commits futuros.
   
   - **`git config --global user.email "seuEmail@exemplo.com"`**: Configura seu e-mail globalmente para todos os commits futuros.

8. **`git push -u origin main`**: Envia (faz o "push") as mudanças confirmadas localmente para o repositório remoto no GitHub. O `-u` define a branch remota como padrão para futuros pushes, então você só precisará usar `git push` nas próximas vezes.



