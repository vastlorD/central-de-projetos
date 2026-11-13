# Analisador de logs

Exemplo de automação defensiva em Node.js publicado em [Viking/seguranca](https://github.com/vastlorD/viking/tree/main/seguranca).

Lê eventos fictícios de autenticação em JSONL, conta falhas por IP e produz um relatório. É um estudo de análise local, não uma ferramenta de detecção definitiva de ataques.

**Limitações:** não há janela temporal, monitoramento contínuo ou integração direta com logs de sistemas operacionais.

**Próximos passos:** reexecutar testes e avaliar leitura incremental de arquivos grandes.
