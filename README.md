# valida_foto

Valida uma foto para documentos baseada nas bibliotecas [insightface](https://github.com/deepinsight/insightface), [deepface](https://github.com/serengil/deepface) e [face-parsing](https://github.com/yakhyo/face-parsing). Verifica se:
1. Rosto está virado para frente
2. Expressão está neutra
3. Se está usando acessórios (óculos, máscara, chapéu)
4. Iluminação lateral está homogênea
5. Olhos estão abertos

O arquivo `config.json` precisa ser chamado, pois contém os limiares necessários para as verificações.

Ao final retorna um arquivo `results.json` com os atributos das verificações.
