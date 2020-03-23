# Weather Plus #

* Autor: Adriano Barbieri
* Compatibilidade com o NVDA: 2017.3 até 2019.3
* Baixar: [Versão Estável][1]

# SOBRE O WEATHER PLUS: #

* Este complemento para o NVDA fornece a temperatura local e a previsão do
  tempo atual para as próximas 24 horas e a previsão até 9 días adicionais.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Lançado sob a licença GNU GPL (General Public License — Licença Pública
  Geral) v2
* O Weather Plus funciona com base na utilização e presença dos seguintes
  serviços:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# USO: #

* Pressione NVDA+w para obter informações sobre a temperatura atual e as
  condições climáticas.
* Pressione NVDA+shift+W para obter uma previsão de 24 horas e previsão de
  até 9 dias.
* Pressione NVDA+shift+control+w para definir uma cidade temporária.
* Pressione NVDA+shift+control+alt+w para abrir o diálogo de configurações
  do Weather Plus.
* Pressione NVDA+alt+w para obter a data e a hora em que o boletim
  meteorológico foi atualizado.
* Pressione control+shift+w para alternar entre as escalas de temperatura
  Fahrenheit, Celsius ou Kelvin.

# Configuração do Weather Plus: #

* Você deve configurar o complemento Weather Plus antes de seu primeiro uso! Vá para o submenu Preferências, submenu Configurações do Weather Plus e escolha uma das seguintes opções:
 * Defina e Gerencie Suas Cidades... - Exibe ou permite definir a cidade atual em uma lista.
 * Documentação - Abre o arquivo de ajuda para o idioma atual.
 * Verificar se há atualização... - notifica sobre a disponibilidade da nova versão.

Para adicionar uma nova cidade: pressione o seguinte item:

* Defina e Gerencie Suas Cidades... - Exibe ou permite definir a cidade
  atual em uma lista.
* A seguinte mensagem é exibida apenas pela primeira vez! Configurações
  Predefinição Nenhuma F1: ajuda na localização, F2: seleção do último TAB,
  F3: lista e caixa de edição, F4: controle da duração da previsão do tempo,
  F5: controles de volume.
* Na caixa de edição, insira uma cidade, woeID (Identificador de lugar na
  Terra) ou escolha uma da lista, se disponível. Nota: A tecla F5 estará
  disponível se os efeitos sonoros estiverem ativados.
* Depois de pressionar enter no item "Defina e Gerencie Suas Cidades...",
  você encontrará outros botões, como a seguir:
* Testar - Testa a validade do woeID digitado e encontra o nome da cidade
  atribuída ou vice-versa.
* Adicionar - Adiciona a cidade atual à sua lista. Este botão pode ser
  ativado se você selecionar uma cidade da lista, quando a cidade inserida
  passou no teste.
* Detalhes - Exibe informações sobre a cidade atual. Este botão é ativado se
  você selecionar uma cidade da lista ou se passou no teste.
* Definir - Permite definir a área, a fim de adaptar os efeitos
  sonoros. Este botão pode ser ativado se os efeitos de áudio estiverem
  instalados e ativados, e você selecionar uma cidade da lista.
* Predefinir - Predefine uma cidade como padrão, será usada sempre que você
  reiniciar o plug-in. Este botão é ativado se você selecionar uma cidade
  inserida anteriormente na lista e não predefinida, ou se passou no teste.
* Remover - exclue a cidade atual da sua lista. Este botão pode ser ativado
  se você selecionar uma cidade inserida anteriormente na lista.
* Renomear - renomeia a cidade atual. Este botão pode ser ativado se você
  selecionar uma cidade inserida anteriormente na lista.
* Importar novas cidades... - Este botão permite importar cidades de outra
  lista de cidades com a extensão *.zipcodes; você pode selecionar a cidade
  que deseja importar, ativando a caixa de seleção associada a ela.
* Exportar suas cidades... - Permite salvar as cidades no arquivo
  especificado com a extensão *.zipcodes. Este botão é ativado se você
  adicionou e salvou pelo menos uma cidade na lista.
* Escala de medição de temperatura: use o botão de opção para selecionar
  entre Celsius (por padrão), Fahrenheit e Kelvin.
* Graus mostrados como: Use o botão de opção para selecionar entre: Celsius
  `-` Fahrenheit `-` Kelvin (por padrão) C `-` F `-` K ou Não Especificado.
* Caixa de combinação: previsões do tempo até dias: 3; você pode escolher
  entre 1 a 10 (3 dias por padrão)
* Para executar as seguintes ações, alterne as seguintes caixas de seleção:
* Copia o boletim meteorológico e a previsão do tempo, incluindo os detalhes
  da cidade para a área de transferência; caixa de seleção não marcada (por
  padrão)
