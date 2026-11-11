#  Threat Intelligence Automator: Integração de Logs com VirusTotal API

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40" alt="Linux / Parrot OS" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" alt="Pandas" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="40" alt="Matplotlib" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" width="40" alt="API REST" />
</p>

## Sobre o Projeto

Projeto de automação desenvolvido em Python para consulta e análise de endereços IP utilizando a API do VirusTotal.

A ferramenta realiza consultas automatizadas, coleta informações sobre possíveis ameaças, processa os dados retornados pela API e apresenta os resultados por meio de tabelas no terminal e gráficos gerados com Matplotlib.

O projeto foi desenvolvido em ambiente Linux (Parrot OS), com foco em automação de consultas, análise de indicadores de comprometimento (IoCs) e visualização de dados relacionados à segurança da informação.

## Objetivo

Automatizar a consulta de endereços IP em uma plataforma de inteligência de ameaças, facilitando a identificação e análise de indicadores potencialmente maliciosos. As consultas foram realizadas por meio da API do VirusTotal, permitindo obter informações sobre a reputação dos endereços IP.

## Funcionamento do Projeto

O processo de análise foi organizado nas seguintes etapas:

1. Inicialização do script Python.
2. Carregamento dos endereços IP que serão analisados.
3. Envio das consultas para a API do VirusTotal.
4. Recebimento das informações retornadas pela API.
5. Processamento e organização dos resultados.
6. Exibição dos dados no terminal.
7. Geração de gráfico utilizando Matplotlib.

## Início da execução

O script inicia a varredura dos endereços IP e apresenta o progresso das consultas realizadas.

<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/bf5bda01-7533-4403-9f90-b55b72152626" />

## Final da análise no terminal 

Ao finalizar as consultas na API, os dados são processados e apresentados em uma tabela no terminal, permitindo visualizar os resultados obtidos para cada endereço IP.

<img width="976" height="505" alt="apis1" src="https://github.com/user-attachments/assets/b3e56573-6570-4ad1-ad7a-a3aee948d1ae" />


## Execução e visualização no Localhost

Após o processamento das consultas, os resultados também podem ser disponibilizados por meio de um servidor HTTP local (Localhost), permitindo visualizar as informações em uma interface acessível pelo navegador.

<img width="875" height="415" alt="apis1 1" src="https://github.com/user-attachments/assets/50b0cd77-dd34-4836-bfc6-594e707bf5f9" />

##  Gráfico gerado com Matplotlib

Ao acessar o localhost é gerado um gráfico de forma autônoma utilizando Matplotlib, facilitando a interpretação visual dos resultados da análise.

<img width="800" height="600" alt="apis2" src="https://github.com/user-attachments/assets/f5026c30-2f94-4bab-bd44-17df8b44f782" />



## Resultados Obtidos

Na execução registrada, o gráfico apresentou 100% dos indicadores classificados como maliciosos segundo o critério utilizado pelo script.

A automação permitiu:

- Realizar consultas automatizadas de endereços IP.
- Integrar Python com a API do VirusTotal.
- Processar informações retornadas pela API.
- Organizar os resultados em formato tabular.
- Gerar visualizações gráficas para facilitar a análise.


## Conclusão

O desenvolvimento deste projeto proporcionou experiência prática com:

- Integração de APIs utilizando Python.
- Automação de consultas de segurança.
- Análise de indicadores de comprometimento (IoCs).
- Processamento e organização de dados.
- Visualização de informações com Matplotlib.
- Utilização de ambiente Linux para desenvolvimento de ferramentas de segurança.

