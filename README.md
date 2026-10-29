# Mídias — @linomatias.idosos

Repositório público reservado para futuras mídias finais do projeto editorial voltado a profissionais de Educação Física que trabalham com pessoas idosas. O código principal, a revisão científica, os manifestos de aprovação e os registros de publicação permanecem no repositório privado `agentes-instagram-idosos`.

## Política de disponibilização

- Rascunhos, fixtures e mídias sem aprovação verificável não devem ser versionados nem enviados como artefatos neste repositório público.
- Uma mídia futura só poderá ser disponibilizada por um fluxo autorizado que confira a aprovação do pacote exato, sua integridade e a política central do repositório privado. A presença de uma imagem aqui não constitui aprovação científica nem autorização de postagem.
- Não armazenar tokens, credenciais, dados pessoais, relatórios internos ou manifestos privados.
- Não há agendamento ou publicação de produção neste repositório. O workflow de layout não acessa Meta, Cloudinary ou secrets e não faz commit, push ou upload de mídia.

## Teste de layout

O workflow `story-teste.yml` renderiza uma fixture sintética PNG RGB de 1080×1920, sem afirmações científicas, no diretório temporário do runner. Confere formato, dimensões e integridade, remove a fixture e escreve somente um resumo textual. Um resultado verde comprova esse teste de renderização; não comprova validação científica, hospedagem de conteúdo ou publicação no Instagram.

## Mídia legada

A alteração proposta remove `stories/teste-equilibrio.png`, que não possuía aprovação auditável, da árvore da branch. A remoção só alcançará `main` após o merge do pull request. Ela não apaga o histórico Git, versões anteriores, URLs históricas, caches ou cópias já obtidas. A retirada do histórico ou de cópias externas exige uma decisão e um procedimento próprios.