* Habilitar efeitos de áudio (apenas para as condições climáticas atuais);
  essa caixa de seleção também permite gerenciar a instalação de efeitos
  sonoros; se os efeitos sonoros estiverem instalados e a caixa de seleção
  estiver ativada, a tecla F5 e a configuração do volume ficam disponíveis.
* Também estará disponível uma caixa de seleção adicional: "Use apenas
  efeitos climáticos".
* Pode alterar o volume geral ou o último efeito sonoro ouvido e filtrar os
  outros sons em seu ambiente. A caixa de seleção não está marcada por
  padrão.
* Use apenas efeitos climáticos - Esta opção estará disponível se os efeitos
  sonoros estiverem ativados; se estiver ativado, permite ouvir apenas
  efeitos climáticos, como chuva, vento, trovão, etc., filtrando todos os
  efeitos ambientais. (desmarcado por padrão)
* Habilitar a leitura das horas no formato de 24 horas. - Se esta caixa de
  controle estiver desmarcada, anuncia a hora no formato de 12 horas, por
  exemplo, 12 AM `-` 12 PM. A caixa de seleção está marcada (por padrão)
* Habilitar os botões de ajuda na janela de configurações; caixa de seleção
  marcada (por padrão)
* Ler as informações do vento; caixa de seleção não marcada (por padrão). Se
  esta caixa de seleção estiver ativada, você também poderá ativar as
  seguintes caixas de seleção:
* Adicionar direção do vento; indica a procedência do vento. Caixa de
  seleção marcada (por padrão)
* Adicionar velocidade do vento; indica a velocidade em quilômetros ou
  milhas por hora. Caixa de seleção marcada (por padrão)
* Adicionar velocidade em metros por segundo do vento; caixa de seleção
  marcada (por padrão)
* Adicionar sensação térmica; caixa de seleção marcada (por padrão)
* Ler informações atmosféricas; caixa de seleção não marcada (por
  padrão). Se ativada, você também pode marcar as seguintes caixas de
  seleção:
* Adicionar valor de umidade; indica a umidade em porcentagem. Caixa de
  seleção marcada (por padrão)
* Adicionar valor de visibilidade; indica em quilômetros ou milhas a
  distância visível. Caixa de seleção marcada (por padrão)
* Adicionar valor da pressão atmosférica; indica a pressão atmosférica em
  milibares ou polegadas de mercúrio. Se estiver marcada, habilita uma caixa
  de seleção adicional que permite indicar a pressão em milímetros de
  mercúrio. Caixa de seleção marcada (por padrão)
* Adicionar estado da pressão barométrica; caixa de seleção marcada (por
  padrão)
* Ler informações astronômicas; indica a hora do nascer e do pôr do
  sol. Caixa de seleção não marcada (por padrão)
* Use a vírgula para separar decimais; se ativado, usa a vírgula como um
  separador decimal; caso contrário, usa o ponto. Caixa de seleção não
  marcada (por padrão)
* Verificar se há atualização; se estiver ativada, este alerta quando houver
  uma atualização do complemento. Caixa de seleção marcada (por padrão)
* Pressione "ok", para confirmar as configurações ou "cancelar", para as
  rejeitar.
* Se você modificou a lista de cidades, pressionando "Cancelar", você será
  lembrado e ainda poderá salvá-la. Nota: suas configurações serão salvas no
  arquivo chamado:
* "Weather.ini": As configurações iniciais do weather plus.
* "Weather.volumes": níveis de volume de áudio personalizados,
  independentemente do volume total.
* "Weather.zipcodes": lista de cidades com o seu código de área e
  definições.
* "Weather_searchkey": chave de pesquisa salva.

--------------------------------------------------------------------------------

# Novidades: #

# Versão 7.4 #

* Corrigida uma falha numa função de pesquisa de cidade.

# Versão 7.3 #

* Corrigido um erro inesperado no caso da página não encontrada durante a
  pesquisa de atualizações.

# Versão 7.2 #

* Corrigido o erro após adicionar uma cidade, se for a primeira inserida, se
  você pressionar o botão ok e reiniciar o complemento.
* Agora o diálogo de progresso mostra novamente o tempo restante e o tempo
  decorrido.
* Corrije a tradução italiana com a ajuda do botão Renomear.

# Versão 7.1 #

* Corrigida falha de atualização.

# Versão 7.0 #

* Janela de pesquisa aprimorada, agora é possível gerenciar toda a chave de
  pesquisa inserida, adicionar, excluir e salvá-la no menu de contexto.
* Controle de abertura de janela aprimorado.
* Algumas pequenas falhas corrigidas.

# Versão 6.9 #

* Implementado a pesquisa de cidades recursivas com o sistema válido usado
  anteriormente na versão Weather_Plus Apixu.
