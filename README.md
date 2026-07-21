## Hotfix 1.2.1

Esta versão corrige a inicialização do Studio Qt no Windows. O viewport é criado antes dos botões da faixa superior, evitando o erro `NablaStudioWindow has no attribute viewport`.

# Nabla Universal Studio 1.1

O Nabla Universal Studio combina uma estação visual 4K com detecção, análise, execução, observação e empacotamento de projetos multiarquivo e multilinguagem. A interface principal é construída em Qt/PySide6, com viewport dominante, zoom/pan, explorer, editor, inspector, targets, terminal, controles de render e bridge direta para os renderizadores do Nabla Render legado.

## Interface Canvas 1.2

A janela principal é um canvas maximizado. A única área persistente além do render é a faixa superior compacta com abas: Arquivo, Projeto, Render, Executar, Avançado e Exibir. Explorer, Editor, Detalhes e Console são painéis ocultos, abertos sob demanda.

O renderer visual padrão é Qt nativo e não importa NumPy durante o bootstrap. O legacy e os módulos avançados são carregados somente quando acionados.

Consulte os demais arquivos do repositório para arquitetura, checklist, suporte de linguagens, segurança, testes e scripts de build.