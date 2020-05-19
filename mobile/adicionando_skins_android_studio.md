# Tutorial para adicionar novas skins no Android Studio

### Download das Skins 

Primeiramente, você já deve ter as skins no seu computador. 

Para baixar as skins da Samsung, acessar [Samsung Developer](https://developer.samsung.com/galaxy-emulator-skin/overview.html)

Após realizar o download, colocar as pastas das respectivas skins dentro no diretório abaixo:

```/home/usuário/android-studio/plugins/android/lib/device-art-resources```

### Cadastrar novo Emulador

Após o passo acima, você deve abrir o Android Studio e seguir os passos abaixo.

1. Clicar em _Tools > AVD Manager_.
2. Clicar na opção _+ Create Virtual Device_.
3. Clicar na opção _New Hardware Profile_.

Nos campos:
- _Device Name_ preencher com a informação que desejar. 
- _Screen Size_: Preencher com o tamanho da tela. 
- _Resolution_: Preencher com a resoluição da tela.

(As informações acima podem ser obtidas acima do botão Download das skins).

4. Na última opção, _Default Skins_, selecionar a sking que foi importada. Caso não aparece na listagem, basta clicar em '...' e buscar no diretório.

Após isso, basta clicar em _Finish_ > _Finish_. 
