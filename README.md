<h1>Prova Processamento Digital de Imagens</h1>
<h2>Transformada de Fourier</h2>
<p>Migra do confuso domínio do tempo para o domínio da frequência que é de fácil compreensão.</p>
<p>A Transformada de Fourier é capaz de separar totalmente as feições de baixa, média e alta frequências.</p>
<h2>Processamento de imagens no domínio da frequencia:</h2>
<h4>Histórico</h4>
<p>matemático e fisíco francês Jean Baptiste Joseph Fourier(1768-1830) demonstrou que qualquer forma de onda pode ser representada por uma somátoria de senoides e cossénoides de diferentes frequências, amplitudes e fases.</p>
<p>A Transformada de Fourier decompõe um sinal em suas componentes elementares seno e cosseno.</p>
<p>Qualquer função f(x) pode ser escrita na forma da soma de uma série de funções seno e cosseno.</p>

<ul>
	<li>a imagem é transformada do domínio espacial para o da frequencia, usando a transformada de Fourier</li>
	<li>Operações sã realizadas nessa imagem</li>
	<li>e para quem possa ser exibida, ocorre o inverso onde a imagem no domínio da frequencia é transformada para o domínio espacial.</li>
</ul>
<p>Na transformada de Fourier não há perda de informação durante a mudança de domínios, apenas a informação visual da imagem está representada de uma outra forma, no domínio da frequencia.</p>
<p>Portanto uma função pode ser decomposta pelo somátorio de senos e co-senos e a transformada de Fourier computa a distribuição( amplitude, frequências e fases)desses senos e co-senos.</p>
<h4>Transformada Discreta de Fourier</h4>
<h5>Transformada rápida de Fourier</h5>
<h2>TEOREMA DA CONVOLUÇÃO</h2>
<p>De forma geral a convolução de uma imagem f(x,y) com uma outra imagem h(x,y) gera uma terceira imagem g(x,y)</p>
<h2>Transformada discreta de Fourier</h2>
<p>O fato de utilizar um número infinito de amostras no domínio do tempo e, consequentemente um número infinito de pontos no domínio da frequencia, representa um problema para implementação da TF na prática(computadores).</p>
<p>Transformada Discreta de Fourier utiliza um número finito de pontos no domínio do tempo e define uma representação discreta do sinal no domínio da frequência</p>
<h3>Algoritmo FFT( Fast Fourier Transform )</h3>
<p>Computa a TFD quando o tamanho N da sequência é uma potência de 2.</p>
<p>Complexidade: n log n contra n ao quadrado para o cálculo pela definição.</p>
<h3>Onde aplicar Fourier</h3>
<p></p>