* Pressione f1 na janela de configurações para obter uma explicação dos
  comandos disponíveis.

# Versão 6.8 #

* Atualizada compatibilidade para Python 3.

# Versão 6.7 #

* Corrigida uma falha ao testar uma nova cidade e usá-la no modo temporário,
  basta pressionar "enter" e, posteriormente, tentar adicioná-lo através do
  botão "Adicionar".
* Adicionada abreviação de SOUTH GEORGIA e a SOUTH SANDWICH ISLANDS no banco
  de dados, mas infelizmente no momento parece que as cidades desse Estado
  não funcionam ou têm dados incompletos, esperamos que seja resolvido em
  breve.

# Versão 6.5 #

* Corrigidos alguns bugs na reprodução de efeitos sonoros; alguns ciclos
  "for" com valores máximos incorretos causaram a chamada a um efeito sonoro
  inexistente.
* Corrigida falha na hora local em "detalhes"; A conversão de 12 horas deu
  um erro.
* Corrigida uma falha no relatório de previsão do tempo do Yahoo; em algumas
  cidades, as previsões começam no dia anterior e não no atual. A correção
  dessas cidades implica a perda dos últimos dias da previsão proporcional à
  incompatibilidade de datas (se os dias da previsão estiverem definidos
  como 10).

# Versão 6.4 #

* Horário de verão removido na função "Details" (Detalhes).
* Reprodução de efeitos de áudio aprimorada; agora eles são atualizados
  regularmente se as condições climáticas mudarem.

# Versão 6.3 #

* Corrigidos problemas de codificação.

# Versão 6.2 #

* Corrigida falha na função "Add city" (Adicionar cidade).
* Corrigido o erro que não atribuía a variável "_volume" ao iniciar o
  complemento.
* Adicionado código ausente da versão 6.0; agora você pode recuperar as
  cidades salvas da versão que usa a API do Apixu; os botões "Testar" e
  "Remover" e cidades não compatíveis estão disponíveis no formato:
  "Ferrara, iter 44.83,11.58 0" (cidade, coordenadas geográficas, definição
  de área).

# Versão 6.1 #

* Corrigidos 2 problemas.

# Versão 6.0 #

* O Weather Plus retorna ao uso da API do Yahoo Weather.
* Praticamente todos os recursos da versão anterior 4.8 estão de volta e
  mantém o botão "Renomear".
* Compatibilidade com Python 3.

# Versão 5.0.1 #

* Corrigido bug, que retornava uma string vazia se a velocidade do vento em
  mph fosse 0.
* Corrigido bug que causou efeitos sonoros não consistentes com o fuso
  horário a ser reproduzido.
* Ajustado o número de dias de previsão de 9 para 6 em readme (leia-me).

# Versão 5.0 #

* O Weather Plus agora usa a API APIXU.

# Mudanças na janela Configurações do Weather Plus #

* Removida caixa de seleção antiga "Estado da pressão
  barométrica". Substituído pela nova caixa de seleção "Adicionar valor de
  nebulosidade";
* Fornece a porcentagem de nebulosidade.
* Adicionada nova caixa de seleção "Adicionar valor de
  precipitação". Fornece a quantidade em milímetros da precipitação.
* Caixa de seleção antiga removida "Indica a espera com um bipe enquanto
  você pesquisa o boletim mais recente"; deixado ativo por padrão.
* Adicionadas as informações astronômicas;
* Hora do nascer da lua e do pôr da lua.
* Adicionado novo botão "Renomear"; para renomear cidades de forma mais
  conveniente.
* Função aprimorada do botão "Testar"; agora aceita alguns comandos para
  facilitar a busca por cidades; esses novos comandos são descritos na
  função de ajuda que pode ser chamada com F1.

# Versão 4.8 #

# Mudanças na janela Configurações do Weather Plus #

* Adicionada nova caixa de seleção; "Use apenas efeitos climáticos"; isso
  permite filtrar todos os outros efeitos ambientais.
* Reprodução aleatória aprimorada e adicionado 71 novos efeitos sonoros;
  você precisará atualizá-los clicando duas vezes na caixa de seleção
  "habilitar efeitos de áudio".
* O tipo de volume atribuído pelo usuário, entre o volume de áudio geral e o
  atual, agora é mantido quando a configuração é salva.
* Removido som inútil durante o texto de seleção na caixa de edição
  pressionando control+a.
* Legibilidade aprimorada na janela de ajuda invocável com a tecla de função
  F1.
* Adicionado novo sinalizador (flag) de compatibilidade para NVDA 2019.1, e
  versões alpha atuais.

# Versão 4.7.7 #

* Removida uma notificação desnecessária de download completo quando se faz
  a atualização do Weather Plus.
* Adicionados 6 novos efeitos de som; será necessário atualizá-los a partir
  das configurações do plug-in.

