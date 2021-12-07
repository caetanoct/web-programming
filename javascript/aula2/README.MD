* control structure and loops
```js
        // estruturas de controle
        let num = 100;
        if (num > 100) {
            window.alert(`valor de num é ${num}, maior q 100`);
        } else if (num < 100) {
            window.alert("valor menor q 100");
        } else {
            window.alert("o valor é 100");
        }
        let sw_case = 10;
        switch (sw_case) {
            case 10:
                window.alert("caso 10");
                // break;
            default:
                window.alert("executado default");
                break;
        }
        // estrutura repeticao
        let i = 0;
        while (i < 10) {
            let b = i;
            window.alert("valor="+(++b));
            i++;
        }
        for (i = 0; i < 10; i++) {
            // do sth
        }
```
* Dialog Box
**Alert, confirm, prompt**
alert - informa
confirm - retorna true/false
prompt - mensagem opcional solicitando entrada de texto
```js
let resultado = window.confirm("deseja continuar?");
if (resultado) {
    document.write("<h1>ok</h1>");
}
```
* Events
Ações relizadas sobre algum elemento, clicar em botão ou alterar um objeto etc..
onclick,onblur,onchange...
onblur - quando o usuario deixa um campo/tira o foco
2 formas de inserir evento, inline ou adicionar o elemento por meio do JS.
* Exception Treatmnet
- arquivos
- try catch finally
```js
try {} 
catch (error) {} 
finally {}
```
* DOM - Document object model
uma interface pra documentos HTML. Tudo que está na página html definidos ou não são objetos no javascript.