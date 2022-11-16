# Inteli - Instituto de Tecnologia e Liderança 

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Banco Pan

## Turing Labs

## Integrantes: 
- <a href="https://www.linkedin.com/in/felipe-pereira-campos-250aa2231/">Felipe Campos</a>
- <a href="https://www.linkedin.com/in/henriquemarlon/">Henrique Marlon</a>
- <a href="https://www.linkedin.com/in/jo%C3%A3o-pedro-gon%C3%A7alves-carazzato-147120231/">João Carazzato</a>
- <a href="https://www.linkedin.com/in/julia-togni/">Julia Togni</a>
- <a href="https://www.linkedin.com/in/melyssa-rojas-221610204/">Melyssa Rojas</a>
- <a href="https://www.linkedin.com/in/mike-mouadeb-24b781224/">Mike Mouadeb</a> 

## 📝 Descrição
Nosso projeto se trata de um modelo preditivo por classificação, que prediz se o cliente é atritado ou não com o Banco Pan, e assim melhorando o sistema de atendimento do próprio banco.
<br>

## 📁 Estrutura de pastas

|--> api<br>
|--> documentos<br>
  &emsp;| T1_G2_V4_5_Predictive_Model_Document.pdf<br>
|--> notebooks<br>
  &emsp;|--> T1_G2_Data_Processing_Development.ipynb<br>
  &emsp;|--> T1_G2_Predictive_Model_Development.ipynb<br>
  &emsp;|--> T1_G2_Tests_Model_Development.ipynb<br>
  &emsp;|--> T1_G2_Deploy_Forms_Development.ipynb<br>
  &emsp;|--> T1_G2_Deploy_Excel_Development.ipynb<br>
| readme.md<br>
| license.txt

Dentre os arquivos presentes na raiz do projeto, definem-se:

- <b>readme.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>documentation</b>: aqui estarão todos os documentos do projeto. Há também uma pasta denominada.

- <b>notebooks</b>: todos os Jupyter Notebooks criados na plataforma Colab para desenvolvimento do projeto.

- <b>license</b>: licença pelo Mit.

- <b>api</b>: aplicação web a partir do modelo escolhido.

## 💻 Execução dos projetos

Todos os notebooks do projeto tem o resultado de execução das células visíveis no próprio repositório Github.

Para replicação (reexecução dos códigos), o botão `Open in Colab` disponível na página do arquivo neste repositório do Github.
> Note que sem salvar uma cópia do notebook no seu Google Drive, não é possível salvar as alterações realizadas no arquivo.

## 📝 Orientações de uso:
<b>Excel:</b>

1. Baixe o notebook predict model que está dentro da pasta notebooks
2. Faça upload do notebook no Google Colab
3. Rode todas as células do notebook
4. Baixe o notebook deploy com excel que está dentro da pasta notebooks
5. Faça upload do notebook no Google Colab
6. Troque o 'nome do arquivo com caminho' pelo seu arquivo com caminho separado por '/'
```sh
df = pd.read_csv('nome do arquivo com caminho')
```
7. Rode todas as células desse notebook

<b>Formulário:</b>

1. Baixe o notebook predict model que está dentro da pasta notebooks
2. Faça upload do notebook no Google Colab
3. Rode todas as células do notebook
4. Baixe o notebook deploy com formulário que está dentro da pasta notebooks
5. Faça upload do notebook no Google Colab
6. Preencha os inputs do formulário de informações do cliente
7. Rode todas as células do notebook

## 📋 Licença/License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL">Turing Labs</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName">Inteli, Felipe Campos, Henrique Marlon, João Carazzato, Julia Togni, Melyssa Rojas, Mike Mouadeb</a> is licensed under <a target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>