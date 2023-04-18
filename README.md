# Language-Logo-List #
  Esse é um repositório que contem as logos das diversas linguagens (de programação ou não) já padronizadas. :D
 - - - - 
## Ressalva ##
  Pretendo no futuro, adiciona uma forma muito melhor do usuário consegui obter as imagens da forma como ele quiser sem ter que baixar o repositório inteiro ou até fica pegando imagem por imagem, mas como ando ocupado (e também procura um emprego :v) irei deixar essa implementação de lado (por enquanto :p).
 - - - - 
## Padrão das imagens ##
  Todas as imagens tem:
  * Tamanho: 256x256 pixels;
  * Formato de arquivo: PNG;
  * Qualidade: 100%;
 - - - - 
## Observações ##
  1. Algumas das linguagens não possuem uma logo oficial, então coloquei alguma coisa que tem coerência com a linguagem;
  2. Parte das linguagens possui mais de uma logo oficial, entretanto coloque apenas a que achei mais combinava;
  3. Tem linguagens que nem logo possui, portanto fiquei à vontade em criar uma logo para essas linguagens;
  4. Fique a vontade para usar as imagens, porém ficaria feliz se você credita o repositório. :)
 - - - - 
## Futuras Adições ##
  - [ ] Ter todas as imagens com o fundo preto e o fundo com alto contraste;
  - [ ] Adicionar mais logos de outras linguagens;
  - [ ] Adiciona as outras logos da mesma linguagem;
  - [ ] Ter pelo menos 3 tamanhos de todas as imagens com todos os fundos;
    - [ ] Pequeno (256x256);
    - [ ] Médio (512x512);
    - [ ] Grande (1024x1024);
  - [ ] Tira todos os serrilhados e pixelizados das imagens
  - [ ] Compressa todas as imagens.
 - - - - 
## Contribuição ##
  Se caso queira contribuir com esse repositório, sinta se à vontade, mas siga todos os padrões estabelecidos, atualize a lista de linguagens e respeite a estrutura as pastas descritas abaixo:
```bash
  ├── background (nome da cor de fundo em inglês, se tive lidando com alto contraste coloque "high contrast")
  │   ├── small
  │   │   └── (nome da linguagem sem abreviações, em caixa alta e com espaços).png
  │   ├── middle
  │   │   └── (nome da linguagem sem abreviações, em caixa alta e com espaços).png
  │   └── large
  │       └── (nome da linguagem sem abreviações, em caixa alta e com espaços).png
  └── language list.txt
```
  Caso, queria adicionar uma outra logo da mesma linguagem:
    * Coloque "-1" no final do nome da logo da mesma linguagem que você esteja adiciona;
    * nomeie os arquivos que vão ser adicionados da seguinte maneira:
        * `(nome da linguagem sem abreviações, em caixa alta e com espaços)-(número natural).png`
  Ex:
> Antes da alteração.
>>
  ```bash
    ├── ...
    ├── JAVASCRIPT.png
    ├── ...
  ```
> Depois da alteração.
>>
  ```bash
    ├── ...
    ├── JAVASCRIPT-1.png
    ├── JAVASCRIPT-2.png
    ├── JAVASCRIPT-3.png
    ├── ...
  ```
 - - - -
