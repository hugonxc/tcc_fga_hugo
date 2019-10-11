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

Retirando da lista anteriormente disposta temos alguns candidatos que seguiram uma bateria de testes para verificar sua utilidade para o projeto. Vão ser considerados o uso na ferramenta, a escrita do código e a forma de armazenamento do código.

- Aria Maestosa - não funfa

Muitas dependencias para instalar:
wxwidgets
libwxgtk3.0-dev
libwebkitgtk-3.0-dev
gir1.2-glib-2.0
libgtk-3-dev
libasound2-dev
Dificil de instalar e não é o que imagino, tá mais pra um grande piano roll pra composição


- Denemo - também não
Instalei dependencias:
  - intltool
  Deu treta com libguile-1.8 também
Não consegui instalar mais rodei no wine e aparenta não ser a solução correta, apenas escreve notas, teria que escrever em formação de acordes


- Frescobaldi
Instalei
pip3 pyqt5
pip3 python-ly

Faltou proplerqt5. Não consegui executar bem também. E só serve para escrever e dps exportar para outros formatos.


- Gregorio
Também dificil de instalar e serve apenas para "escrita" nã reproduz som.

- Impro-Visor


- LilyPond
Error com versão do guile no build
Consigo instalar usando o .sh, tem que chamar como sudo
Lê uma extensão .ly e gera pdf, não envolve audio

- MuseScore
install lame
install libpulse-dev
install libmp3lame-dev
install qtbase5-dev qttools5-dev qttools5-dev-tools qtwebengine5-dev
install qtscript5-dev libqt5xmlpatterns5-dev libqt5svg5-dev libqt5webkit5-dev


- MusiXTeX
Fiz o download do CTAN, mas também só serve para a escrita em latex e conversão para pdf ou outras coisas


- Rosegarden


- MMA
- chord pad
- lemma
- easyabc
- canorus
- linux band