# Versão 4.7.6 #

* Versão com correção de falha.

# Versão 4.7.5 #

* Versão com correção de falha.

# Versão 4.7.3 #

* A função "Details" (Detalhes) foi atualizada por conveniência; as
  informações sobre a altitude são agora fornecidas pelo
  veloroutes.org. Isso leva a pequenas diferenças de pouca relevância.

# Versão 4.7.2 #

* Corrigido um pequeno erro de codificação.

# Versão 4.7.1 #

* Corrigida falha ao obter as informações sobre o fuso horário.

# Versão 4.7 #

* Simplificado a seção de atualização; agora no início, caso haja uma
  atualização disponível, será possível prosseguir diretamente através de
  uma única caixa de diálogo.
* Removido o seletor de arquivos na seção de atualização; agora o arquivo de
  atualização é salvo na pasta temporária, abre a possibilidade de instalar
  a atualização automaticamente, ideal para iniciantes.

# Versão 4.6.9 #

* Localização (tradução) em Árabe adicionada (agradecimentos a Wafik
  Imaculate).

# Versão 4.6.8 #

* Localizações (traduções) atualizadas para localizações (traduções) do
  Português Brasileiro e do Português Europeu (agradecimentos a Alberto
  Mendonça).

# Versão 4.6.7 #

* Melhorado a leitura da hora atual; em algumas cidades, não estava
  correto. Adicionado horário de verão aos detalhes; disponível apenas para
  os países que o adotam.

# Versão 4.6.5 #

* Corrigida uma pequena falha ao ler a hora.

# Versão 4.6.4 #

* Melhorada a leitura da hora local atual; As chaves de procura tornaram-se
  mais precisas.

# Versão 4.6.2 #

* Corrigido bug: após uma verificação de atualizações, o menu "definir uma
  cidade temporária ..." era ativado mesmo que não existisse lista de
  cidades disponíveis.
* Corrigido bug; incapaz de configurar o WP quando o weather.ini ainda não
  tivesse sido criado.

# Versão 4.6 #

* Adicionado o item de menu "Definir uma cidade temporária..."; por uma
  questão de integridade, agora você pode abrir a lista temporária da cidade
  também no menu.
* Aprimorado gerenciamento da escala de temperatura; agora a janela de
  configurações sempre retornará o valor padrão.
* Melhor prevenção de abertura múltipla das janelas principais; se uma delas
  já estiver aberta, além do alerta sonoro, a colocará em primeiro plano.
* Efeitos de áudio aprimorados; agora são baseados no horário local atual da
  cidade em uso.

# Alterações na função do botão de detalhes na janela de configurações #

* Adicionada a hora local atual.
* Corrigido Valor da altitude; agora retorne os valores de altitude quando o
  valor for menor ou igual a zero.

# Versão 4.5.5 #

* Corrige localização (tradução) e documentação em Sérvio.
* Corrijida a localização (tradução) Alemã.

# Mudanças na janela Configurações do Weather Plus #

* Adicionada nova caixa de seleção; você pode ativar a vírgula como
  separador decimal, caso contrário o separador será o ponto.

# Versão 4.5.3 #

* Corrige duas strings (sequências de caracteres) na localização (tradução)
  Russa e Ucraniana.
* Título corrigido da janela Verificar atualização.
* Algoritmo de atualização aprimorado.

# Versão 4.5 #

* Adicionada tecla de atalho NVDA+shift+control+alt+w; Abre o diálogo de
  configurações do Weather Plus.
* Corrije algumas strings (sequências de caracteres) em Inglês.

# Mudanças na janela Configurações do Weather Plus #

* Adicionadas 8 novas caixas de seleção; agora é possível personalizar ainda
  mais a leitura:
* Direção do vento.
* Velocidade do vento.
* Sensação térmica.
* Valor da humidade.
* Valor da visibilidade.
* Valor da pressão atmosférica.
* Indica a pressão atmosférica em milímetros de mercúrio (mmHg).
* Estado da pressão barométrica.

# Versão 4.4.8 #

* Adicionada a tradução em Polaco (Agradecimentos a  Zvonimir Staneczyć).
* Compatibilidade com wx python versão 4.

# Versão 4.4.1 #

* Adicionado suporte a SSL.

# Versão 4.4 #

* Corrigido erro na leitura da nova seqüência de caracteres de versão,
  durante um tempo limite de conexão.
* Melhorado a seção de atualização; agora o diálogo não interfere no menu do
  nvda.
* Revista e corrigida a localização (tradução) Russa.
* Adicionado tradução Ucraniana (agradecimentos a Alex Yeshanu).

# Versão 4.3.4 #

* Revista e corrigida a localização (tradução) Alemã.

# Versão 4.3.3 #

* Foi adicionada a localização (tradução) Alemã (agradecimentos a Karl
  Eick).

