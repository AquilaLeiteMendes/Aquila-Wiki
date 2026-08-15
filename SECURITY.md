# Política de Segurança

## Comunicação de vulnerabilidades

Se você encontrar uma vulnerabilidade de segurança no **Aquila-Wiki**, pedimos que não abra uma issue pública para relatá-la.

Relatos de segurança devem ser tratados de forma privada para reduzir o risco de exploração antes que uma correção esteja disponível.

Para comunicar uma vulnerabilidade, utilize os canais privados disponíveis no perfil ou no repositório do projeto no GitHub.

Ao fazer um relatório, procure incluir:

* descrição clara da vulnerabilidade;
* arquivos, componentes ou funcionalidades afetados;
* passos necessários para reproduzir o problema;
* impacto potencial;
* evidências técnicas relevantes;
* uma possível sugestão de correção, quando disponível.

Quanto mais informações forem fornecidas, mais fácil será reproduzir, avaliar e corrigir o problema.

## Escopo

Esta política se aplica ao código, aos arquivos de configuração e aos demais componentes mantidos neste repositório.

Problemas relacionados exclusivamente a serviços externos, plataformas de terceiros ou à infraestrutura que não seja controlada pelo projeto devem ser comunicados aos respectivos responsáveis.

## Credenciais e informações sensíveis

Nunca inclua em issues, pull requests, commits ou outros conteúdos públicos:

* senhas;
* tokens de autenticação;
* chaves de API;
* credenciais de acesso;
* cookies de sessão;
* chaves privadas;
* arquivos `.env` contendo informações sensíveis;
* informações pessoais que não sejam necessárias ao desenvolvimento.

Credenciais expostas acidentalmente devem ser consideradas comprometidas. Sempre que possível, revogue ou substitua imediatamente a credencial afetada.

O arquivo `.gitignore` do projeto contém regras destinadas a evitar o versionamento acidental de determinados arquivos locais e informações sensíveis. Ainda assim, **o `.gitignore` não substitui procedimentos adequados de segurança**.

## Divulgação responsável

Solicitamos que vulnerabilidades sejam comunicadas de maneira responsável e que seja concedido tempo razoável para investigação e correção antes de qualquer divulgação pública.

Após a correção, informações sobre a vulnerabilidade poderão ser divulgadas de forma responsável, preservando dados sensíveis e evitando detalhes que possam facilitar novos ataques.

## Atualizações desta política

Esta política poderá ser atualizada conforme o projeto evoluir, especialmente quando novos componentes, serviços ou mecanismos de segurança forem incorporados ao Aquila-Wiki.
