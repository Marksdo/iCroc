# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - Aplicativo de linha de comando Croc para iOS e macOS

Baixe [a versão mais recente na App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Redesenho completo de toda a interface do aplicativo e lógica de operação.
- Atualização da versão embutida do croc para v10.0.8.
- Adição de suporte ao recurso handoff do iOS & macOS.
- Suporte para mais idiomas.

V1.1
---
- Redesign do ícone do aplicativo.
- Correção de bugs e melhorias de desempenho.

V1.0
---
croc é uma ferramenta que permite que dois computadores simplesmente e de forma segura transfiram arquivos e pastas. Até onde eu sei, croc é a única ferramenta de transferência de arquivos CLI que faz todas as seguintes coisas:

- permite que dois computadores transfiram dados (usando um relay).
- fornece criptografia de ponta a ponta (usando PAKE).
- possibilita transferências fáceis entre plataformas (Windows, Linux, Mac).
- permite transferências de múltiplos arquivos.
- permite retomar transferências que foram interrompidas.
- não necessita de servidor local ou redirecionamento de porta.
- primeiro ipv6 com fallback para ipv4.
- pode usar proxy, como o tor.

A aplicação de linha de comando na qual isso se baseia pode ser encontrada aqui:

https://github.com/schollz/croc

## Ative iCroc no macOS nas Configurações
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Enviar arquivos rapidamente com iCroc
- Selecione arquivos no Finder e use abrir com iCroc.
- No Finder, selecione arquivos e use ⌘+C para copiar, depois abra o iCroc e use ⌘+V para enviar os arquivos.
- Arraste arquivos para o iCroc.

# ⚡ Handoff
- Dispositivos iOS e macOS devem ambos ter o aplicativo iCroc instalado.
- Dispositivos iOS e macOS devem ter o recurso Handoff ativado.
- Quando o remetente gerar a frase-código, o iCroc no outro dispositivo receberá automaticamente a frase-código.

# 🔮 Retomar tarefa interrompida
- O remetente reenvia o arquivo e o receptor usa o formato nova frase-código@antiga frase-código, por exemplo: 4161-mambo-young-baby@7611-south-concept-satire.
- O remetente reenvia o arquivo usando o token personalizado como a frase-código anterior.

# 💾 Pasta de recebimento personalizada
- A pasta de recebimento será salva em ~/Downloads/'${frase-código}'.
- Use '@nomeDaPasta' para salvar em ~/Downloads/nomeDaPasta, por exemplo: 8443-siren-mayor-origin@mypics.
- Usar a mesma pasta de destino permitirá retomar automaticamente as tarefas interrompidas.