# Versão 4.3.2 #

* Foi adicionada a localização (tradução) Romena (agradecimentos a Florian
  Ionașcu).

# Versão 4.3.1 #

* Corrigido um pequeno erro na função "details" (detalhes); as strings
  (sequências de caracteres) "latitude" e "longitude" foram revertidas em
  comparação com o valor.

# Versão 4.3 #

* Weather Plus movido para o "nvda.it" como seu provedor de hospedagem
  padrão.

# Versão 4.2.4 #

* Resolvida uma pequena falha quando a conexão não estava ativa.

# Versão 4.2.3 #

* Agora, o Weather Plus pode executar algumas tentativas de conexão antes de
  notificar o mau funcionamento do WoeId em uso, emite um sinal sonoro a
  cada tentativa; esse bipe, se você quiser, pode ser desabilitado usando
  uma caixa de seleção nas configurações do Weather Plus.

# Versão 4.2.2 #

* Corrigido um erro nas sequências de caracteres de conversão para a escala
  de medição. Em alguns idiomas, Kelvin, Celsius e Fahrenheit não foram
  traduzidos.

# Versão 4.2.1 #

* Corrigido aviso de atualização do Weather Plus durante a inicialização do
  Windows; isso acontece quando foi pressionado o botão "Usar configurações
  atuais salvas no logon e em outras telas seguras (requer privilégios
  administrativos)" nas configurações gerais do nvda, que copia a
  configuração e toda a pasta do complemento para systemConfig, mas elas não
  são sincronizadas com as atualizações subseqüentes dos complementos. Se
  você já usou pelo menos uma vez essa opção, precisará fazê-lo novamente
  uma última vez, logo após ter o Weather Plus atualizado.

# Versão 4.2 #

* Adicionado 5 novos efeitos sonoros; será necessário atualizá-los a partir
  das configurações do plug-in.
* Corrigida falha na função de importação; a lista de cidades não foi
  ordenada alfabeticamente.
* Adicionado modo de importação na função de importação; você pode
  substituir completamente sua própria lista ou simplesmente adicionar novas
  cidades a ela.
* Atualizado a leitura da previsão do tempo, boletim meteorológico atual;
  adicionando a temperatura percebida (vento frio).
* Adicionadas novas sequências de caracteres para a lista dos boletins
  meteorológicos.

# Versão 4.1 #

* Corrigido erro na previsão por até 10 dias; agora, se as estimativas
  recebidas forem em número menor que a solicitação do usuário, os dias
  ausentes serão indicados como desconhecidos.
* Corigida sequência de caractere da entrada de ajuda no comando
  nvda+shift+w.
* Documentação revisada e atualizada.

# Versão 4.0 #

* Atualizadas algumas partes do código e substituídas todas as instruções
  eval().

# Versão 3.9.7 #

* Corrigido erro durante a leitura das previsões meteorológicas; agora as
  temperaturas são lidas corretamente.

# Versão 3.9.6 #

* Alterado o arredondamento na conversão da pressão atmosférica de milibares
  em polegadas de mercúrio; agora o valor é calculado em defeito, enquanto
  antes estava em excesso.

# Versão 3.9.5 #

* Adicionadas duas novas sequências de caracteres para a lista de serviços
  meteorológicos.
* Corrigidos 2 problemas.
* Atualizada execução de sons para o efeito   somente nas condições do
  vento; agora o som do vento pode variar aleatoriamente.

# Versão 3.9.4 #

* Documentações, localizações (traduções) para o idioma Croata e Alemão
  foram removidas; porque elas não são mais suportadas pelos respectivos
  tradutores.
* Falha corrigida na localização (tradução) Sérvia.
* Localização (tradução) Tcheca atualizada.
* Documentação e localização (tradução) atualizadas para Galego.

# Versão 3.9 #

* Mudou novamente a API de serviço; O Weather Plus agora usa a nova API
  Yahoo Weather com as linguagens Yahoo!Query e JQuery:
* A tecla api não é mais necessária.
* Restaurado A busca das cidades homônimas; será possível escolher
  exatamente a cidade desejada em uma lista.
* Otimizado a saída de sons gerais; agora eles estão sincronizados com a
  síntese de voz e são mais rápidos.
* Melhorou o cache para dados off-line; é zerado a cada 10 minutos ou apenas
  mudando a cidade.
* Pressão barométrica medida em mbar (milibares) ou em polegadas de mercúrio
  (se definido como Fahrenheit).

# Versão 3.8 #

* Correções de precisão de dados.
* Habilitado a configuração automática de idioma; agora a API envia os dados
  das condições climáticas no idioma definido pelo nvda.
