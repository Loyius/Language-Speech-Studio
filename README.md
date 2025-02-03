# Conversão de Fala em Texto em Tempo Real com Azure Speech Services

Neste projeto utilizei o Azure Speech Services para converter fala em texto em tempo real. A ferramenta permite transcrever áudio falado em diferentes idiomas, detectando automaticamente a língua utilizada. Como aúdio utilizei um trecho de áudio do Bilawal Sidhu, disponível na TED AI Show no link: https://audiocollective.ted.com.

**Funcionalidades Oferecidas pelo serviço:**

Reconhecimento de Fala via Microfone

Detecção Automática de Idioma a partir de um Arquivo de Áudio

Conversão Contínua de Fala em Texto

**1. Reconhecimento de Fala via Microfone (Speech Recognition with Microphone)**

O serviço captura áudio do microfone do usuário e transcreve automaticamente o que foi dito. No exemplo testado, o sistema reconheceu corretamente frases em inglês

🔹 Resultados Obtidos:

Foi feita a transcrição da fala, capturando cada palavra dita.

**2. Detecção Automática de Idioma a partir de um Arquivo de Áudio (Automatic Language Detection)**

Utilizando um arquivo de áudio, o serviço analisa o conteúdo falado e identifica automaticamente o idioma, antes mesmo de iniciar a transcrição.

🔹 Resultados Obtidos:

O áudio foi corretamente identificado como estando em inglês e a transcrição gerada foi coerente com o conteúdo do áudio.

**3. Conversão Contínua de Fala em Texto (Continuous Speech-to-Text)**

Essa funcionalidade permite transcrever fala em tempo real a partir de um fluxo contínuo de áudio. Diferente da abordagem anterior, onde a conversão ocorre por frases isoladas, aqui o sistema acompanha o discurso inteiro.

🔹 Resultados Obtidos:

O serviço acompanhou e transcreveu um longo trecho de fala sem muitas interrupções tendo precisão na identificação do idioma e no conteúdo transcrito

