# Expressões regulares
Em ciência da computação, uma expressão regular ou "Regex" provê uma forma concisa e flexível de identificar cadeias de caracteres de interesse, como caracteres particulares, palavras ou padrões de caracteres. Expressões regulares são escritas numa linguagem formal que pode ser interpretada por um processador de expressão regular, um programa que serve um gerador de analisador sintático ou examina o texto e identifica as partes que casam com a especificação dada.

__Fonte: https://pt.wikipedia.org/wiki/Express%C3%A3o_regular__

De forma bem resumida, expressões regulares permitem encontrar padrões de textos e manipulá-los.


### Conversão de caracteres para Utf-8 javascript

```javascript
function convertToUTF8(str) {
    return decodeURIComponent(escape(str));
}

// Exemplo de uso
let textoComCaracteresInvalidos = "Por exemplo, o texto com caracteres invÃ¡lidos";
let textoConvertido = convertToUTF8(textoComCaracteresInvalidos);

console.log(textoConvertido); // Saída convertida para UTF-8
```