* Adicionado o cache para boletins e previsões meteorológicas; se não mudou
  a cidade, a escala de graus ou os dias de previsão definidos, você poderá
  ler os dados por 10 minutos, mesmo quando a conexão estiver off-line. O
  cache é redefinido a cada alteração descrita acima. Isso ocorre porque os
  boletins não mudam nesse período e reduzem as chamadas frequentes para a
  API, talvez tocando com efeitos sonoros.
* Pesquisa aprimorada de atualizações; agora uma vez baixada, ela será
  ativada para sua instalação ou, no caso de uma versão portátil do nvda,
  será aberta a pasta em que você salvou a atualização.
* Atualizado todos os sons; agora os sons estão no formato wav.

# Versão 3.7 #

* Foi adicionada a possibilidade de desabilitar a conversão em metros por
  segundo do vento.
* Adicionada a possibilidade de usar a unidade de medida em milhas por
  polegadas quadradas.
* Corrigidos 2 problemas.

# Versão 3.6 #

* Mudado a API de serviço (interface de programação de aplicativos); agora o
  WP usa o serviço oferecido pelo OpenWeatherMap.org em vez do Yahoo
  Weather.com.
* Adicionada classificação de vento no boletim atual.
* Adicionada uma porcentagem de nebulosidade no boletim atual.
* Adotado as unidades de medida de pressão em hectopascal no boletim atual.

# Alterações na janela Configurações do Weather Plus #

* Alterada inserção/pesquisa de código de área/woeId do Yahoo para número de
  ID, identificador da cidade; Os números de ID (identificação) da cidade
  são semelhantes ao woeid, mas o woeId não funcionará mais, igualmente o
  zipcode (código de área) antigo. Você poderá redescobrir grande parte das
  cidades digitando o nome ou parte dele.
* Adicionada inserção/Pesquisa de coordenadas geográficas.
* Adicionada inserção/pesquisa de código postal (CEP).
* Melhorada a função "detalhes".
* Atribuída à tecla F1 a ajuda de inserção/pesquisa.
* Atribuído à tecla F4, os controles para definir as previsões do período de
  1 a 16 dias. Atenção, se você optar por copiar para a área de
  transferência um valor maior que 10, ele não será lido!
* Tecla F5 atribuída para controles de áudio.
* Adicionado escala de medida graus Kelvin.
* Adicionada verificação de atualizações; você pode definir o controle por
  configurações ou verificar manualmente no menu.
* Reatribuído o botão "Localize sua cidade" em "Gerenciamento da sua tecla
  API..."; permite inserir ou alterar a tecla-API.

# Versão 3.5 #

* Adicionada tradução em Croata (agradecimentos a Gordan Radić).
* Adicionado controle para códigos WoeId e Código de Área (Zip Code) não
  válidos encontrados na rede; houve relatos de códigos que pararam de
  funcionar de um dia para o outro, agora o WP alerta se um deles foi
  inserido nas janelas de pesquisa na rede. Se isso ocorrer usando a função
  "Encontre sua cidade...", informe-o para que eu possa atualizar o
  Weather_buffer e removê-lo da lista.
* Corrigido erro de codificação na funcionalidade de pesquisa.
* Atualizada a janela para definir um código de área temporário; recurso
  adicional "Localizar" Como nas outras janelas do Weather Plus: Control+F3
  = Localizar..., F3 = Localizar próximo, Shift+F3 = Localizar anterior.

# Versão 3.4 #

* Adicionada a tradução para Galego. Agradecimentos a Iván Novegil).
* Adicionada a tradução para Português europeu (Agradecimentos a Ângelo
  Miguel Abrantes).
* Adicionada a tradução para Alemão (incompleta).

# Versão 3.3 #

* Adicionada a medida da velocidade do vento, em metros por segundo.
* Correções de codificação.

# Versão 3.2 #

* Atualizado a leitura da previsão do tempo, boletim meteorológico atual e
  leitura da data do boletim meteorológico atual; A Previsão do Tempo do
  Yahoo, de pouco tempo e em quantidades aleatórias, permite passar um
  histórico de -10 a -5 dias de previsão do tempo a ser inserido entre os
  dados atualizados que queremos ler; foi adicionado um filtro que permite
  ler apenas os últimos dados climáticos atualizados, e um sinal sonoro
  discreto alerta quando ele intervém; esse bipe, se você quiser, pode ser
  desativado usando uma caixa de seleção nas configurações do Weather
  Plus. Obviamente, a filtragem de dados às vezes envolve um pequeno atraso
  na resposta, mas ainda é aceitável.
* Previsões do tempo estendida para 10 dias.

# Versão 3.1 #

* Adicionada tradução para Sérvio (agradecimentos a amável cooperação de
  Dejan Gasic).
* Corrigido comando insert+alt+w; não verificava a validade do código de
  área em uso e não verificava se a conexão estava ativa como os outros
  comandos.
