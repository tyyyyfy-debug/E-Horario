# E-horario — correção do leitor de planeamentos

Esta versão altera a deteção das cinco colunas: em vez de cortar a página em cinco partes iguais, calcula os limites a partir das posições reais dos códigos de obra no PDF. Isto evita que nomes/equipas que ficam perto da margem entre dias sejam atribuídos à coluna seguinte.

## Carregar pelo GitHub no telemóvel
Coloca `codemagic.yaml` e `project.zip` na raiz do repositório. Depois inicia um novo build no Codemagic.

A compilação ainda tem de ser validada pelo Codemagic; este pacote não é um APK já compilado.
