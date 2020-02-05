# Aplicativo Agenda de Eventos

Aplicativo para tarefas do dia a dia bem simples, que salva as tarefas no armazenamento local, pra isso foi usado uma biblioteca chamada ``AsyncStorage`` do React Native.


## Desenvolvimento

**Imagens do App:**

![PrintScreenApp](https://user-images.githubusercontent.com/54339869/73840832-dd173000-47f7-11ea-8031-9fad62f1b8a5.png)

Para o teclado não ficar por cima da input de adicionar tarefa, foi usa uma biblioteca do React Native chamada ``KeyboardAvoidingView`` com as seguintes propriedade ``<KeyboardAvoidingView
        keyboardVerticalOffset={0}
        behavior="padding"
        style={{ flex: 1 }}   
        enabled={ Platform.OS === 'ios' }    
      >``.
      
**Foi usado duas bibliotecas para os icones:**

``import { Ionicons, MaterialIcons } from "@expo/vector-icons";``

**Código do Botão Excluir com as Propriedades de Icon**

``<TouchableOpacity onPress={() => removeTask(item)}>``

 ``<MaterialIcons name="delete-forever" size={25} color="#f64c75"/>``
   
``</TouchableOpacity>``


**Código do Botão Adicionar com as Propriedades de Icon**

``<TouchableOpacity style={styles.Button} onPress={() => addTask()}>``

``<Ionicons name="ios-add" size={25} color="#FFF" />``

``</TouchableOpacity>``







### Feito com

- Javascript ES6+.
- React Native.
- Expo.

**Programa usado(s):**

- Visual Studio Code.
- Figma



#### Autores

- Leonardo Flores - *Trabalho completo*.

##### Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo -aqui- para obter detalhes