* Atualizada a função de reprodução de efeitos sonoros; O formato mp3 agora
  é usado. Agora os arquivos serão muito menores.
* Adicionados 55 novos efeitos sonoros; será necessário atualizá-los a
  partir das configurações do plug-in.

# Alterações na janela Configurações do Weather Plus #

* Corrigida exibição de ajuda nos botões; agora desabilita / habilita em
  tempo real através da caixa de seleção apropriada.
* Adicionados 3 comandos de atalho para navegar mais rapidamente na janela:
* F1 salta para a lista e edita a caixa de código de área.
* F2 retorna para a última seleção alcançada com TAB.
* F3 pula para os controles de volume (se os efeitos sonoros estiverem
  instalados e ativados).
* Adicionado comandos de atalho para todas as caixas de seleção e botões;
  preterido os dois botões de opção, pois estão presentes em sucessão e o
  primeiro é alcançável com o comando contro+shift+w.
* Alterado, o botão "definir" será desativado se os efeitos sonoros não
  estiverem instalados e ativados.
* Adicionados controles de volume; você pode ajustar o volume geral e o
  último efeito sonoro ouvido; essa opção é ativada se os efeitos sonoros
  estiverem instalados e ativados.
* Adicionada Capacidade de definir a hora do sistema no formato de 12 horas
  (12:30 AM `-` 12:30 PM) ou no sistema de 24 horas (12:30 `-` 00:30).

# Versão 3.0 #

* Adicionada a tradução para Eslovaco (agradecimentos a amável cooperação de
  Vitek Jirasek).
* Adicionadas traduções para Português Brasileiro e Português Europeu
  (agradecimentos a amável cooperação de Adair Knaesel).
* Adicionadas novas sequências de caracteres para a lista dos boletins
  meteorológicos.
* Adicionados 171 novos efeitos sonoros, agora a quantidade total é de 213.
* Adicionado comando insert+alt+w, o qual informa a última atualização do
  boletim meteorológico.
* Adicionado scriptCategory que coloca na posição correta as teclas rápidas
  do Weather Plus em "Gestos de entrada..."

# Alterações na janela Configurações do Weather Plus #

* Adicionado botão de opção para definir como indicar a escala de
  temperatura;
* A escolha é entre:
* Celsius `-` Fahrenheit
* C `-` F
* Nenhuma indicação
* Adicionado botão "Definir"; permite definir a zona de uma cidade entre:
* Interior do país
* Região marítima
* Zona de deserto
* Zona do ártico
* Zona de montanha
* A escolha autorizará o Weather Plus a usar efeitos sonoros mais adequados
  para cada cidade; esta é a razão do aumento do número de novos efeitos
  sonoros nesta versão do complemento; muitos dos novos efeitos sonoros eu
  recebi de Tapin, a quem agradeço sinceramente.

# Versão 2.9 #

* Adicionada nova opção ao menu "importar", a qual permite  selecionar o
  conteúdo do arquivo a ser importado.
* Foram adicionados quatro novos efeitos sonoros.
* Adicionada tradução para Russo (agradecimentos a Alex Yeshanu).
* Adicionadda tradução para Tcheco (agradecimentos a Jirimu Holzingerovi).

# Versão 2.8 #

* Corrigido bug em "detalhes", abre a janela de ocorrências quando não
  encontra a cidade.
* Regexp corrigido para procurar a altitude; não aceitava parâmetros de um
  dígito.
* Analisador aprimorado da caixa de edição; deve encontrar mais facilmente a
  cidade.
* Conexões agora manipuladas por urllib2, em vez de urllib; isso deve
  permitir o funcionamento do complemento, mesmo em um computador conectado
  à rede corporativa protegida por proxy.
* Adicionado recurso "Localizar"; Control+F3 = Localizar..., F3 = Localizar
  próximo, Shift+F3 = Localizar anterior.

# Versão 2.7 #

* Corrigido o nome incorreto de uma sequência de caractere "Motorcycle" em
  "Motorcycle00"; ele requisitou efeitos sonoros atualizados porque não
  conseguiram encontrar o arquivo.
* Adicionado capacidade de ler sobre o vento; direção, velocidade e
  temperatura do vento.
* Adicionado capacidade de ler informações atmosféricas; umidade,
  visibilidade, pressão e estado da pressão barométrica.
* Adicionada capacidade de ler as informações astronômicas; hora do nascer e
  pôr do sol.

# Alterações na janela Configurações do Weather Plus #

* Adicionadas 3 caixas de seleção para gerenciar as informações listadas
  acima.
* Adicionado botão "Detalhes"; fornece algumas informações, como o nome real
  da cidade (atribuído pelo Yahoo Weather Forecast), o Estado/região e o
  país ao qual pertence; com coordenadas geográficas e altura acima do nível
  do mar.
