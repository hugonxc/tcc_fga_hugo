# Relatório semanal

## Resultados para Atividades planejadas - semana 02 e 03

### Termos de pesquisa - Tipos de notação

#### Leadsheet vs Sheet music

#### "backtrack notation"

### Softwares de acompanhamento

#### Band-in-a-Box

Apesar de ser considerado um software de acompanhamento, o Band-in-a-Box é também uma poderosa DAW. A sua principal funcionalidade é sim gerar trilhas de acompanhamento baseado em cifragem fornecida pelo usuário, porém essa trilha pode ser completada por gravações de outros instrumentos que o usuário deseje incluir. Assim como os outros avaliados até o momento ocorre a falha comum, a limitação em criação dos estilos que a banda virtual irá tocar.
O software conta com diversos recursos: geração de linhas melódicas baseada na harmonia descrita, alteração de tonalidade, mixer de volumes completo, com opções de mudo, solista e outros. A usabilidade acaba sendo um pouco confusa, com um menu muito repleto de funcionalidades, porém creio não ser algo que em algumas práticas venha a ser problemático. Infelizmente o software não conta com versão de teste, logo todas essas observações foram retiradas de vídeos e imagens demonstrativas.

#### Chord pulse

O software apresenta uma interface simples, intuitiva e que agrupa bem os recursos disponiveis. Diferentemente da notação padrão para backtrack ("nome da notação de backtrack") a visualização é feita utilizando blocos os quais são armazenados em páginas. O máximo de blocos permitidos por página são 16. Cada bloco representa um acorde, que pode ser acrescido de tensões e inversões. Finalizando o aspecto de usabilidade, o software apresenta boa consistência nas *hotkeys* utilizadas.
Além disso o sistema oferece outras funcionalidades:

- __Mixer de volume__: controle do volume do áudio dos elementos que compõem a banda virtual (bateria, baixo e piano)
- __Arranjador__: alterar como os instrumentos virtuais da backtrack atuam, por exemplo, retirar bumbo e caixa da bateria em certos momentos da execução da música.
- __Exportar arquivo__: exporta a "musica" como MIDI ou como txt
- __Seleção de estilo__: existem diversos estilos pré-definidos, podendo alterar o tempo (BPM) de execução
- __Seleção de entonação__: permite mudança da tonalidade, tom de referência e frequência base de afinação. Além de seleção de *voicings* para os acordes executados pelo piano.

Entretanto o *Chord pulse* apresenta falhas ao limitar os estilos apenas aos existentes, não havendo possibilidade de personalização ou mesmo criação. E também conta que o usuário tenha um sequenciador MIDI capaz de ser a porta de saída para o áudio.

#### iReal

É um software voltado aos dispositivos mobile, iOS e Android. Possui como principal foco a criação e execução rápida de ("nome da notação de backtrack"). Assim como o *Chord pulse* apresenta boas funcionalidades para a execução e controle da backtrack. Possui também um forúm onde os usuários podem compartilhar músicas entre si, ficando assim mais fácil o acesso a canções e um sistema de exportação das canções em diversos formatos: PDF, MusicXML, iReal format, etc.
No entanto, assim como os outros citados, não possibilita a criação e personalização dos estilos musicais que a banda virtual executa. O software deixa a desejar quanto a usabilidade do editor de acordes, este é bastante confuso e desprende muitos clicas para utilização. Isso prejudica a criação de ("nome da notação de backtrack") de forma mais rápida, deixando assim o processo muito mais trabalhoso e cansativo.

### Scorewriters livres

Partindo da lista de Scorewriters existentes, produzida anteriormente, foram selecionados os projetos de software livre. Esses projetos foram _buildados_ a partir do código fonte e depois utilizados normalmente visando visualizar sua maturidade e experiência de usuário. Durante o proceso notou-se funcionalidades em comum entre os software. Com isso subdividiu-se a lista baseado nesses aspectos:

**Sistema de tracks** - o software possibilita divisão dos instrumentos em faixas
- Aria Maestosa
- Rosegarden

**Escrita em notação formal e Reprodução de aúdio durante a escrita** - o software utiliza a escrita formal como padrão e durante a escrita o respectivo som para cada nota é reproduzido. É possível ainda reproduzir a música na íntegra.    
- Aria Maestosa
- Canorus
- Denemo
- Easyabc
- Impro-Visor
- MuseScore
- Rosegarden

**Escrita em LaTEX e não há reprodução de áudio** - nesse aspecto os softwares não reproduzem áudio, apenas convertem de LaTEX para outros formatos como PDF, JPG.
- Frescobaldi
- Gregorio
- LilyPond
- MusiXTeX


Durante o processo de pesquisa encontrei um novo software que apresentou a caracterstica de **escrita em linguagem própria** para geração automática de acompanhamento.
- **MMA - Music MIDI Accompaniment:** Feito em python e executado em linha de comando, basicamente converte um arquivo _.mma_ contendo especificação de harmonia (usando notação de acordes) e estilo (grooves que também podem ser escritos), de forma própria, para um arquivo _.midi_ que pode ser executado por qualquer player de MIDI ou controlador externo. Para facilitar sua utilização outros projetos se originaram buscando criar GUI para o MMA. Entre eles temos os principais:

- [LeMMA](https://github.com/geksiong/LeMMA)
- [LinuxBand](https://github.com/noseka1/linuxband)

Ambos possuem um editor para escrever os acordes que serão reproduzidos e escolher em qual estilo deve ser tocado. O LeMMA não abre arquivos anteriormente escritos, apenas cria novos. Nenhum dos dois cria ou edita os Grooves.
