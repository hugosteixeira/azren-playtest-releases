# Azren's Legend — Playtest Windows

Repositorio publico apenas para instaladores e pacotes assinados. O codigo-fonte permanece privado.

Baixe o instalador `.exe` da release mais recente. O launcher instala e atualiza o cliente, verifica assinaturas e hashes e conecta ao servidor do playtest. Windows 10/11 x64; WebView2 pode ser instalado durante o setup.

Nao baixe o ZIP manualmente: ele e usado pelo launcher. `manifest.json`, `channel.json`, `launcher-latest.json` e `.sig` sao metadados de atualizacao.

Builds de playtest ainda podem apresentar avisos SmartScreen. A assinatura de atualizacao protege os pacotes, mas nao e um certificado Authenticode Windows.

Servidor em manutencao ou uma release incompativel pode bloquear Jogar. Reporte problemas ao organizador com a versao e os logs do launcher.