* Adicionado reconhecimento do WoeID (códigos de localização, por exemplo,
  Bolonha corresponde a 711080).
* Agora você pode digitar o nome da cidade; nesse caso, se houver, as
  ocorrências serão listadas e você poderá escolher.

# Versão 2.6 #

* As funções dos botões "Adicionar" e "Remover" foram otimizadas no
  gerenciamento de listas do código de área; agora a operação é muito mais
  rápida!
* A função do botão "Testar" foi otimizada, agora explora até 13 chaves de
  pesquisa; Agora, se não encontrar o nome da cidade, é uma verdadeira má
  sorte!
* A função do botão "Localize sua cidade..." agora encontra mais países; foi
  adicionado um teste automático que coleta os códigos de área em
  funcionamento e autoriza ainda uma visualização rápida graças à criação de
  um pequeno buffer correspondente ao nome do país específico.
* Três novos efeitos sonoros foram adicionados; será necessário atualizá-los
  a partir das configurações do plug-in.

# Versão 2.5 #

* Adicionado um comando para alterar temporariamente a escala de temperatura
  entre Celsius ou Fahrenheit, este comando tambén é efetivo na janela de
  configuração.
* Corrigido um erro, se o usuário não pressionou os botões "Adicionar" ou
  "Predefinir", não permite pronunciar o nome da cidade, já que não estava
  incluído na lista.
* Adicionadas novas sequências de caracteres para a lista dos boletins
  meteorológicos.

# Alterações na janela Configurações do Weather Plus #

* Adicionado botão para abrir uma página web de pesquisa com o fim de
  verificar os códigos de área de todo o mundo.
* Adicionada a possibilidade de importar/exportar os códigos de área dos
  seus amigos.
* Adicionada a possibilidade de copiar o boletim meteorológico e a previsão
  do tempo para a área de transferência.
* Adicionada a possibilidade de ouvir efeitos sonoros meteorológicos, a
  opção tambén permite a instalação/atualização dos efeitos de áudio.
* Adicionados botões de ajuda no gerenciamento de códigos de área.
* Mudança no modo de visualização da janela, os menus do NVDA são
  disponibilizados quando estão abertos.

# Versão 2.4.4 #

* Adicionadas duas novas sequências de caracteres para a lista de serviços
  meteorológicos.
* Adição de tradução para Espanhol e Francês (agradecimentos a Pablo Vargas
  e Rémy Ruiz).

# Versão 2.4.3 #

* Adicionada a previsão meteorológica para os próximos 4 días.
* Adição de uma sequência de caracteres na lista dos boletins
  meteorológicos.
* A lista de códigos de área temporários fica agora ordenada depois de cada
  nova inserção.

# Versão 2.4 #

* Foi corrigido um erro que impedía salvar e gerenciar corretamente os nomes
  das cidades que contêm vogais acentuadas.

# Versão 2.3 #
* Removida a caixa de diálogo para estabelecer a escala de medição de
  temperatura tendo sido adicionada uma nova interface gráfica do usuário
  que lhe permite configurar tudo en uma só janela.
* Em seguida, tambén é possível testar / adicionar / remover / predefinir o
  Código de Área ppadrão estabelecido em uma lista.
* Modificada a caixa de diálogo para introduzir, por escrito, um código de
  área, agora, no modo temporário, permite-lhe estabelecer um Código de Área
  previamente adicionado na lista   no menú Preferências.
* Agora a documentação pode ser lida em Inglês, se a configuração do idioma
  não estiver incluída nos documentos.

# Versão 2.2 #

* Solucionado um problema que não lhe permitía abrir a documentação das
  versões estáveis do NVDA.

# Versão 2.1 #

* Foi corrigido um erro que não fechava corretamente o plug-in, o que
  impedía a atualização do ícone do NVDA na bandeja do sistema.

# Versão 2.0 #

* O menu de configuração do Weather Plus    foi movido para  o submenu
  Preferências.
* A entrada correta em tempo real não é mais salva, portanto é temporária;
  para chamar a cidade definida nas preferências, pressione NVDA+control+f3.

# Versão 1.9 #

* Adicionada ajuda para introdução de funções.
* Adicionada uma nova função para digitação rápida de Código de Área.
* Adicionado ao weather.ini configuração de leitura/escrita, agora não é
  mais necessário editar o arquivo de origem.
* Adicionado O menu Weather na bandeja do sistema.
* Adicionado o submenu de configuração Código de Área.
* Adicionada sub-configuração escala de temperatura (Fahrenheit ou Celsius).
* Adicionado menu Documentação.
* Adicionada a localização (tradução) Italiana.

# Versão Inicial 1.1 #

* Atualizado o NVDA-addon.
* Suporte de tradução foi adicionado.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
